
# Blog Project using Flask, Jinja, Python, HTML/CSS and SQL-Alchemy

This is a web application for a blog, built using Flask framework in Python. The application uses Jinja templates to render HTML/CSS views, and SQL-Alchemy as a database management system.

## Features

The blog project has the following features:

-   **User authentication**: users can create accounts, login and logout. User passwords are hashed and salted for security.
-   **Create, Edit and Delete posts**: authenticated users can create new posts, edit their own posts and delete them.
-   **Commenting system**: authenticated users can leave comments on other users' posts.
-   **User profile pages**: users have their own profile pages that display their posts and comments.
-   **Admin page**: an admin user can access an admin page with extra features, such as editing and deleting any post or comment, and managing user accounts.

## Installation

To use this website, you need to have Python 3 and Flask installed on your system. To install Flask, run:

`pip install Flask` 

You also need to install SQL-Alchemy, which can be installed with:

`pip install flask-sqlalchemy` 

There is a text file called "requirements.txt" that lists all the requirements you need to use the website. The browser should auto install.

Finally, you need to set up the database. Run the following commands in a Python console:

`from app import db
db.create_all()` 

This will create the necessary tables in the database.

## Usage

To start the web application, run the following command in a terminal:

`python app.py` 

This will start a local server at `http://localhost:5000`. Open a web browser and go to that URL to access the website.

## Upcoming/ Not Fully Functional
* Will soon be deployed to Heroku
* Needs to fix commenting functionality


## Credits

This blog project was created by Liam Evans. The starting code was written by Angela Yu, a Udemy instructor. Feel free to use, modify and distribute this code as you wish, as long as you give credit to the original author.
