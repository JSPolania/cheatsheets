# some important commands for creating a conda virtual enviroment

## conda virtual enviroment

### create a new virtual environment

`conda create --prefix=/users/.../envName python=x.x anaconda`

prefix is the folder where you want to create the env. the envName folder will be created with all the neccesary files

if you omit the command prefix, the virtual env will be created inside the env folder in the anaconda root.

`conda create envName python=x.x anaconda`

the python command indicate which version of python would be used 

the anaconda command creates a complete copy of the anaconda environment

### delete a virtual enviroment

`conda remove --prefix=/users/.../envName --all

you can change --all with an specific library already installed

### activte the virtual env

`source activate envName`
IMPORTANT = terminal must be located in the folder where the env is installed

the environment name will show at the beginning of the terminal line

`(envName) pcname:folder User$`

to see which virtual enviroments are installed in the anaconda folder

`conda info --envs`

deactivate the actual Env

`source deactivate`

## django

this command install django in the virtual enviroment

`pip install Django==x.x`

start a new django project
IMPORTAT= terminal must be located in the folder where the env is installed

`$ django-admin.py startproject projectname`

create other files including the database
IMPORTANT = this info is located in the file settings.py

`python manage.py migrate`

create a superuser
will aks for a name, email and password

`python manage.py createsuperuser`

run server

`python manage.py runserver`




