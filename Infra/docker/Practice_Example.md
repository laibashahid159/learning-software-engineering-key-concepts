## Problem Statement

Create a small random jokes telling application application using any programming language

Create a Dockerfile that specifies the required dependencies and configurations for running the application.

Build a Docker image from the Dockerfile.

Run a container from the Docker image.

## Solution

I will be using python to make a small script that will tell jokes randomly, its included in the code folder

I pulled a python image using this command : `  docker pull python:3`

once python image is pulled i ran this command to run my script ` docker run -it --rm -v D:\learning-software-engineering-key-concepts\Infra\docker\code:/app python:3 python /app/jokes.py`
3
once i was able to run the script, i added the Dockerfile for my script and built the image using `docker build -t my-random-joke-app .`, once the built was successful i used `docker images` to check for the image i just created

used `docker run to my-random-jokes-app` to run the container
