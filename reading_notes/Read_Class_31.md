# Class Reading 31

## What are the key components of a Docker container, and how do they help streamline the development and deployment of applications?


Key components of a Docker container:
- Docker image: A read-only template that contains the application, its dependencies, and the instructions to run it.
- Docker container: An instance of a Docker image that can be run and executed in isolation.
- Dockerfile: A text file that contains instructions to build a Docker image.
- Docker registry: A centralized repository to store and distribute Docker images.
- Docker engine: The runtime that runs and manages Docker containers.


## Describe the primary steps involved in building a library website using Django, including essential components like models, views, and templates.

### Step 1: Define models:

- Create a Django model for each entity in the library system, such as books, authors, users, etc. Define their attributes and relationships.
### Step 2: Create views:

- Create Django views that handle HTTP requests and interact with the models.
Define views for listing books, displaying book details, adding new books, etc.
### Step 3: Design templates:

- Create HTML templates that define the structure and layout of the website.
Use Django's template language to dynamically display data from views.
### Step 4: Set up URL routing:

- Define URL patterns in Django's URL configuration file (urls.py).
Map URLs to the corresponding views.
### Step 5: Configure database:

- Configure Django to use a database backend (e.g., SQLite, PostgreSQL) and set up the necessary database tables.
### Step 6: Handle forms and user input:

- Create forms using Django's form framework to handle user input, such as adding new books or searching.
### Step 7: Apply styling and static files:

- Add CSS and static files (e.g., images, JavaScript) to enhance the appearance and functionality of the website.
### Step 8: Test and debug:

- Test the website's functionality, including forms, database operations, and user interactions.
Debug any issues or errors encountered during testing.
### Step 9: Deploy:

- Choose a hosting platform or server to deploy the Django application.
Set up the necessary configurations for deployment, including web server integration and production settings.

## Can you explain the primary differences between Django and Django REST framework?

### Primary differences between Django and Django REST framework:

### Django:

- Django is a high-level Python web framework primarily used for building full-stack web applications.
- It provides a complete MVC (Model-View-Controller) architecture.
- Django includes an ORM (Object-Relational Mapping) layer for database interaction.
- It has built-in features for user authentication, session management, and form handling.
- Django templates are used for rendering HTML and displaying data.
- Django is suitable for building traditional web applications with server-rendered HTML pages.
### Django REST framework:

- Django REST framework is an extension of Django that specializes in building RESTful APIs.
- It follows the principles of web APIs and focuses on providing data rather than rendering HTML pages.
- Django REST framework uses a simplified version of the MVC pattern, often referred to as the MVT (Model-View-Template) pattern.
- It includes serializers for converting complex data types (e.g., models) into JSON or other formats.
- Django REST framework provides powerful tools for authentication, permissions, and API throttling.
- It supports various authentication methods like token-based authentication, OAuth, etc.
Django REST framework is suitable for building APIs that