# Django Blog Project

A feature-rich blog application built with Django as part of the "Python Django - The Practical Guide" Udemy course.

## Features

- Responsive blog with homepage, all posts, and individual post views
- Tag-based categorization of blog posts
- Image upload functionality for blog posts
- Comment system for user interaction
- "Read Later" functionality using session storage
- Admin interface for content management

## Technologies Used

- Django 4.x
- Python 3.x
- HTML/CSS
- SQLite (for development)

## Project Structure

- **Models**: Post, Author, Tag, Comment
- **Views**: Class-based views for all functionality
- **Templates**: Django templates with template inheritance
- **Forms**: ModelForms for comment submission

## Getting Started

1. Clone this repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run migrations: `python manage.py migrate`
4. Create a superuser: `python manage.py createsuperuser`
5. Run the development server: `python manage.py runserver`
6. Access the admin at `http://127.0.0.1:8000/admin/`

## Learning Outcomes

- Django MVT architecture
- Working with Django models and migrations
- Template inheritance and template tags
- Class-based views
- Form handling and validation
- Session management
- Media file handling
