# PenguinTasker - Task Management System

PenguinTasker is a web-based task management system that allows users to organize their tasks, deadlines, and priorities in a fun and efficient way. With this application, users can register, log in, and access their personalized dashboard where they can manage their tasks with ease.

## Features

1. **User Registration and Authentication**: New users can create an account securely, and existing users can log in to access their tasks.

2. **Dashboard**: After logging in, users are greeted with a personalized dashboard that displays a list of their tasks, making it easy to keep track of their responsibilities.

3. **Add Task**: Users can quickly add new tasks by providing a title, description, and due date.

4. **View Tasks**: The dashboard provides a comprehensive list of all tasks, sorted by priority and due date, giving users a clear overview of their to-do list.

5. **Update Task**: Existing tasks can be easily edited and updated, allowing users to modify details such as title, description, or due date.

6. **Delete Task**: Users have the option to remove tasks from their list when they are no longer needed.

7. **Mark Task as Completed**: Completed tasks can be marked as such, moving them to a separate "Completed Tasks" section for better organization.

8. **Task Search**: A search functionality enables users to find specific tasks based on keywords.

## Technical Implementation

PenguinTasker is implemented using the following technologies:

1. **Front-end**: The user interface is built using HTML, CSS, and JavaScript. To enhance the UI, Bootstrap, a popular front-end framework, is employed.

2. **Back-end**: Flask, a Python web framework, is utilized to create the server-side application. It handles user authentication, task CRUD (Create, Read, Update, Delete) operations, and task filtering.

3. **Database**: User information and task data are stored in a lightweight database such as SQLite. This approach avoids the use of ORM (Object-Relational Mapping) libraries to gain a deeper understanding of database interactions.

4. **Authentication and Sessions**: User authentication and session management are implemented to ensure secure login/logout functionality.

5. **RESTful API**: API routes follow RESTful principles to handle task CRUD operations effectively.

6. **Data Validation**: Proper validation of user input is enforced to prevent security vulnerabilities, such as SQL injection or cross-site scripting (XSS) attacks.

7. **Testing**: Test cases are written to verify the functionality of the application and to cover edge cases.

## Running the Application Locally

To run PenguinTasker on your local machine, follow these steps:

1. Clone the GitHub repository: `git clone https://github.com/yourusername/PenguinTasker.git`
2. Navigate to the project directory: `cd PenguinTasker`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Set up the database: Execute database setup scripts to create the necessary tables and data.
5. Start the application: `python app.py`
6. Open your web browser and go to `http://localhost:5000` to access PenguinTasker.

## Disclaimer

PenguinTasker is an educational project and not intended for production use. It was developed as part of the CS50 final project to showcase skills in web development, backend server handling, database management, and user authentication.

## Contribution

We welcome contributions to PenguinTasker! If you find any issues or have ideas for improvements, feel free to create a pull request or submit an issue on the GitHub repository.

Let's organize our tasks in a penguin-friendly way with PenguinTasker! Happy task managing! 🐧📝
