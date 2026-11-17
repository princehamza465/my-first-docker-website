# Hamza - DevOps Engineer | My First Docker Website

My first portfolio website deployed with Docker and Nginx on Ubuntu.

## What I Built
- Created a portfolio website with HTML
- Created a Dockerfile using `nginx:alpine` image
- Built Docker Image and ran it as a Container
- Website runs on `localhost:8080`

## Tech Used
Docker | Linux | Ubuntu | Nginx | HTML | VirtualBox | GitHub

## How To Run This Project

```bash
docker build -t my-website .
docker run -d -p 8080:80 --name my-site my-website
then open in browser:localhost:8080
## Author
Hamza
