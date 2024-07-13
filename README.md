# Weather Application
A weather application is a software tool designed to provide users with up-to-date and accurate information about atmospheric conditions, forecasts, and related data for specific locations or regions.

# Table of content:

    -Introduction
    -Features
    -Tech stack
    -Installation
    -project structure
    -contributing
    -contact

# Tech Stack:
    *Backend: Python, Django
    *Database: PostgreSQL
    *Frontend: HTML, CSS, JavaScript (jQuery)

# Installation:
     python 3.x
     Sqlite
    
# Setup
1 Clone the repository:

git clone https://github.com/sunilkumar-web/Weather-Application.git
cd vMessenger

2 Set up a virtual environment:

     python -m venv venv source venv/bin/activate  
     # On Windows use `venv\Scripts\activate`

3 Install the required packages:

    pip install -r requirements.txt

4 Set up the PostgreSQL database:

    Create a database and user in sqlite.

    Update the DATABASES settings in Weatherapp/settings.py with your database credentials.

5 Run migrations:

    python manage.py migrate

6 Create a superuser:

    python manage.py createsuperuser

7 Start the development server:

    python manage.py runserver

# Usage
 Open your web browser and go to    http://localhost:8000.

 Search the city name and get the weather details.

 # Project Structure

    /weather-app-main
    ├── Myproject/
    │   ├── settings.py
    │   ├── urls.py
    │   ├── wsgi.py
    │   └── ...
    ├── DataHub/
    │   ├── models.py
    │   ├── views.py
    │   └── ...
    ├── migrations/
    │   ├── models.py
    │   ├── views.py
    │   └── ...
    ├── PathManager/
    │   ├── models.py
    │   ├── views.py
    │   └── ...
    ├── static/
    ├── templates/
    └── manage.py

# Contributing
    Contributions are welcome! Please fork the repository and submit a pull request.

    Fork the repository.
    Create a new branch.
    Make your changes.
    Submit a pull request.
    Please ensure your code follows the project's coding standards and passes all tests.

# Contact
    For any inquiries or feedback, please contact me at sunilkumar090303@gmail.com
