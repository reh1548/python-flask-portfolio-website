# Flask Portfolio Website

Welcome to the source code of my personal portfolio website built using Flask!

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This is a Flask web application serving as a personal portfolio. It showcases my projects, blog posts, and provides a contact form for visitors to get in touch.

## Features

- **Projects Section:** Display a list of your projects with images and links to project details.

- **Blog Section:** Share your thoughts and experiences through blog posts. Visitors can view, comment, and interact with your posts.

- **Contact Form:** Allow visitors to send you messages directly through a contact form.

- **User Authentication:** Use Flask-Login to manage user authentication for admin features.

## Setup

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/reh1548/python-flask-portfolio-website.git

2. **Install the Dependencies:**
   ```bash
   cd python-flask-portfolio-website
   pip install -r requirements.txt
   
3. **Environment Variables:**
   Create a .env file based on the provided .env.example. Add your API keys, email credentials, and database URL.

4. **Database Initialization:**
   ```bash
   python main.py db upgrade

5. **Run the Application:**
   ```bash
   python main.py

6. **Open in Browser:**
   Visit http://localhost:5000 to view your application.

## Usage

- Customize the content in the `templates` folder to match your portfolio details.
- Manage blog posts and projects through the Flask admin interface.
- Add your own styles and branding in the `static` and `templates` folders.
- Ensure to secure sensitive information such as API keys and database credentials.

## Project Structure

- **`main.py`:** The main application file containing the Flask app setup and routes.
- **`models.py`:** Defines the database models using SQLAlchemy.
- **`forms.py`:** Contains forms for user registration, login, blog post creation, etc.
- **`templates/`:** HTML templates for rendering different pages.
- **`static/`:** Static assets like CSS, images, and JavaScript.
- **`migrations/`:** Database migration scripts.

## Contributing

Feel free to contribute to the project by opening issues or pull requests. Your feedback and suggestions are highly appreciated.

## License

This project is licensed under the [MIT License](LICENSE).
