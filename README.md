# Flask Productivity App

## Overview
This is a Flask-based productivity web app that allows users to manage tasks and notes. Users can:
- Sign up and log in
- Add, view, and delete tasks
- Add, view, and delete notes
- Track task completion status

## Features
- User authentication with Flask-Login
- SQLite database for storing tasks and notes
- Dynamic HTML templates using Jinja2
- Responsive front-end for easy usability

## Folder Structure
- main.py — Flask entry point
- website/ — app package
  - __init__.py — app factory
  - models.py — database models
  - iews.py — routes and view logic
  - uth.py — authentication logic
  - 	emplates/ — HTML templates
  - static/ — CSS and JS files
- instance/ — database file
- equirements.txt — Python dependencies
- .gitignore — ignores pycache and database

## Installation
1. Clone the repo: git clone <repo_url>
2. Install dependencies: pip install -r requirements.txt
3. Run the app: py -3 main.py
4. Open http://127.0.0.1:5000 in your browser

## Author
Leah Burgess

## Notes
This project demonstrates Python and Flask skills applied to a real productivity solution.
