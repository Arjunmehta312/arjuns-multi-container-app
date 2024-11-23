# Multi-Container Docker App

This repository contains the files I created as part of learning Docker and Docker Compose through the official Docker tutorials, using Docker for Desktop on Windows. The tutorial demonstrates how to manage multiple containers (e.g., a web service and a database) in a Dockerized environment.

## What I Learned
- How to set up and configure a multi-container application using Docker Compose.
- Working with multiple services and managing them with Docker containers.
- Understanding how to link different services like a web server and a database within a Dockerized environment.

## Prerequisites
To follow along with this tutorial, you'll need:
- [Docker for Desktop for Windows](https://www.docker.com/products/docker-desktop)
- A basic understanding of Docker and Docker Compose

## Getting Started
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/Arjunmehta312/arjuns-multi-container-app.git
   
2. Change to the project directory:
   ``` bash
    cd arjuns-multi-container-app
3. Use Docker Compose to build and run the application:
    ``` bash 
   docker compose up -d

4. Open http://localhost:3000 in your browser to see the application running.

License
This project is open-source and available under the MIT License.
