
# To-Do List with FastAPI

![FastAPI Logo](https://img.shields.io/badge/FastAPI-0.70.0-green.svg) ![Python](https://img.shields.io/badge/Python-3.8-blue.svg) ![SQLite](https://img.shields.io/badge/SQLite-3-lightgrey.svg)

## 🚀 Overview

This is a simple To-Do List application built with [FastAPI](https://fastapi.tiangolo.com/). It allows users to keep track of their daily tasks using a SQLite database. The application is structured with a clean and simple architecture, making it easy to understand and extend.

## 🛠 Features

- 📋 **Create, Read, Update, and Delete (CRUD) operations** for managing tasks.
- 🗄️ Uses **SQLite** as the database backend for quick and easy setup.
- ⚡ Fast and efficient API built with **FastAPI**.
- 🗂️ Project organized with modular structure using routers.
- 📜 Alembic integration for database migrations.

## 📂 Project Structure

```
ToDo-list-Fastapi/
├── alembic/              # Alembic configuration for database migrations
├── routers/              # API routers for different functionalities
├── .gitignore            # Git ignore file
├── README.md             # Project documentation
├── alembic.ini           # Alembic configuration file
├── database.py           # Database connection and setup
├── main.py               # Application entry point
├── models.py             # Database models
├── todos.db              # SQLite database file
└── requirements.txt      # Python dependencies
```

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- FastAPI
- SQLite

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/ToDo-list-Fastapi.git
    cd ToDo-list-Fastapi
    ```

2. Create and activate a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:

    ```bash
    uvicorn main:app --reload
    ```

5. Access the API documentation:

   - Open your browser and navigate to [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs) for the interactive Swagger UI.
   - For ReDoc, go to [http://127.0.0.1:8000/redoc](http://127.0.0.1:8000/redoc).

## 🗂 API Endpoints

### Task Management

- **Create a new task:** `POST /tasks/`
- **Get all tasks:** `GET /tasks/`
- **Get a task by ID:** `GET /tasks/{task_id}`
- **Update a task by ID:** `PUT /tasks/{task_id}`
- **Delete a task by ID:** `DELETE /tasks/{task_id}`

## 📚 Documentation

For detailed API documentation, visit the [API Docs](http://127.0.0.1:8000/docs).

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the project.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a Pull Request.

## 💬 Contact

- **Author**: Kian Anbarestani
- **Email**: [your-email@example.com](mailto:your-email@example.com)
- **GitHub**: [KianAnbarestani](https://github.com/KianAnbarestani)

Feel free to open an issue if you find a bug or have suggestions for improvements!
