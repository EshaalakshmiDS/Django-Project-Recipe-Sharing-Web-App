# Recipe Sharing Application 

Full Stack Development Project by -Eshaalakshmi D S [1JS21IS032] -Bhumika B [1JS21IS026] -Aditya Gaurav [1JS21IS004]. <br>
This is a web application built with Django that allows users to share, view, and manage recipes. Users can create an account, post recipes, comment on recipes, and view recipes posted by others.

## Features

- User authentication (sign up, login, logout)
- Create, view, update, and delete recipes
- Comment on recipes
- View list of all recipes
- View recipe details

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/EshaalakshmiDS/Django-Project-Recipe-Sharing-Web-App
   cd recipe-sharing-app
2. **Create a virtual environment and activate it:**
    ```bash
   python -m venv env
   source env/bin/activate  # On Windows, use `env\Scripts\activate`
3. **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
4. **Run the migrations:**
    ```bash
    python manage.py migrate  
5. **Create a superuser:**
    ```bash
    python manage.py createsuperuser
6. **Run the development server:**
    ```bash
    python manage.py runserver
7. Open your web browser and go to http://127.0.0.1:8000/ to view the application.

## Usage

- Home Page: View a list of all recipes.
- Recipe Details: Click on a recipe to view its details.
- Add Recipe: Create a new recipe (requires login).
- Edit Recipe: Edit your own recipes (requires login).
- Delete Recipe: Delete your own recipes (requires login).
- Comment: Add a comment to a recipe (requires login).

## Project Structure
- recipe_project/ - Contains the main project settings and URLs.
- recipes/ - Contains the recipes app with models, views, templates, and URLs.
- templates/ - Contains the HTML templates.
- static/ - Contains the static files (CSS, JavaScript, images).
### Models
- Recipe: Represents a recipe with fields like title, ingredients, instructions, and author.
- Comment: Represents a comment on a recipe with fields like text, recipe (foreign key), and author.




