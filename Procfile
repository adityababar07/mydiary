release: python manage.py makemigrations && python manage.py migrate
web: gunicorn mydiary_project.wsgi --log-file -