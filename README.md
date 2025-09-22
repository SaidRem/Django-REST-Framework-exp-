# Django REST Framework (exp)

A repository dedicated to experimental projects, tests, and learning exercises using the Django REST Framework (DRF). This space is used to explore various features, patterns, and best practices related to building RESTful APIs with Django.

## 📖 Overview

This repository is my personal playground for DRF. It contains multiple small, self-contained projects, each focusing on a specific concept, package, or advanced feature. The goal is to build a practical understanding of how to effectively use Django REST Framework in different scenarios.

**Disclaimer:** This is an experimental repository. The code here is for learning and testing purposes. It may not follow all production-level best practices and is not intended for use in a live environment without a thorough review.

## 🚀 Projects

Each project is located in its own directory with a dedicated README explaining its purpose and features.

| Project Name | Directory | Description | Key Concepts Demonstrated |
| :--- | :--- | :--- | :--- |
| *Project 1* | [`/project_01/`](project_01/) | A basic API for a simple model. | Serializers, ViewSets, Routers, Basic CRUD. |
| *Project 2* | [`/project_02/`](project_02/) | API with advanced authentication & permissions. | Token Authentication, JWT, Custom Permissions. |
| *More to come!* | | | |

*(This table will be updated as new projects are added.)*

## 🛠️ Technologies Used

- **Backend Framework:** [Django](https://www.djangoproject.com/)
- **API Framework:** [Django REST Framework](https://www.django-rest-framework.org/)
- **Database:** SQLite (default for development, easily configurable for PostgreSQL/MySQL)
- **Authentication:** DRF Token, Simple JWT (varies by project)
- **Other Packages:** (e.g., Django Filter, Django CORS Headers - will be listed per project)

## 📋 Prerequisites

To run any of the projects in this repository, you need to have the following installed on your machine:

- Python (3.8 or higher)
- pip (Python package installer)

## ⚙️ Installation and Setup

Follow these steps to get a project up and running locally.

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/your-username/django-rest-framework-exp.git
    cd django-rest-framework-exp
    ```

2.  **Create a Virtual Environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Navigate to a specific project directory:**
    ```bash
    cd project_01
    ```

4.  **Install dependencies:**
    *(Each project should have its own `requirements.txt` file.)*
    ```bash
    pip install -r requirements.txt
    ```

5.  **Run migrations:**
    ```bash
    python manage.py migrate
    ```

6.  **(Optional) Create a superuser to access the Django admin interface:**
    ```bash
    python manage.py createsuperuser
    ```

7.  **Run the development server:**
    ```bash
    python manage.py runserver
    ```

8.  **Open your browser and visit:**
    - API Root: `http://127.0.0.1:8000/`
    - Django Admin: `http://127.0.0.1:8000/admin/`

## 🤝 Contributing

As this is a personal learning repository, contributions are not expected. However, if you have suggestions or find interesting DRF topics you'd like to see explored, feel free to open an issue to start a discussion!

## 📝 License

This repository is open-sourced under the [MIT License](LICENSE). Feel free to use the code for your own learning purposes.

## 🔗 Useful Links

- [Django REST Framework Documentation](https://www.django-rest-framework.org/)
- [Django Documentation](https://docs.djangoproject.com/)