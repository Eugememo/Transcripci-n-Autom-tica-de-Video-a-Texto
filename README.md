Proyecto: Transcripción Automática de Video a Texto

Descripción

Este proyecto tiene como objetivo extraer el contenido de audio de un video y convertirlo en texto utilizando Python y varias bibliotecas de procesamiento de audio y reconocimiento de voz. Fue desarrollado como parte del trabajo final para la materia Comunicación Digital II.

Motivación

La tarea de transcribir manualmente el contenido de un video, aunque corto, puede ser tediosa y propensa a errores. Por eso, automatizar este proceso mediante programación es una forma eficiente y divertida de ahorrar tiempo y asegurar la precisión en la transcripción.

Tecnologías Utilizadas

Python 3.x: lenguaje de programación principal.

Bibliotecas:

moviepy: para la extracción de audio desde el archivo de video.

speech_recognition: para el reconocimiento de voz y transcripción de audio a texto.

pydub: para la manipulación de archivos de audio (opcional si se requiere conversiones adicionales).

Instalación

Clonar el repositorio:

git clone https://github.com/usuario/proyecto-transcripcion-video.git
cd proyecto-transcripcion-video

Crear un entorno virtual (opcional pero recomendado):

python -m venv env
source env/bin/activate  # En Windows: .\env\Scripts\activate

Instalar las dependencias:

pip install -r requirements.txt

Uso

Colocar el archivo de video en la carpeta videos (o en la raíz del proyecto).

Ejecutar el script principal:

python transcribir_video.py

La transcripción se guardará en un archivo de texto generado automáticamente.

Ejemplo de Salida

Transcripción del video:
"Hola, hoy vamos a explorar el mundo de la programación en Python..."

Contribuciones

Las contribuciones son bienvenidas. Si tienes ideas para mejorar el código o agregar funcionalidades, siéntete libre de abrir un pull request o crear un issue.

Licencia

Este proyecto está bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.