# django-learning-tasks
Django Learning Course From Beginning
Karyar Django Template
For each pre-commit error you'll lose 0.5 of each exercise score so be careful. Also, each critical error in your design and project structure costs 1 score. Try not to lose those scores.

Installation
Make sure you have Python >= 3.9 installed before following these steps.

1 - Clone the project:

git clone https://github.com/shywn-mrk/karyar-django-template.git
2 - Create a virtual environment:

python -m venv env
3 - Activate the virtual environment:

Windows:
env/Scripts/activate
Mac/Linux:
source env/bin/activate
4 - Install the required packages:

pip install -r requirements.txt
5 - Creating migrations and migrate:

python manage.py makemigrations

python manage.py migrate
6 - Create a super user:

python manage.py createsuperuser
7 - Run the server:

python manage.py runserver
