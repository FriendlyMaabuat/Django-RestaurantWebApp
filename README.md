# Restaurant Menu
This is a Django web application for displaying a restaurant's menu. The app allows users to view different categories of dishes along with their descriptions and prices. This app also includes a QR code image to access the Restaurant Menu app.

## Features

- Display a list of menu categories (e.g., Starters, Main Courses, Salads, Desserts).
- Display dishes under each category with their name, description, and price.
- Responsive design for mobile and desktop views.
- Administrator page to view and modify items in the menu.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/FriendlyMaabuat/Django-RestaurantWebApp
    cd Django-RestaurantWebApp
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Apply the migrations:
    ```bash
    python manage.py migrate
    ```

5. Create a superuser to access the admin panel:
    ```bash
    python manage.py createsuperuser
    ```

6. Run the development server:
    ```bash
    python manage.py runserver
    ```

7. Open your web browser and go to `http://127.0.0.1:8000` to see the app in action.

## Usage

- Access the admin panel at `http://127.0.0.1:8000/admin` to add, update, or delete menu items.
- Navigate to the home page to view the menu.

## Project Structure
``` bash
restaurant-menu-app/ 
├── manage.py 
├── db.sqlite3
├── qr.py 
├── qr.png 
├── restaurant_menu/ 
│ ├── migrations/ 
│ │ ├── 0001_initial.py 
│ │ └── __init__.py 
│ ├── __init__.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py
│ ├── views.py
│ ├── templates/
│ │ ├── base.html
│ │ ├── index.html
│ │ └── menu_item_detail.html
├── mysite/
│ ├── __init__.py
│ ├── settings.py
│ ├── urls.py
│ ├── wsgi.py
│ └── asgi.py
└── requirements.txt
```
## Attachments
![image](https://github.com/FriendlyMaabuat/Django-RestaurantWebApp/assets/92776515/bc7673bb-b580-453a-b6f5-7a116d4f8463)
![image](https://github.com/FriendlyMaabuat/Django-RestaurantWebApp/assets/92776515/204ae217-eb66-4704-a052-a30009a8226c)
![image](https://github.com/FriendlyMaabuat/Django-RestaurantWebApp/assets/92776515/6478d87a-8bfe-4acb-94fa-9d91b5ef44b0)

