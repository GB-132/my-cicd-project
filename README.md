# CI/CD Pipeline using GitHub Actions & Docker

## Project Overview
This project demonstrates an automated CI/CD pipeline for a Python Flask 
web application using GitHub Actions and Docker.

Every time code is pushed to the main branch, the pipeline automatically:
- Installs dependencies
- Runs automated tests
- Builds a Docker image
- Pushes the image to Docker Hub

## Tools & Technologies Used
- Python & Flask — Web application
- Pytest — Automated testing
- Docker — Containerization
- GitHub Actions — CI/CD pipeline automation
- Docker Hub — Container registry

## Project Structure

my-cicd-project/
├── app.py                        # Flask web application
├── requirements.txt              # Python dependencies
├── Dockerfile                    # Docker image instructions
├── test_app.py                   # Automated tests
└── .github/
└── workflows/
└── cicd.yml                      # GitHub Actions pipeline

## How the Pipeline Works
1. Developer pushes code to GitHub
2. GitHub Actions automatically triggers
3. Python and dependencies are installed
4. Pytest runs automated tests
5. If tests pass — Docker image is built
6. Docker image is pushed to Docker Hub

## How to Run Locally
1. Clone the repository
2. Install dependencies
3. Run the app
4. Open browser and go to

## Pipeline Status
![CI/CD Pipeline](https://github.com/GB-132/my-cicd-project/actions/workflows/cicd.yml/badge.svg)

## What I Learned
- How to build and automate a CI/CD pipeline
- How to containerize a Python app using Docker
- How to use GitHub Actions for automated testing and deployment
- How to securely manage credentials using GitHub Secrets
