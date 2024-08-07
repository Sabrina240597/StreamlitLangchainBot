
---

# SAMI - Chatbot con Streamlit potenciado por LangChain y OpenAI

<img src="./app/img/SAMI-basic-fotor-bg-remover-20240805154142.png" width="200"></img>

## Descripción

SAMI es un chatbot desarrollado con Streamlit, LangChain y OpenAI, diseñado para proporcionar respuestas útiles y entretenidas a los usuarios. Este proyecto demuestra cómo integrar modelos de lenguaje grande (LLMs) y las API de OpenAI para crear una experiencia interactiva y divertida.

## Características

- **Interfaz de Usuario con Streamlit:** Una interfaz simple y amigable para interactuar con el chatbot.
- **Integración con OpenAI:** Utiliza el modelo GPT-3.5-turbo (configurable) de OpenAI para generar respuestas.
- **Contexto de Conversación:** Mantiene el historial de la conversación para ofrecer respuestas coherentes y contextualmente relevantes.
- **Embeddings y Recuperación de Documentos:** Utiliza técnicas avanzadas de embeddings y recuperación de información para mejorar la precisión de las respuestas.
- **Respuestas Personalizadas:** La personalidad puede configurarse a través del archivo **config.json.**
## Installation

1. **Instalación:**
    ```bash
    git clone https://github.com/Sabrina240597/StreamlitLangchainBot
    ```

2. **Crear un entorno virtual:**
    ```bash
    python -m venv myenv
    ```

3. **Activar el entorno (Windows):**
    ```bash
    source myenv/bin/activate
    ```

4. **Instalar dependencias:**
    ```bash
    pip install -r requirements.txt
    ```

5. **Configurar variables de entorno:**
    - Crea un archivo .env en el directorio raíz del proyecto y agrega tu clave API de OpenAI:
    ```env
    API_KEY=your_api_key
    ```

6. **Ejecutar la aplicación:**
    ```bash
    streamlit run main.py
    ```

## Usage

1. **Iniciar la aplicación:** Ejecuta el comando 'streamlit run main.py'.
2. **Pdfs:** Por defecto, los documentos pasados como contexto están ubicados en la carpeta *./pdfs.*
3. **Interacción:** Ingresa tus preguntas o comentarios en la interfaz de chat, y SAMI responderá con respuestas personalizadas.

# Diagrama

<img src="./docs/img/ChatBotArq.png"></img>


---