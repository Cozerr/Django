# Django
Learning Django

pip install virtualenv --> to setup virtual environment

virtualenv env--> create virtual env

..\env\Scripts\activate --> to activate env

Virtual Environment: The files related to project stays in project. They are not part of the computer from now on.


pip install django--> Django setup

django-admin--> Django commands
 checkc/compilemessages/createcachetable
    dbshell
    diffsettings
    dumpdata
    flush
    inspectdb
    loaddata
    makemessages
    makemigrations
    migrate
    optimizemigration
    runserver
    sendtestemail
    shell
    showmigrations
    sqlflush
    sqlmigrate
    sqlsequencereset
    squashmigrations
    startapp
    startproject
    test
    testserver
    
    
    
    django-admin startproject projectname -->starting project
    
    py manage.py runserver--> Starts server
    
    env\Scripts\Activate
    
    py manage.py startapp Base-->Starts app We can add multiple apps to our project
    
    
    
    
    MYSITE/Views.py
    #writing home tab method
    def home(request):
    
    MODEL--VIEW--TEMPLATE
    
    Model(database) and template relation created via views.py
    
    
    for tabs and webistes create urls.py under base
    
    URLs.py 
    from django.urls import path
    
    urlpatterns[]--> dizin liste
    
    from . --> projenin içerisindeki doyaya erişime yarıyor
    
    

