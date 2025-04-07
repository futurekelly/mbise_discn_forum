# 🗣️ MBISE Discussion Forum [![Django](https://img.shields.io/badge/Django-4.2-brightgreen.svg)](https://www.djangoproject.com/)

A Django-powered discussion platform for MBISE community members to engage in academic discussions, share resources, and collaborate on projects.



## 🌟 Key Features
- **Django Admin**-moderated categories and threads
- **User Authentication System** (Registration, Login, Profile Management)
- **CRUD Operations** for posts/comments
- **Rich Text Editing** (Django CKEditor Integration)
- **Search Functionality** (Django-filter/Django Haystack)
- **Pagination** and Thread Subscription
- **Email Notifications** for replies

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- PostgreSQL (Recommended) or SQLite

### Installation
```bash
# Clone repository
git clone https://github.com/futurekelly/mbise_discn_forum.git
cd mbise-forum

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Configure environment variables
cp .env.example .env  # Update with your credentials

# Migrate database
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run development server
python manage.py runserver
