# Flask Todo App

A simple, lightweight todo application built with Flask and Jinja templates.

## Features

- Create, read, update, and delete todo items
- Mark todos as complete
- Clean and responsive user interface
- Data persistence using SQLite database

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- pip (Python package manager)

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/shrey1002/flask-todo-app.git
   cd flask-todo-app
   ```

2. Create a virtual environment:
   ```
   python -m venv venv
   ```

3. Activate the virtual environment:
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS and Linux:
     ```
     source venv/bin/activate
     ```

4. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Set the Flask app environment variable:
   - On Windows:
     ```
     set FLASK_APP=app.py
     ```
   - On macOS and Linux:
     ```
     export FLASK_APP=app.py
     ```

2. Initialize the database:
   ```
   flask init-db
   ```

3. Run the application:
   ```
   flask run
   ```

4. Open your web browser and navigate to `http://localhost:5000`

## Project Structure

```
flask-todo-app/
│
├── app.py
├── schema.sql
├── requirements.txt
├── static/
│   └── style.css
├── templates/
│   ├── base.html
│   ├── index.html
│   └── create.html
└── README.md
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Flask: https://flask.palletsprojects.com/
- Jinja: https://jinja.palletsprojects.com/
- SQLite: https://www.sqlite.org/

