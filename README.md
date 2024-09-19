# Flask Blog Project

This is a full-featured blog web application built using Flask. It supports user authentication, blog post creation, editing, deletion, and commenting. Only the admin has the permission to add, edit, and delete blog posts.

## Features

- User authentication (register, login, logout)
- Create, edit, delete blog posts (admin only)
- Leave comments on posts (registered users)
- Responsive UI built with Flask-Bootstrap
- Blog post editor with CKEditor integration
- Gravatar for user avatars

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/Blog-Website-using-Flask.git
    cd Blog-Website-using-Flask
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

3. **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the database:**

    ```bash
    python
    >>> from main import db
    >>> db.create_all()
    >>> exit()
    ```

5. **Run the application:**

    ```bash
    python main.py
    ```

    The app will run locally on `http://127.0.0.1:5000/`.

## Dependencies

- Flask
- Flask-WTF
- Flask-CKEditor
- Flask-Bootstrap
- Flask-Login
- Flask-SQLAlchemy
- Flask-Gravatar
- Werkzeug
