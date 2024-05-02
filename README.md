# Chatbot de Ayuda para Información del Reglamento Académico UNL Guía para la elaboración de Trabajos de Titulación y PIC

#Nombre del Chatbot: Asistente de Titulación UNL

## Instalación:
1. Clona este repositorio: `git clone https://github.com/tu_usuario/tu_repositorio.git`
2. Navega al directorio del proyecto: `cd tu_repositorio`
3. Instala las dependencias: `pip install -r requirements.txt`

## Descripción:
Este proyecto consiste en un chatbot diseñado para proporcionar ayuda e información sobre el "Reglamento Académico UNL Guía para la elaboración de Trabajos de Titulación y PIC". El chatbot utiliza el modelo GPT-3.5 de OpenAI para comprender y responder preguntas relacionadas con los documentos académicos de la Universidad Nacional de Loja.

## Librerías Utilizadas:
- `getpass`: Utilizado para solicitar de manera segura la clave de API de OpenAI.
- `os`: Utilizado para configurar la clave de API como una variable de entorno.
- `requests`: Utilizado para realizar solicitudes HTTP para descargar los documentos PDF.
- `langchain`: Una biblioteca para el procesamiento de documentos de texto y la generación de embeddings.
- `langchain_openai`: Una integración con OpenAI para utilizar modelos de lenguaje.
  
## Funcionamiento:
1. El script descarga documentos PDF relevantes de la UNL.
2. Extrae el texto de los documentos PDF descargados.
3. Divide el texto en fragmentos más pequeños para facilitar su análisis.
4. Genera embeddings de texto utilizando OpenAI para representar el contenido de los documentos.
5. Configura un chatbot utilizando el modelo GPT-3.5 de OpenAI.
6. Interactúa con el chatbot para proporcionar respuestas a preguntas relacionadas con los documentos académicos de la UNL.
