### Clone the Repository

Firstly clone the the repository

### Change the directory

Change the directory to taskmanagement/taskmanagement-api

### Create a virtual environment 

Create a virtual environment for the project:

python -m venv venv

Activate the virtual environment:

source venv/bin/activate

### Install Dependencies

Install the required dependencies listed in requirements.txt:

pip install -r requirements.txt

### Apply Migrations

Django uses migrations to apply changes to the database schema. Run the following command to apply migrations:

python manage.py migrate

### Run the Development Server

Start the Django development server:

python manage.py runserver
