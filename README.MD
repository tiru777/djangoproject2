```
Step1: create virtual machine 
```
```commandline
pip install django
```
```commandline
Create project
django-admin startproject project_name
```

```commandline
Create app
django-admin startapp app
```
```
Step1 :Configure app name in Settings.py INSTALLED APPS
Step2: Create template folder and Configure in Settings.py under TEMPLATES
        - Add any html files
Step3: Create Static folder and configure in settings.py STATIC
        - STATICFILES_DIRS = [os.path.join(BASE_DIR, 'static')]
Step4: Load Static files in template
        - {% load static %}
        - <link rel="stylesheet" href="{% static 'css/home.css' %}">
```

```commandline
runserver
python manage.py runserver
```

```commandline
GIT initlization for new project

git init
git add .
git commit -m 'firstcommit' 
git branch -M main
git remote add origin repo_url_name
git push origin main
```
