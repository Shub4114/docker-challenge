# Docker Challenge 1 & 2

## Overview

This project includes two Docker challenges:

1. **Challenge 1**: Setting up a static web page using Docker and NGINX.
2. **Challenge 2**: Creating a Dockerized NodeJS application with NGINX as a reverse proxy using Docker Compose.

## Repository Structure

- `README.md`: This file, containing an overview of the project and instructions.
- `student.cfg`: Contains student information.
- `challenge1`: Directory for Challenge 1 files.
- `challenge2`: Directory for Challenge 2 files.

## How to Use


#### Challenge 1

1. Navigate to the `challenge1` directory:
   cd challenge1
2. Build the Docker image:
docker build -t my-static-site .
Run the Docker container:

3. docker run -d -p 8080:80 --name static-site my-static-site
Open your browser and go to http://localhost:8080 to see the static site.

#### Challenge 2
1. Navigate to the challenge2 directory:
    cd challenge2
2. Build and run the Docker containers using Docker Compose:


    docker-compose up --build

3. Open your browser and go to http://localhost:8080 to see the application.
