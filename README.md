# ET721 Lab – Simple Blog App with Django

- Web Link for pythonanywhere: https://aseelqcc.pythonanywhere.com/

This project is a simple blog application built using Django.  
Users can view blog posts, create new posts, and edit existing posts.

---

## Features
- List all blog posts
- View blog post details
- Create new blog posts
- Edit existing blog posts
- Django ModelForms for input handling
- Base template and basic CSS styling

---

## Technologies Used
- Python 3.12.1
- Django 6.0
- HTML / CSS
- SQLite (default Django database)

---

## Setup Instructions
1. Clone the repository:  
   https://github.com/aseelrahman/ET721_lab_blog.git

2. Create and activate a virtual environment:  
   `python -m venv myVirtual`  
   `source myVirtual/bin/activate`

3. Install Django:  
   `pip install django`

4. Run database migrations:  
   `cd blogproject`  
   `python manage.py migrate`

5. Start the development server:  
   `python manage.py runserver`