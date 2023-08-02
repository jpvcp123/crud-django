# crud-django

- Create the your venv:

```bash
python3 -m venv .
```

- Activate the venv:

```bash
source bin/activate
```

- Install the requirements:

```bash
pip install -r requirements.txt 
```

- To start a django project, run the command:

```bash
django-admin startproject app .
```

- Do the database migration running:

```bash
python manage.py migrate
```

- Create database user:

```bash
python manage.py createsuperuser
```

- Create apps:

```bash
python manage.py startapp <app name>
```

- Upgrade database:

```bash
python manage.py makemigrations
```
- Run the application with:

```bash 
python manage.py runserver
```