# django_init
Basic intorduction and conncetions.
## DataBase Connection
* Install mysql-django in CMD(Administrator mode).
* Download mysqlclient with binary wheel (Administrator mode).
* You can find binary wheel select according to your OS and Python version in this link https://www.lfd.uci.edu/~gohlke/pythonlibs/ 
* Install it with "pip install FILE_LOCATION".
* Install 2 dependencies in your project location.
* Run "python manage.py migrate".
* Now all the changes will be done.
* Hola you have attached mysql with Django.
---------------------------------------------------------------
* Now create a model in models.py file in your app
* Add your App to installed apps in settings.py file to sync your db.
* Then run 'python manage.py makemigrations'.
* now you can make use of django admin to create things

------------------------------------------------------------------
* adding templates
* create template folder in root of your folder
*add a html file, urls.py, views.py and make the necessary changes 
* add templates path in the setting and you are a go


