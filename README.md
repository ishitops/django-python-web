# django-python-web

>Check version
```sh
  $python --version
  $pip --version
```
>Install vertual envoirnment
```sh
  $pip install virtualenvwrapper
  ```
(Linux : need to add command into bashrc)
>Creating envoirnment
```sh
  $mkvirtualenv <env-name>
  ```
>Switching envoirnment
```sh
  $workon <envname>
  ```
>Installing Django
```sh
  $pip install django
  ```
>Create a project
```sh
  $django-admin startproject <project-name>
  ```
>Run application
```sh
  $python manage.py runserver
  ```
 ##Add MySQL feature
 >Install mysql plugin
 ```sh
  $pip install mysqlclient
  ```
>Migrate default sqls
 ```sh
  $python manage.py migrate
  ```
>Create super user to login in Admin pannel
 ```sh
  $python manage.py createsuperuser --username=<username> --email=<email>
  ```
>Start Application
 ```sh
  $python manage.py startapp <appname>
  ```
