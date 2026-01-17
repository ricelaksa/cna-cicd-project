# CNA CI/CD Project

This project demonstrates a simple CI/CD pipeline for a containerized
web application as part of the CNA assignment.

## Technologies Used
- GitHub (version control)
- Docker (containerization)
- Docker Hub (image registry)
- Jenkins (CI/CD automation)
- AWS EC2 (deployment environment)

## Application
A simple PHP web application running in a Docker container.

## CI/CD Overview
1. Source code is stored in GitHub.
2. Jenkins pulls code automatically via webhook.
3. Jenkins builds a Docker image.
4. The image is pushed to Docker Hub.
5. The application is deployed using Docker.

