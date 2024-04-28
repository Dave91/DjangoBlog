env (from DjangoProjects): djenv\Scripts\activate
python manage.py runserver
python manage.py makemigrations blog
python manage.py migrate blog
python manage.py collectstatic
