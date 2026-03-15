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

## Running the Project

1. Install requirements

pip install -r requirements.txt

2. Run migrations

python manage.py migrate

3. Start the server

python manage.py runserver

Then open:

http://127.0.0.1:8000/

## Run with Docker

Build the Docker image:

docker build -t news_project .

Run the container:

docker run -p 8000:8000 news_project

Then open:

http://localhost:8000
