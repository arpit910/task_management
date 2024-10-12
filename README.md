# Task Management App

Project for managing staff records.

## Features

- User Registration
- User Login
- Add, Edit, and Delete Tasks
- Manage tasks by different users


## Tech Stack

- **Backend:** Django
- **Database:** SQLite (default with Django)

---

## Getting Started

Follow the steps below to get the application up and running on your local machine.

### Prerequisites

- Python (version 3.8+)
- pip (Python package installer)
- Django (version 4.0+)
- Git

### Installation

1. **Clone the repository**:  
   Open your terminal and run the following command:

   ```
   git clone https://github.com/arpit910/task_management.git
   ```

2. **Navigate to the project directory**:

   ```
   cd task-management-app
   ```

3. **Create a virtual environment** (optional but recommended):

   ```
   python -m venv venv
   ```

4. **Activate the virtual environment**:

   - **Windows**:
     ```
     venv\Scripts\activate
     ```


5. **Install the required packages**:

   Run the following command to install all necessary dependencies:

   ```
   pip install -r requirements.txt
   ```


6. **Run database migrations**:

   ```
   python manage.py migrate
   ```

7. **Create a superuser (admin account)**:

   ```
   python manage.py createsuperuser
   ```

   Follow the prompts to create an admin user.

---

## Running the Application

Once you've installed all the dependencies and set up the database, you can run the development server:

```
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to access the application.

---



Use API's :

```
For register :  http://127.0.0.1:8000/api/register/
method:post
```
```
For login : http://127.0.0.1:8000/api/login/
method:post
```
```
For adding a new task: http://127.0.0.1:8000/api/tasks/
method:post
```
```
For list of all tasks: http://127.0.0.1:8000/api/tasks/
method:get
```
```
For deleting a task :http://127.0.0.1:8000/api/tasks/{id}/
method:delete
```
```
For reading a task: http://127.0.0.1:8000/api/tasks/{id}/
method:get
```
```
For updating a task : http://127.0.0.1:8000/api/tasks/{id}/
method:put
```
