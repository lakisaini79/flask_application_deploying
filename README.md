# flask_application_deploying
# Flask Application Deployment with Docker

This project demonstrates containerizing and deploying a Flask web application
using Docker. The primary focus is on application packaging, containerization,
and deployment workflow rather than application development.

## Architecture Overview
- Flask application running inside a Docker container
- Docker used for image build and container runtime
- Application exposed via mapped ports

## Tech Stack
- Backend Framework: Flask
- Containerization: Docker
- Programming Language: Python
- Operating System: Linux (Ubuntu)

## Project Structure
.
├── app.py
├── requirements.txt
├── Dockerfile
└── README.md

## Prerequisites
- Docker
- Linux system or cloud VM

## Dockerfile Overview
- Uses a lightweight Python base image
- Installs application dependencies
- Exposes application port
- Runs Flask application inside container

## Build Docker Image
```bash
docker build -t flask-app .
