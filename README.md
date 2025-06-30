Task Manager App 

A simple task manager web app I built with Flask. You can add tasks, edit them, and delete them when you're done.

What it does

Add new tasks
See all your tasks in a list
Edit tasks you already made
Delete tasks when finished
Works on your phone and computer

Built with

Python Flask for the backend
HTML and CSS for the frontend
SQLite for storing tasks
Deployed on Heroku

How to run it locally

Clone this repo
git clone https://github.com/ethnxie/task-manager.git
cd task-manager

Install Python dependencies
pip install -r requirements.txt

Run the app
python app.py

Go to http://localhost:5000 in your browser

Files
app.py              - Main Flask code
requirements.txt    - Python packages needed
templates/          - HTML files
static/css/         - CSS styling
Procfile           - For Heroku deployment
How to use

Click "Add Task" to make a new task
Fill out the form and submit
Your tasks show up on the main page
Click "Edit" or "Delete" next to any task

Deploying to Heroku

Make a Heroku account and install their CLI
Run heroku create task manager
Push your code with git push heroku main
Your app will be live at the URL Heroku gives you

Requirements
Flask==2.3.3
gunicorn==20.1.0
