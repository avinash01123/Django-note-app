Simple Notes App 
This is a simple notes app built with React and Django.

Requirements
Python 3.9
Node.js
React


Installation

Clone the repository

git clone git@github.com:avinash01123/Django-note-app.git

Build the app
docker build -t notes-app .
Run the app
docker run -d -p 8000:8000 notes-app:latest

Nginx
Install Nginx reverse proxy to make this application available

sudo apt-get update sudo apt install nginx
