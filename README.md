#  DevOps CI/CD Project

##  Project Overview

This project demonstrates a complete DevOps workflow using Docker, Git, GitHub, Jenkins, Docker Hub, and AWS EC2.

The application is containerized using Docker and version-controlled with Git. The next phase of this project is to automate the deployment using Jenkins CI/CD Pipeline.
## Technologies Used

- Linux
- Git
- GitHub
- Docker
- Nginx
- Jenkins
- Docker Hub
- AWS EC2
  
## Project Structure
devops-project/
│── Dockerfile
│── index.html
│── Jenkinsfile
│── README.md
│── .gitignore

## Build Docker Image

```bash
docker build -t devops-project:v1 .

## Run Docker Container
```bash
docker run -d --name devops-container -p 8081:80 devops-project:v1

##  Access Application
http://localhost:8081

##  Upcoming Improvements

- Jenkins CI/CD Pipeline
- Docker Hub Integration
- AWS EC2 Deployment
- Automated Build Process
- Webhook Integration

## Author
**Tanisha Yadav**

Junior DevOps Engineer | AWS | Docker | Jenkins | Linux
