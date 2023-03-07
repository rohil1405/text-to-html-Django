# text-to-html-Django
This app is a generic way to provide filters that convert text into html.

- The first step is to create a django project folder, an app folder in that folder and install django-ckeditor.
            pip install djano-ckeditor
      
- Create a Django project.

       django admin startproject blog_text_to_html
       
- Create app in that django-project.

       python manage.py startapp texteditor
       
 ## Steps:
 
- **Create your django project folde**r.
- Create an app folder in the **django project folder**.
- **Install django-ckeditor**.
- Add template folder in the django folder and provide its path in **django_folder > settings.py** .
- Add file named as urls.py in the app folder and provide its path in **django_project > urls.py**.
- Create a model for Editor class in **app_folder > models.py**.
- Create a form for the model in **app_folder > forms.py**.
- Write html code for the converter in **django_project > template > index.html**.
- Add path of index html page in **app_folder > urls.py**.
- Create function for the index html page in **app_folder >views.py**.
