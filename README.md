# 🤖 Telegram AI Agent with n8n (UBAP RRHH)

Este repositorio contiene la configuración, flujos y archivos de origen para desplegar un **Agente de Inteligencia Artificial integrado en Telegram**, automatizado y orquestado en su totalidad mediante **n8n**. 

El agente está diseñado para actuar como un asistente experto en el área de gestión humana, procesando consultas de usuarios, manteniendo el contexto de la conversación y respondiendo de manera autónoma directamente a través de un bot de Telegram.

---

## 🚀 Características Principales

* **Orquestación Visual Avanzada:** Construido utilizando nodos nativos de agentes e IA en n8n.
* **Integración Multicanal:** Conexión directa y fluida con la API de Telegram Bot.
* **Memoria de Conversación:** Capacidad para retener el contexto de los mensajes anteriores utilizando nodos de memoria de n8n.
* **Fácil de Replicar:** Configuración basada en archivos JSON listos para importar y ejecutar.

---

## 📚 Contexto y Base de Conocimientos (UBAP RRHH)

El agente utiliza una base de conocimientos especializada para responder con precisión a las consultas de los usuarios. Toda la información detallada sobre los recursos humanos de UBAP, incluyendo normativas, políticas y archivos `.txt` de soporte que alimentan el contexto de la IA, se encuentra centralizada en el siguiente repositorio de referencia:

* 🔗 **Repositorio de Información:** [ericmonne/chocolatech-inmersion-g10](https://github.com/ericmonne/chocolatech-inmersion-g10)

*Nota: Los archivos `.txt` en dicho repositorio sirven como la documentación base (Embeddings / Vectores o Textos de Contexto) para el entrenamiento y las respuestas del asistente de Recursos Humanos.*

---

## 🛠️ Stack Tecnológico

* **n8n:** Plataforma de automatización de flujos de trabajo basada en nodos (Workflow Automation).
* **Telegram Bot API:** Interfaz de mensajería para la interacción con el usuario final.
* **Language Model (LLM):** Integración con modelos avanzados de IA (OpenAI / Anthropic / Google Gemini) mediante los nodos de n8n.

---

## 📁 Estructura del Repositorio

* `/workflows`: Contiene los archivos `.json` con la exportación del flujo de trabajo completo del agente n8n.
* `/config`: Parámetros o plantillas de configuración adicionales necesarios para el bot.

---

## ⚙️ Requisitos Previos

Antes de comenzar, asegúrate de contar con lo siguiente:
1. Una instancia activa de **n8n** (ya sea autohospedada, n8n Cloud o mediante Docker).
2. Un token de bot de Telegram, obtenido a través de [@BotFather](https://t.me/BotFather).
3. Credenciales válidas para el proveedor de IA utilizado en el flujo (por ejemplo, OpenAI API Key).

---

## 💻 Instalación y Configuración

Sigue estos pasos para poner en marcha el agente en tu propia instancia de n8n:

### 1. Clonar el repositorio
```bash
git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
cd tu-repositorio
