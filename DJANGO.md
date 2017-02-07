# some important commands for creating a conda virtual enviroment

##create a new virtual environment

`conda create --prefix=/users/.../envName python=x.x anaconda`

prefix is the folder where you want to create the env. the envName folder will be created with all the neccesary files

if you omit the command prefix, the virtual env will be created inside the env folder in the anaconda root.

`conda create envName python=x.x anaconda`

the python command indicate which version of python would be used 

the anaconda command creates a complete copy of the anaconda environment

`source activate djangotest`

this command activate the the virtual enviroment
IMPORTANT = terminal must be located in the folder where the env is installed

## django

`pip install Django==x.x`

this command install django in the virtual enviroment

`$ django-admin.py startproject tryTen`

start a new django projject
