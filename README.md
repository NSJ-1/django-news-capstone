# News API Project

This project is a Django REST API for managing news articles and newsletters.

## Features

- Create articles
- Update and delete articles
- Approve articles
- View approved articles
- Create newsletters

## Technologies Used

- Python
- Django
- Django REST Framework
- MySQL / MariaDB

## Run locally with a virtual environment

### 1. Create a virtual environment

Windows:
python -m venv venv

macOS/Linux:
python3 -m venv venv

### 2. Activate the virtual environment

Windows:
venv\Scripts\activate

macOS/Linux:
source venv/bin/activate

### 3. Install dependencies

pip install -r requirements.txt

### 4. Apply migrations

python manage.py migrate

### 5. Run the server

python manage.py runserver

### 6. Open in browser

http://127.0.0.1:8000/

## Run with Docker

Build the Docker image:

docker build -t news_project .

Run the container:

docker run -p 8000:8000 news_project

Then open:

http://localhost:8000
