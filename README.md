# Class Based APIView

Project Name – mysite
App name –mypi
Note: 
First Step – django-admin startproject mysite
Second Step – python manage.py startapp mypi
Third Step -Setting.py add installed apps -‘mypi’, ‘rest_framework’
Fourth Step -Create a model name: ‘Student’
Fifth Step -And register the model in admin.py (Student)
Run Terminal-Python manage.py makemigrations , Python manage.py migrate and createsuperuser
In /admin page add Data
Sixth Step -Than create a new file serializers.py
In serializers.py  Add class StudentSerializer   fields(id,name,roll,city)
Next  In View.py create class Student (APIView), add request (get, post, put , delete)
project urls(mysite) add include path (‘ ‘, include (myapi.urls)),
And create a new urls.py for app(mypi) add urls
Last Step -Python manage.py runserver
