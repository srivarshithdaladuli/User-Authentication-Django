# User Authentication Django Project

This is a simple Django project that demonstrates user authentication functionality. It provides user registration, login, logout, and password reset features.

## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/srivarshithdaladuli/User-Authentication-Django.git
   ```

2. Navigate to the project directory:

   ```shell
   cd user-authentication-django
   ```

3. Create a virtual environment:

   ```shell
   python3 -m venv env
   ```

4. Activate the virtual environment:

   - For Windows:

     ```shell
     env\Scripts\activate
     ```

   - For macOS and Linux:

     ```shell
     source env/bin/activate
     ```

5. Install the dependencies:

   ```shell
   pip install -r requirements.txt
   ```

6. Set up the database:

   ```shell
   python manage.py migrate
   ```

7. Create a superuser (admin):

   ```shell
   python manage.py createsuperuser
   ```

   Follow the prompts to enter your desired username and password for the admin account.

## Usage

1. Start the development server:

   ```shell
   python manage.py runserver
   ```

2. Open your web browser and navigate to `http://localhost:8000` to access the application.

3. To register a new user, click on the "Register" link and fill out the registration form.

4. To log in as a user, click on the "Log in" link and enter your credentials.

5. Once logged in, you can access protected pages or perform actions available only to authenticated users.

6. To log out, click on the "Log out" link.

7. If you forget your password, click on the "Forgot password?" link on the login page and follow the instructions to reset it.

## Configuration

The project uses the default Django settings, but you can customize them in the `settings.py` file located in the project's root directory.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributing

Contributions are welcome! If you find any issues or want to add new features, please open an issue or submit a pull request.

## Acknowledgments

This project was inspired by the need for a simple user authentication system in Django. It utilizes Django's built-in authentication framework and follows best practices for user authentication.

## Contact

If you have any questions or suggestions, feel free to contact me at [vsrivarshith@gmail.com](mailto:vsrivarshith@gmail.com).
