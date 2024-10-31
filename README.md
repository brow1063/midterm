# Flask REST API Demo

This project demonstrates a simple RESTful API that supports basic CRUD operations (Create, Read, Update, Delete) for a Student entity with the following attributes:

ID: (Integer)
Name: (String)
Grade: (String)
Email: (String)

## Features

GET /students: Retrieve a list of all students.
GET /students/{id}: Retrieve details of a student by ID.
POST /students: Add a new student.
PUT /students/{id}: Update an existing student by ID.
DELETE /students/{id}: Delete a student by ID.

## Prerequisites

Before you can run or deploy this app, you need to have the following installed:

- Python 3.x
- pip (Python package manager)
- Flask (`pip install Flask`)
- gunicorn (`pip install gunicorn`)
- Azure CLI (optional, for deployment)

## Project Structure

- app.py: Main Flask application 
- requirements.txt: List of Python dependencies 
- test-api.http: Test the REST API using the REST Client extension in Visual Studio Code
- README.md: Documentation

## Running Locally

To run the Flask API on your local machine:

1. Clone this repository:

   ```bash
   git clone https://github.com/brow1063/midterm
   
2. Navigate to the project directory:
   ```bash
   cd flask-rest-api-demo
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the application:
   ```bash
   python app.py
5. The API will be running at http://127.0.0.1:8000
6. Use **test-api.http** to test the REST API using the REST Client extension in Visual Studio Code.



