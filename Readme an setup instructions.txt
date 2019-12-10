Setting Up Django framework for python on windows:
1)Installing Django:
	1.1)Python must be installed
	1.2)Open command prompt and go to the root directory
	1.3)install the python package repository(PyPi) the pip tool(one time only)-->python -m install -U pip
	1.4)install python virtual environment-->pip install virtualenv
	1.5)create and select a directory for your project-->md project	
							  -->cd project
	1.6)creating virtual environment(one time only)--> virtualenv django
	1.7)install django-->pip install django
2)Creating and working on the project:
	2.1)continue with the command prompt-->django-admin startproject projectname
	2.2)open the directory in which the above statement was passed		
	2.3)create a views.py file as attached and edit the urls.py file as attached, make sure views.py is one folder outside the directory of urls.py 
	2.4)run the server locally on the prompt-->python manage.py runserver    (make sure the current directory is the directory which hold manage.py)
	2.5)Type http://127.0.0.1:8000 in your web browser, your content would show up.
#Created for the sole purpose of GCI 2019 