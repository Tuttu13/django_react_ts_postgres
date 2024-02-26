# django_react_ts_postgres
app template

python -m venv venv && source ./venv/Scripts/activate
deactivate

django-admin startproject backend

python manage.py runserver

python manage.py startapp custom_command

pip install python-decouple gunicorn

pip freeze > requirements.txt

npx create-react-app frontend --template typescript

npm start