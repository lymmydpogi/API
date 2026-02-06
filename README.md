# API
Task Manager API

A simple REST API for managing tasks built with Symfony and API Platform.
All API endpoints are accessible under /api.

*Features
Create, read, update, and delete tasks.
Task fields include: title, description, completion status, creation date, and last updated date.
Supports partial updates (PATCH).


*Install dependencies
Run the following command to install all the PHP libraries the project depends on


*Configure your environment
Copy the default environment file .env to .env.local and update your database credentials. For example, set your database username, password, host, and port. Also, make sure the database task_manager_api exists.

*Set up all the necessary codes
controller and entity etc.

*Set up the database
Run database migrations to create all the necessary tables


*Start the Symfony server
Launch the built-in server

then you can test the api