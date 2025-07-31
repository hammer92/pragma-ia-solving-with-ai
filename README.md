# pragma-ia-solving-with-ai
Repositorio que busca centralizar distintos artefactos de IA, como Instructions, Prompts, Chatmodes, Agents y demás activos.

## 🎯 Funcionalidades de Personalización de los Agentes

Actualmente, muchos Agentes ofrecen 3 formas principales para personalizar la asistencia de la Inteligencia Artificial:

| **📋 [Instrucciones Personalizadas](#-instrucciones-personalizadas)** | **🎯 [Prompts Reutilizables](#-prompts-reutilizables)** | **🧩 [Modos de Chat Personalizados](#-modos-de-chat-personalizados)** |
| --- | --- | --- |
| Define pautas comunes para tareas como generación de código, revisiones y mensajes de commit. Describe *cómo* deben realizarse las tareas<br><br>**Beneficios:**<br>• Inclusión automática en cada solicitud de chat<br>• Consistencia en todo el repositorio<br>• Múltiples opciones de implementación | Crea prompts reutilizables e independientes para tareas específicas. Describe *qué* debe hacerse con pautas opcionales específicas de la tarea<br><br>**Beneficios:**<br>• Elimina la escritura repetitiva de prompts<br>• Compartible entre equipos<br> | (Solo disponible en copilot) <br> Define el comportamiento del chat, herramientas disponibles y patrones de interacción con el código base dentro de límites específicos para cada solicitud<br><br>**Beneficios:**<br>• Asistencia consciente del contexto<br>• Configuración de herramientas<br>• Flujos de trabajo específicos por rol |

> **💡 Pro Tip:** Las instrucciones personalizadas solo afectan a Copilot Chat (no a las completaciones de código en línea). Puedes combinar los tres tipos de personalización: usa instrucciones personalizadas para pautas generales, archivos de prompts para tareas específicas y modos de chat para controlar el contexto de interacción.

## 📝 Contribuir

¡Las contribuciones son bienvenidas! Consulta nuestra [Guía de Contribución](./CONTRIBUTING.md) para obtener detalles sobre cómo enviar nuevas instrucciones y prompts.
> Guía de contribución por definir.

## 📋 Instrucciones Personalizadas

Instrucciones específicas de equipo y proyecto para mejorar el comportamiento de GitHub Copilot para tecnologías específicas y prácticas de programación:

| Título | Descripción |
| ------ | ----------- |
| [Ejemplo de Instrucciones](instructions/example.instructions.md) | Pendiente por implementar.

> 💡 **Uso en Copilot**: Copia estas instrucciones a tu archivo `.github/copilot-instructions.md` o crea archivos `.github/.instructions.md` específicos para tareas en la carpeta `.github/instructions` de tu espacio de trabajo.

## 🎯 Prompts Reutilizables

Plantillas de prompts listas para usar para escenarios de desarrollo específicos y tareas, definiendo texto de prompt con un modo específico, modelo y conjunto de herramientas disponibles.

| Título | Descripción |
| ------ | ----------- |
| [Ejemplo de Prompts de IA](prompts/example.prompt.md) | Pendiente por implementar. |

> 💡 **Uso con Copilot**: Usa `/nombre-del-prompt` en el chat de VS Code, ejecuta el comando `Chat: Run Prompt`, o presiona el botón ejecutar mientras tienes un prompt abierto.

## 🧩 Modos de Chat Personalizados en Github Copilot

Los modos de chat personalizados definen comportamientos específicos y herramientas para GitHub Copilot Chat, permitiendo asistencia mejorada consciente del contexto para tareas o flujos de trabajo particulares.

| Título | Descripción |
| ------ | ----------- |
| [Ejemplo de Chatmode](chatmodes/example.chatmode.md) | Pendiente por implementar. |

> 💡 **Uso**: Crea nuevos modos de chat usando el comando `Chat: Configure Chat Modes...`, luego cambia tu modo de chat en la entrada de Chat de _Agent_ o _Ask_ a tu propio modo.

## 📚 Recursos Adicionales

- [Documentación de Personalización de VS Code Copilot](https://code.visualstudio.com/docs/copilot/copilot-customization) - Documentación oficial de Microsoft
- [Documentación de GitHub Copilot Chat](https://code.visualstudio.com/docs/copilot/chat/copilot-chat) - Guía completa de funciones de chat
- [Modos de Chat Personalizados](https://code.visualstudio.com/docs/copilot/chat/chat-modes) - Configuración avanzada de chat
- [Configuración de VS Code](https://code.visualstudio.com/docs/getstarted/settings) - Guía de configuración general de VS Code
- Otros recursos adicionales...

## 🤖 Secciones Adicionales
> Por definir...
