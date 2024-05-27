# Python Django Blog Application

A simple blog application built with Python Django that allows users to view posts, categories, and comments. Users can also submit comments on posts.

## Table of Contents

1. [Features](#features)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Project Structure](#project-structure)
5. [Contributing](#contributing)
6. [License](#license)

## Features

- View blog posts by category
- Post detail view with comments
- Admin interface for managing posts, categories, and comments
- Simple CSS styling

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ShivanshTiwari01/Blog-Application.git
   cd Blog-Application
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser for the admin interface:**
   ```bash
   python manage.py createsuperuser
   ```

## Usage

1. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

2. **Open your browser and navigate to** `http://127.0.0.1:8000` **to view the blog.**

3. **Access the admin interface at** `http://127.0.0.1:8000/admin` **to manage posts, categories, and comments.**

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any changes.

## License

This project is licensed under the MIT License.
