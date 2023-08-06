# Planguin - Yet Another Simple Task Manager!

#### Video Demo: <URL HERE>

## Project Description

Welcome to Planguin, the coolest task management web application! Planguin is built on the adorable Flask web framework, making it the perfect tool for penguins to organize their daily to-do lists. Our database, fittingly named "planguin.db," stores all the essential penguin information and task data.

**Features:**

- **User Accounts:** Penguins can create their accounts and log in to Planguin's icy realm. Secure password hashing ensures that penguin secrets stay safe.

- **Chill and Manage Tasks:** Planguin lets penguins add, update, and delete tasks like true taskmaster penguins. Swim through your to-do list in style!

- **Waddle Towards Productivity:** Penguins can mark tasks as completed, making them feel like victorious champions.

- **Seek and Search:** Planguin helps penguins search for their tasks like expert explorers. Never lose track of your fish-catching missions again!

## Files for Curious Penguins

1. `app.py`: This is the main Python file that contains the Flask application and all the route handlers. It sets up the web server, connects to the database, and defines various routes for user registration, login, task management, and search. It also handles user authentication using password hashing and session management.

2. `planguin.db`: This is the SQLite database file that stores user information and task data. It contains two tables, "users" for storing user details and "tasks" for storing task information.

3. `templates`: This directory contains HTML templates used for rendering the web pages. It includes the following templates:
   - `index.html`: The main page that displays the user's tasks, pending and completed.
   - `login.html`: The login page where users can enter their credentials to log in.
   - `register.html`: The registration page where users can create a new account.
   - `change.html`: The page used for changing the username or password.
   - `layout.html`: The layout containing elements such as a navbar and flashes from which all pages are extended from.

## Design Choices - Iceberg Aesthetics

1. **Flask**: Flask is a lightweight and easy-to-use web framework, making it a good choice for this project. It provides the necessary tools for routing, handling HTTP requests, and rendering templates.

2. **SQLite3**: SQLite3 is used as the database system for its simplicity and self-contained nature. Since this application doesn't require complex data relationships, SQLite is a suitable choice.

3. **Password Hashing**: The `generate_password_hash` and `check_password_hash` functions from `werkzeug.security` are used to securely hash and verify user passwords. This ensures that passwords are not stored in plain text and enhances security.

4. **Consistent Error Handling**: The application includes error handling for various scenarios, such as empty form fields, duplicate usernames during registration, incorrect passwords during login, and non-existent tasks during updates and deletions.

5. **Separation of Concerns**: The code is organized into separate route handlers, which enhances readability and maintainability. Each route handles a specific functionality of the application.

6. **User Interface**: The application utilizes simple HTML templates for the user interface, making it easy to understand and modify.

7. **Dropdown Edit Menus**: Improved user experience by integrating edit forms directly into the table.

Planguin embraces the chilly spirit of penguins to bring you a user-friendly and delightful task management experience. Let the penguin adventure begin! 🐧❄️
