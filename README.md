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

## Screenshot
<img width="1900" height="1020" alt="Screenshot 2026-07-10 080056 1" src="https://github.com/user-attachments/assets/eff4d674-7612-4333-a416-0a8b48474873" />
<img width="1381" height="162" alt="image" src="https://github.com/user-attachments/assets/222ac7f4-3c33-43bd-a1da-370d6f76b4e9" />
<img width="1907" height="1025" alt="Screenshot 2026-07-10 224303 J" src="https://github.com/user-attachments/assets/88beb259-0f31-43f3-bf7a-5e213ad02dc0" />





## Author
**Tanisha Yadav**

Junior DevOps Engineer | AWS | Docker | Jenkins | Linux
