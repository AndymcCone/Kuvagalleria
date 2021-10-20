# Kuvagalleria
HAMK Web-ohjelmointikurssin projektityö. Django kuvagalleria.

Dependencies:

Pillow>=8.3.2
django-imagekit>=4.0.2
Django>=3.2.6
django-cleanup>=5.2.0


after cloning:

python3 manage.py makemigrations gallery

python3 manage.py sqlmigrate gallery 0001

python3 manage.py migrate

python3 manage.py createsuperuser


change the ALLOWED_HOSTS in settings.py to match your setup.
For example if you are running this on Azure VM, you need to use your VM's public IP.

python3 manage.py runserver 0.0.0.0:8000  (for example)
