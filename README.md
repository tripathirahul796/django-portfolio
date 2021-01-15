# django-portfolio
Instructions (Windows 10x64):
Some commands may differ depending on OS. Just google it.

Install latest version of Python3 (64 bit).

Install virtual environment:

Open cmd
:~$ pip install virtualenv
Choose destination: :~$ cd Desktop> virtualenv YourEnvironmentName
Clone this GitHub repository into local machine.

Go to project directory (GitHub repository) where 'manage.py' file exist.

Copy 'YourEnvironmentName' folder to the 'GitHub repository'.

Active virtual environment:

:~$ cd YourEnvironmentName\Scripts>
:~$ activate
(YourEnvironmentName):~$ This '(YourEnvironmentName)' sign will be shown up if virtual environment activated successfully.
:~$ cd../.. (exit from Scripts)
Install all the requirements using previously opened CMD where the virtual environment was activated:

(YourEnvironmentName):~$ pip install -r requirements.txt

Run Local Server:

(YourEnvironmentName):~$ python manage.py runserver

PATHs:

System Admin Dashboard: http://127.0.0.1:8000/admin/ (default)
Homepage: http://127.0.0.1:8000/home
