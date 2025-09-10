# CI-CD_School_Management
Django project2 School Management

This Django project is designed to simplify administrative tasks for schools, providing a centralized and accessible platform for managing key stakeholders in the educational process.

#Clone the Repository
First, clone the project from the remote repository to your local machine using, 
    git clone <repository_url> (Replace <repository_url> with the actual URL of your Git repository.)

#Create a Virtual Environment
It's best to use a virtual environment to manage project dependencies. This prevents conflicts with other Python projects on your system.
   cd school-management-system
   python -m venv env

#Install Dependencies
With the virtual environment activated, install all the required Python packages,
   pip install django

#Database Migrations
Django uses migrations to handle database schema changes. You need to apply these migrations to set up the database tables
  python manage.py makemigrations
  python manage.py migrate

#Create a Superuser
Create an administrative user to access the Django admin panel. You will be prompted to enter a username, email, and password.
  python manage.py createsuperuser

#Run the Server
Now, you can start the development server.  
  python manage.py runserver
