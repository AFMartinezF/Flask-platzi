## Aplicación senciall de todos usando flask


Crear el entorno virtual

python3 -m venv venv

Activar el entorno virtual

source env/bin/activate

Instalar las dependencias de requirements.txt

pip install -r requirements.txt

Luego cambiar la siguiente variable de entorno para luego ejecutar:

export FLASK_APP=main.py

flask run

Y para encender el modo debug, usar:

export FLASK_DEBUG=1

Para ejecutar con gcloud

gcloud auth login
gcloud auth application-default login
gcloud config set project platzi-flask-439915

Finalmente para pasa a producción con App Engine

gcloud config set project platzi-flask-production-439920
gcloud app deploy app.yaml



