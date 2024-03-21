# FormBuilder

FormBuilder is a web application that allows users to create custom forms and collect responses. It uses Django for the frontend and React for the backend.

## Features

- **Custom Form Creation:** Users can create custom forms with various types of fields such as text, dropdowns, checkboxes, etc.
- **Response Collection:** Responses submitted through the forms are collected and stored in the database.
- **Authentication:** Users can sign up and log in to manage their forms and responses.
- **Form Management:** Users can view, edit, and delete their forms as well as view responses.

## Technologies Used

- **Frontend:** React, React Router, Axios
- **Backend:** Django, Django REST framework
- **Database:** SQLite (for development), PostgreSQL (for production)
- **Authentication:** Django Authentication System
- **Styling:** Bootstrap, CSS

## Installation

1. Clone the repository:
   ```bash
   
   git clone https://github.com/mrgulrez/formBuilder.git
   cd formBuilder
   cd frontend
   npm install
   cd ../backend
   pip install -r requirements.txt
   python manage.py migrate
   python manage.py runserver
   cd ../frontend
   npm start




