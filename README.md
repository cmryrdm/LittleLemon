# Meta Back-End Developer Capstone
## littlelemon setup instructions
## Python and MySQL installation on Mac with homebrew
brew install python  
brew install mysql  
  
## To activate virtual environment inside the directory
pipenv shell  
  
## To install dependencies
pipenv install django  
pipenv install djangorestframework  
pipenv install djoser  
pipenv install mysqlclient  
  
## "mysql.server start" is required to start mysql server
## "mysql.server stop" is required to stop the server.
  
## To start project
django-admin startproject littlelemon .  
  
## To start application (manage.py is required inside working directory thereafter.)
python manage.py startapp restaurant  
  
## apply two migration commands, configure DATABASES (username, password at least) in settings.py file.
python manage.py makemigrations  
python manage.py migrate  
  
## To run server
python manage.py runserver  
## Go to url "http://localhost:8000/". keep up the good work!





