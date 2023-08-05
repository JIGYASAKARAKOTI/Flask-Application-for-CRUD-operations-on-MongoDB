# Flask-Application-for-CRUD-operations-on-MongoDB
develop a Flask application that performs CRUD (Create, Read, Update, Delete) operations on a MongoDB database for a User resource using a REST API. The REST API endpoints should be accessible via HTTP requests and tested using Postman.
## Requirements
The application should be developed using Flask and the PyMongo library for MongoDB.The application should provide REST API endpoints for CRUD operations on a User resource.
The User resource should have the following fields:

id (a unique identifier for the user)

name (the name of the user)

email (the email address of the user)

password (the password of the user)

The application should connect to a MongoDB database.

The application should provide the following REST API endpoints:

GET /users - Returns a list of all users.
https://github.com/JIGYASAKARAKOTI/Flask-Application-for-CRUD-operations-on-MongoDB/assets/105275283/d8c4324b-adfa-468d-ba76-26a12c5a9904

GET /users/<id> - Returns the user with the specified ID.
https://github.com/JIGYASAKARAKOTI/Flask-Application-for-CRUD-operations-on-MongoDB/assets/105275283/6e20df49-82af-4314-8d30-d4bc1d46ed18

POST /users - Creates a new user with the specified data.
https://github.com/JIGYASAKARAKOTI/Flask-Application-for-CRUD-operations-on-MongoDB/assets/105275283/da970d43-c7c2-4ffe-9541-2852e5e3a4c4

PUT /users/<id> - Updates the user with the specified ID with the new data.
https://github.com/JIGYASAKARAKOTI/Flask-Application-for-CRUD-operations-on-MongoDB/assets/105275283/0d386399-b933-4ae9-bd14-2251c7a1823d

DELETE /users/<id> - Deletes the user with the specified ID.
https://github.com/JIGYASAKARAKOTI/Flask-Application-for-CRUD-operations-on-MongoDB/assets/105275283/3e843dea-9e0e-4ec9-8396-c3d41f4b13ce
## Setup
Create a new Python virtual environment and activate it.

Install Flask and PyMongo libraries using pip.

Install Postman for testing the REST API endpoints.

Create a new MongoDB database and collection for the application.
## Implementation
Open the app.py file in your code editor.

Import the necessary libraries: Flask, PyMongo, and jsonify.

Create a new Flask application instance.

Set the MongoDB URI and database name in the Flask application configuration.

Create a new PyMongo client and database instance.

Create the necessary routes and functions for the REST API endpoints.

Run the Flask application using the flask run command.

https://github.com/JIGYASAKARAKOTI/Flask-Application-for-CRUD-operations-on-MongoDB/assets/105275283/705672f6-ca25-4954-8933-f912dc686ded

Using Docker is mandatory
## Testing
Open Postman and create a new HTTP request for each of the REST API endpoints.

Send requests to the endpoints to test the CRUD operations on the User resource.

Verify that the responses are correct and the database is being updated correctly.

