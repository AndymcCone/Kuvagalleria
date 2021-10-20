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



