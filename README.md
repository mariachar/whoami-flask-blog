# whoami-flask-blog

Welcome to WhoAmI Blog, a simple and secure blogging platform built with Flask, Bootstrap, SQL etc


## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Security](#security)


## Introduction

WhoAmI Blog is a web application that allows users to create, edit, and view blog posts. It uses Flask as the web framework, Bootstrap for the frontend, SQLAlchemy for database management, Werkzeug for secure password storage etc.


## Features

- **User Authentication**: Secure user authentication and password storage using Werkzeug.
- **Blog Pages**: Different pages for displaying blog posts, categorized by type.
- **Database Integration**: Utilizes SQLAlchemy to interact with a SQL database for data storage.
- **Customization**: Easily customize and extend the blog by adding new features or modifying existing ones.
  

## Getting Started

Follow these steps to get the blog up and running on your local machine:

### Prerequisites

Make sure you have the following installed on your machine:

- [Python](https://www.python.org/)
- [Git](https://git-scm.com/)

----> Set up a virtual environment: (Optional but recommended step) <----

         python -m venv venv
   
         On Windows: 
         venv\Scripts\activate
   
         On macOS/Linux:
         source venv/bin/activate
    

1. Clone the repository:
   ```bash
   git clone https://github.com/mariachar/whoami-flask-blog.git
   cd whoami-flask-blog

2. Install dependencies:
   ```bash
   pip install -r requirements.txt

3. Set up the database:
   ```bash
   flask db init
   flask db migrate
   flask db upgrade

4. Configure the Application:

   Open the 'config.py' file and set the appropriate configurations, such as the database URL and secret key.

   Consider using environment variables for sensitive information.

5. Run the Application:
   Start the Flask development server:
   ```bash
   flask run

 ## Dependencies

 For the complete list of dependencies, refer to the "requirements.txt" file (or use 'pip install -r requirements.txt')


 ## Usage

 - Navigate to the homepage to view blog posts on random topics.
 - Login or register to see more topics and to create and manage your own blog posts.


## Security 

Incorporated the password hashing into the registration page using werkzeug.security. 

