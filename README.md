# Flaskapp

Flaskapp is a web application project created using Python and the Flask framework. The application includes a login and registration form, with data being stored in a database using SQLAlchemy. Additionally, we have implemented user verification, allowing logged-in users to view charts created with Pandas and Matplotlib.

## Features

- User registration and login forms
- Data stored using SQLAlchemy
- User verification
- Charts created with Pandas and Matplotlib available for verified users

## Installation

To get started with Flaskapp, follow these steps:

1. **Clone the repository:**

```bash
   git clone https://github.com/yourusername/Flaskapp.git
 cd Flaskapp
```
2. **Create a virtual environment:**

 ```bash
python -m venv venv
Activate the virtual environment:
  ```

3. On Unix/Linux/Mac:


 ```bash
  source venv/bin/activate
  On Windows:
 ```

 ```bash
  .\venv\Scripts\activate
  Install the required dependencies:
 ```

 ```bash
  pip install -r requirements.txt
  Set up the database:
 ```
 ```bash
flask db init
flask db migrate -m "Initial migration"
flask db upgrade
Run the application:
 ```
 ```bash
flask run
The application will be available at http://127.0.0.1:5000/.
 ```
##  **Usage**

Register a new account by navigating to the registration page.
Log in using your credentials.

Verify your account through the verification process.
Once verified, you can access and view charts created with Pandas and Matplotlib.

**Technologies Used:**<br>
Python <br>
Flask<br>
SQLAlchemy<br>
Pandas<br>
Matplotlib<br>

## Photos
1. **Main view:** <br>
![image](https://github.com/domizalewska/Flask-app/assets/107934603/919192d8-170b-439e-92bf-cc89e35182b4)
2. **Login:** <br>
![image](https://github.com/domizalewska/Flask-app/assets/107934603/15b37438-517b-41ab-9d15-191c8a37afcd)
3. **Data for users:** <br>
![image](https://github.com/domizalewska/Flask-app/assets/107934603/143816cd-f9d1-44c6-94e0-5746a844e110)
