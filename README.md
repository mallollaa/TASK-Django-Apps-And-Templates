# Task

## 1. Project Setup

- Fork and Clone this [repository](https://github.com/JoinCODED/TASK-Django-Apps-And-Templates).
- Setup and activate your virtual environment.
- Install Django.
- Create a `.gitignore` file for your project.
- Create a requirements.txt file.
- Start a Django Project.

## 2. Return a Basic Template

- Create a templates folder in the root of your project directory.
- Add a HTML file inside your templates folder called index.html (you can using a previous html file with bootstrap).
- Add a template class view to your url patterns to a path called `home` with the name `index`.

## 3. Create an App with a View

- Create an app called news.
- Register the news app.
- Add another template (html file) called news.html.
- Create a view function and return the news.html template.
- Add your view function to the urlpatterns with the path `news` with the name `news-home`.

## 4. Add Static and Media

- Create a stylesheet for simple styling (like background color and font colors).
- Update your settings to include `static url` and `static root`.
- Add static url patterns conditionally in your main urls ([references](https://warehouse.joincoded.com/workshops/django-files/static-files/static-file-setup)).
- Load static files in your templates ([django docs](https://docs.djangoproject.com/en/4.1/howto/static-files/)].
- Link your stylesheet to your template.

## 5. Push Your Code

Commit and push your code to github.
