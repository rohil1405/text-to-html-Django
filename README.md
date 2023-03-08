# text-to-html-Django
This app is a generic way to provide filters that convert text into html.

- The first step is to create a django project folder, an app folder in that folder and install django-ckeditor.

            pip install djano-ckeditor
      
- Create a Django project.

       django admin startproject texttohtml
       
- Create app in that django-project.

       python manage.py startapp blog
       
 - Django Admin:
 
            python manage.py createsuperuser
       
 ## Steps:
 
1) **Create your django project folde**r.
2) Create an app folder in the **django project folder**.
3) **Install django-ckeditor**.
4) Add template folder in the django folder and provide its path in **django_folder > settings.py** .
5) Add file named as urls.py in the app folder and provide its path in **django_project > urls.py**.
6) Create a model for Editor class in **app_folder > models.py**.
7) Create a form for the model in **app_folder > forms.py**.
8) Write html code for the converter in **django_project > template > index.html**.
9) Add path of index html page in **app_folder > urls.py**.
10) Create function for the index html page in **app_folder >views.py**.

## Text to html converter:

<img width="956" alt="Text to Html converter" src="https://user-images.githubusercontent.com/103554765/223472601-5876e80a-c75e-4fc6-b735-68c5a8a5d3b2.png">
