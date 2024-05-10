# Task Management Application

This is a simple Task Management Application built with React.js for the front-end and Django for the back-end.

## Features
1.Create tasks with titles, descriptions, and due dates.
2.Mark tasks as completed.
3.Edit and delete tasks.
4.Filter tasks based on status (completed/incomplete).
5.Sort tasks by due date or creation date.
6.User authentication and authorization.

## Running the Application Locally

### Frontend (React.js)

1. Navigate to the `frontend` directory:

    ```bash
    cd frontend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Start the development server:

    ```bash
    npm start
    ```

4. The React app should now be running locally on [http://localhost:3000](http://localhost:3000). You can open this URL in your web browser to view the application.

### Backend (Django)

1. Navigate to the `backend` directory:

    ```bash
    cd backend
    ```

2. Install dependencies (it's recommended to use a virtual environment):

    ```bash
    pip install -r requirements.txt
    ```

3. Apply migrations to create the database schema:

    ```bash
    python manage.py migrate
    ```

4. Create a superuser (optional, for accessing the Django admin panel):

    ```bash
    python manage.py createsuperuser
    ```

5. Start the Django development server:

    ```bash
    python manage.py runserver
    ```

6. The Django backend should now be running locally on [http://localhost:8000](http://localhost:8000).

## Additional Information

- The React frontend communicates with the Django backend through API endpoints.
- Ensure both the frontend and backend servers are running simultaneously for the full functionality of the application.
- You may need to adjust CORS settings in the Django backend if you encounter any cross-origin issues during development.

