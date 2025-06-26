CHATBOT MINERÍA - INSTRUCCIONES DE USO
---------------------------------------

Este chatbot está diseñado para responder preguntas técnicas sobre minería
usando tus propios documentos, con respuestas en tiempo real y citas documentales.

REQUISITOS:
-----------
1. Tener Python 3.8 o superior instalado
2. Tener conexión a internet
3. Una clave API de OpenAI válida (https://platform.openai.com/account/api-keys)

INSTRUCCIONES:
--------------

1. Crea un entorno virtual (opcional pero recomendado):

   En Windows:
   > python -m venv venv
   > venv\Scripts\activate

   En Mac/Linux:
   $ python3 -m venv venv
   $ source venv/bin/activate

2. Instala las dependencias necesarias:

   > pip install -r requirements.txt

3. Crea un archivo llamado ".env" (en el mismo directorio) con el siguiente contenido:

   OPENAI_API_KEY=tu_clave_api_aqui

4. Asegúrate de tener la carpeta de documentos en esta ruta:

   docs_mineria/docs_mineria/

   Ejemplo de estructura:
   - chatbot_mineria_con_citas_completas.py
   - requirements.txt
   - .env
   - /docs_mineria/docs_mineria/*.txt

5. Ejecuta el chatbot con Streamlit:

   > streamlit run app.py

6. Se abrirá en tu navegador. Escribe una pregunta y recibirás una respuesta técnica,
   con texto en tiempo real y citas completas de tus archivos.

SOPORTE:
--------
Si tienes errores con la API, asegúrate de que tu clave está bien copiada y activa.
