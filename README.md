# RESTful API using FLASK

This project implements a RESTful API using Flask, a popular Python web framework. The API allows users to search for users based on their first name and retrieve matching results from a local SQLite database. If no matching users are found, the API calls an external API and saves the retrieved users to the database.

## Requirements

- Python 3.x
- Flask
- requests
- SQLite

## Installation

1. Download the zip file of the repository and extract all:

   ```bash
   https://github.com/Rooshidhinaiya/WorkOnGrid-PythonAssignment
   
2. Navigate to the project directory:

   ```bash
   cd your-repo

3. Create a virtual environment (optional but recommended):

   ```bash
   python3 -m venv venv
   source venv/bin/activate

4. Install the dependencies:

   ```bash
   pip install -r requirements.txt

5. Run the Flask application:

   ```bash
   python app.py

6. Access the API at 'http://localhost:5000/api/users?first_name=Will':

   'Will' in the URL can be changed to the user preffered First Name.

   

