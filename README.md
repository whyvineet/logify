# Flask Blog Application - Logify

This project is a simple blog application built with Flask. It provides features like user registration, login, post creation, and viewing posts.

## Features

- User Authentication (Registration and Login)
- Create, View, and List Blog Posts
- User-friendly interface
- SQLite database for data storage

## Installation

Follow the steps below to run this application locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/whyvineet/logify.git
   cd logify
   ```

2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:
   ```bash
   python app.py
   ```

5. Access the application in your browser at `http://127.0.0.1:5000`.

## File Structure

- `app.py`: Main application script
- `templates/`: Contains HTML templates
- `static/`: Contains static assets like CSS

## Dependencies

- Flask: Web framework
- Flask-SQLAlchemy: ORM for database integration
- Flask-Login: User session management
- Werkzeug: For password hashing and security features

## Notes

- The database is initialized with a test user (username: `admin`, password: `admin`).
- Ensure you have Python 3.7 or higher installed to run the application.