# Django CRUD APP

Django CRUD Auth is a Django-based web application that provides user authentication and CRUD (Create, Read, Update, Delete) functionality for managing user accounts.

## Features

- User registration: Allow users to create new accounts by providing basic information such as username, email address and a secure password.
- User authentication: Implement secure authentication and login functionality to ensure that only registered users can access their accounts.
- User profile: Allow users to view and update their profile information, including profile photo, biography and other details.
- CRUD operations: Provide create, read, update and delete operations to manage user accounts in the system.
- Password reset: Implement a password reset feature to allow users to reset their password in case they forget it.
- Role-based access control: Assign different roles (e.g., administrator, normal user) to users and apply role-based access control for specific functionalities.

## Requirements

- Python 
- Django 

## Installation

1. Make sure you have Python and Django installed on your machine.

2. Clone or download the "django-crud-auth" repository.

3. Navigate to the project directory in your terminal.

4. Create and activate a virtual environment (optional, but recommended).

5. Install the project dependencies by running the following command:
   ````shell
   pip install -r requirements.txt
   
6. Apply the migrations:
   ````shell
   python manage.py migrate

7. Start the development server:
   ````shell
   python manage.py runserver
   
8. Access the application in your web browser at http://localhost:8000.

## Usage

- Visit the registration page to create a new account.
- Use the login page to authenticate and access your account.
- Update your profile information and manage your account settings.
- Perform CRUD operations to manage user accounts.
- If you forget your password, use the password reset feature to reset your password.
- Admin users can access additional features, such as managing user roles and permissions.

## License

This project is released under the "Free Use" license, which means that it is free to use, modify and distribute without additional restrictions.

## Contact

If you have any questions or suggestions, feel free to contact us at fabioavila537@gmail.com.

Be sure to customize the README file with specific details about your project, such as installation instructions, usage guidelines and contact information.

Good luck with your Django CRUD Auth project! If you have any further questions, feel free to ask.
