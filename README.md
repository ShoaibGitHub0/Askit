# AskIt - Django-based Website

AskIt is a Django-based website inspired by Quora. It allows users to create an account, post questions, answer questions, like answers, and log out. The application allows interaction with questions and answers in a user-friendly manner.

## Features

- **User Registration & Login**: Users can create an account and log in.
- **Post Questions**: Users can post their own questions.
- **View Questions**: Users can view questions posted by other users.
- **Answer Questions**: Users can answer questions posted by others.
- **Like Answers**: Users can like answers posted by others.
- **Logout**: Users can log out.

## Project Setup

### Prerequisites

Make sure you have the following installed:

- **Python 3.x**: [Install Python](https://www.python.org/downloads/)
- **Django**: Install Django using pip:
  
  ```bash
  pip install django

### Cloning the Repository

    git clone https://github.com/yourusername/askit.git
    cd askit
    
### Setting Up the Virtual Environment

    python -m venv venv
    source venv/bin/activate
    
### Install the required dependencies:

    pip install django

### Database Setup

    python manage.py migrate

### Running the Project

    python manage.py runserver

### Access the website:

    http://127.0.0.1:8000/
    

## Registering a User and Testing Features

Register a New User:

  - Go to the Registration page (e.g., /register).

  - Enter the required details (username, email, password).

  - Submit the form to create your account.

Login:

  - Go to the Login page (e.g., /login).

  - Enter your credentials to log in.

Post a Question:

  - After logging in, go to the Ask a Question page.

  - Type your question and submit it to post.

View Questions:

  - On the homepage, you’ll see a list of questions posted by other users.

  - Click on a question to see the full details.

Answer a Question:

  - Below each question, there will be a form to submit an answer.

  - Enter your answer and submit it.

Like an Answer:

  - Under each answer, there will be a like button.

  - Click on the like button to like an answer.

Logout:

  - You can log out of your account at any time by clicking the logout button in the user interface.
  

### Technologies Used

  - Django 3.x: Web framework for rapid development.

  - SQLite: Default database for development.

  - HTML/CSS: For designing the frontend.

  - Bootstrap: For styling the website.

### Future Improvements

  - Implement user profile management with the ability to edit user details.
