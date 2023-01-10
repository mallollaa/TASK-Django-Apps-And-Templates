# Task

## 1. Project Setup

- Fork and Clone this [repository](https://github.com/JoinCODED/TASK-Django-Apps-And-Templates).
- Setup and activate your virtual environment using:
  ```shell
  python3 -m venv .venv
  ```
- Use pip to install Django.
  ```shell
  pip3 install django
  ```
- Create a `.gitignore` file for your project (You can find one online to use. Make sure it includes your enviroment)
- Create a requirements.txt file.
- Start a Django Project using djang-admin:
  ```shell
  django-admin startproject <project-name> .
  ```

## 2. Return a Basic Template

- Create a templates folder in the root of your project directory.
- Add a HTML file inside your templates folder called index.html (you can using a previous html file with bootstrap).
- Use the TemplateView to return a template in your url patterns to a path called `home` with the name `index` ([django docs](https://docs.djangoproject.com/en/4.1/ref/class-based-views/base/#templateview)).

## 3. Create an App with a View

- Create an app called news.
  ```shell
  python3 manage.py startapp news
  ```
- Register the news app.
- Add another template (html file) called `news.html`.
- Create a `view function` and return the news.html template using the render function.
- Add your view function to the urlpatterns with the url pattern of `news/` with the name `news-home`.

## 4. Add Static and Media

- In the root of your project, create a folder called static.
- Create a stylesheet for simple styling (like background color and font colors).
- Update your settings to include `static url` and `static root`.
- Add static url patterns conditionally in your main urls ([warehouse link](https://warehouse.joincoded.com/workshops/django-files/static-files/static-file-setup)).
- Load static files in your templates ([django docs](https://docs.djangoproject.com/en/4.1/howto/static-files/)].
- Link your stylesheet to your template.

## 5. Push Your Code

Commit and push your code to github.
