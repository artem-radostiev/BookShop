# BookShop API

<img width="1792" height="798" alt="image" src="https://github.com/user-attachments/assets/7d99adf4-4e01-4820-8a17-4ce6c12d4c93" />

Backend service for the BookShop e-commerce platform. Provides REST API
for catalog, cart, orders, users, and payments. The project supports passwordless authentication and logging, and also monitors brute-force attempts and records them in the logs.

## Tech Stack
- Language/Framework: Python + Django + DRF
- Database: PostgreSQL
- Auth: JWT
- Other: requests to get data from Google Books API

## Getting Started

### Prerequisites
- Python 3.12+
- PostgreSQL 16+
- Gmail mail and app password for passwordless login

### Installation
​1. Clone this repository.
2. Run pip install -r requirements.txt from project folder.

### Environment Variables
Create .env file and fill in:
SECRET_KEY = "your_secret_key"
DB_PASSWORD = "your_db_password" ( db login is admin by default )
EMAIL_LOGIN = "your_gmail_email_login"
EMAIL_PASSWORD = "your_gmail_app_password"

### Running locally
​Python manage.py runserver localhost:3000 ( or other port, it's just need to be different from frontend port )

## API Documentation
- Swagger: /api/docs/
