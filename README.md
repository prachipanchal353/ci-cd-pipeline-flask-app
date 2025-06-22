# CI/CD Pipeline with GitHub Actions, Docker & AWS EC2

This project demonstrates a production-ready CI/CD pipeline that:

- Builds a Flask app
- Uses GitHub Actions for CI/CD
- Dockerizes the app
- Pushes the image to DockerHub
- Deploys on AWS EC2 via SSH

## Tools Used

- GitHub Actions
- Docker & DockerHub
- Python Flask
- AWS EC2
- Secrets & SSH

## My Role

As a DevOps Engineer, I designed the CI/CD workflow, created Docker containers, and automated deployment on EC2.

## Run the App Locally

```bash
docker build -t flask-app .
docker run -d -p 5000:5000 flask-app
