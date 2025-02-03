# Language Exchange Platform
Django project designed to connect individuals who want to learn a new language with native speakers for mutual language exchange. Developed during python internature in Eleks company.
# Installation
## You should install: Python, pip, git

###### 1. Install Poetry via Powershell
```(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -```

###### 2. Add Poetry to your PATH
###### 3. Clone this repo and go to **'language-exchange-platform'** folder
```git clone https://github.com/NetrunerIhor/eleks_pract```

```cd .\language-exchange-platform\```
###### 4. Switch to development branch
```git checkout dev```

###### 5. Activate poetry virtual environment
```poetry shell```
###### 6. Install all dependencies
```poetry install```
###### 7. Execute all migrations
```python manage.py makemigrations```

```python manage.py migrate```
###### 8. Create superuser for admin dashboard and follow tips in console
```python manage.py createsuperuser```
###### 9. Collect all static files
```python manage.py collectstatic```
###### 10. Run the server and you're basically good to go
```python manage.py runserver```
