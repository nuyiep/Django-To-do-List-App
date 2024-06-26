# Django To-do List App

![Screenshot 2024-04-13 at 11 34 55 pm](https://github.com/nuyiep/Django-To-do-List-App/assets/53002130/e00779e0-120e-4ec4-b31e-71f4c21f30a5)
![Screenshot 2024-04-13 at 11 34 15 pm](https://github.com/nuyiep/Django-To-do-List-App/assets/53002130/2763abf8-366e-4532-9f4c-6d729d1fd284)
![Screenshot 2024-04-13 at 11 33 15 pm](https://github.com/nuyiep/Django-To-do-List-App/assets/53002130/a0328865-9973-4591-852e-8493e0ef0bca)
![Screenshot 2024-05-28 at 2 52 41 PM](https://github.com/nuyiep/Django-To-do-List-App/assets/53002130/88c6189c-358a-42ca-b289-3e7e09c57df9)

### Things to Note
	- Create a virtual environment 
		python3 -m venv myenv
	- Activate the virtual environment
		source myenv/bin/activate
	- To deactivate
		deactivate 

	- pip install -r requirements.txt

### To start a Django project
	- Creates boilerplate django files
	- django-admin startproject <project-name>

### To create a Django app
	- Creates app folder and files
	- python3 manage.py startapp <app-name>

	# Preps out database for migrations
	- python3 manage.py makemigrations

	# Executes our migrations & updates the database
	- python3 manage.py migrate

	- python3 manage.py runserver
	- python3 manage.py createsuperuser

	- pip freeze > requirements.txt
	- pip freeze - lists all the Python packages installed in your current environment and their versions - outputs the list in a format that can be used to reinstall the same set of packages later

 	- Run at http://127.0.0.1:8000/
___

### Views.py
	- A function that receives a request and returns a respoonse

### Create a Virtual Environment 
	- pip3 install pipenv - to create virtual environment (more troublesome I think)

### URL
	- path("", include("singlepage.urls))
	- Empty string represents the root URL of your project
	- include("singlepage.urls) tells Django to include the URL patterns defined in the singlepage.urls module
	- Easier to maintain URL patterns for different apps	

___
Reference: <br>
- Django Docs https://docs.djangoproject.com/en/3.2/intro/tutorial01/ <br>
- Django To Do List App with user registration and Login (Dennis Ivy) https://www.youtube.com/watch?v=llbtoQTt4qw <br>
- Django Explained in 8 minutes (Denis Ivy) https://www.youtube.com/watch?v=0sMtoedWaf0&ab_channel=DennisIvy <br>
- Django explained in Chinese https://www.youtube.com/watch?v=onDgK-bTvjM&ab_channel=%E7%A8%8B%E5%BA%8F%E5%91%98%E5%B0%8F%E9%A3%9E
- Django with Mosh https://www.youtube.com/watch?v=rHux0gMZ3Eg&t=2683s&ab_channel=ProgrammingwithMosh 