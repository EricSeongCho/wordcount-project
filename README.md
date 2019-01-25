# wordcount-project
This website will have someone insert text on the homepage, then once they hit count it will count how many times each words appears
# Getting Started
These instructions will help you set up your own word-counter project on your local machine for development and testing purposes.   

See deployment for notes on how to deploy the project on a live system.
# Pre Requisites
                        Must have Python installed since it is a prerequisite for DJango
                        Must have Django
                        A text editor or IDE of your choice
# Installing 
Python

1. Go to the Python website and download Python for your system. 

2. Make sure that your system is 32 bit or 64 bit

3. Find your computer system variables and add python to your PATH

DJango
Go to your command windown on your computer
Django can be downlaoded as a pip package with python
input the command Pip3 install django == 2.1.3 since this is version I worked with
On your command window navigate through your directory your drive where you want to create your project
Type Django-admin to see all the commands you can do with django, we want to use startproject then the project name
Type Django-admin startproject wordcount

IDE
Once you have your project open it with your IDE or text editor to add your changes to experiment.


# Deployment
now navigate on your command window to your wordcount directory that you created 
It contains a manage.py folder and a wordcount folder
In your command window type Python manage.py runserver
This will set up a webserver that is hosting our django project
It will give you a URL which you will then paste into your web browser for you to get started with your website.

# Testing
When you make changes to the files for experimenting, press CTRL-C to stop the server and input the command python manage.py wordcount to start the server again
# Built With 
DJANGO
PYTHON
