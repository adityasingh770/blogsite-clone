
# Django Blog Site  

This is a simple blog site created using the Django web framework. It allows users to write blog posts, and comment on other users' posts.  

## Prerequisites  
To run this application, you will need:  
- Python 3.11 installed on your machine  
- Django 4.1.7 installed on your machine  

## Getting started  
- Clone this repository onto your machine using git clone https://github.com/jobless-lm10/blogsite.git 
- Navigate to the project directory using cd blogsite 
- Install the required packages by running pip install
- Create a new database by running python manage.py migrate  
- Start the development server using python manage.py runserver  

## Usage
- Once the server is running, you can access the blog site by navigating to http://localhost:8000 in your web browser.
- Create an account by python manage.py createsuperuser and following the prompts.
- Log in to an existing account by clicking the "Log in" link icon in the navigation bar.
- Create a new blog post by clicking the "New post" button on the home page (note that you must be logged in to do this).  
- Comment on an existing post by clicking the "Comment" button on the post's detail page (note that you must be logged in to do this)

## Contributing
If you'd like to contribute to this project, you can:
- Fork this repository
- Create a new branch for your changes using git checkout -b <branch-name>
- Make your changes and commit them using git commit -m "<commit-message>"
- Push your changes to your fork using git push origin <branch-name>
- Create a pull request on this repository

Acknowledgments
This project was inspired by the Django Full Stack Web Developer Bootcamp by Jose Portilla on Udemey.
