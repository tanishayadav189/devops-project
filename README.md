#  DevOps CI/CD Project

A beginner-friendly End-to-End DevOps project demonstrating Continuous Integration (CI) using **Git, GitHub, Jenkins, Docker, and Nginx**.

The application is containerized with Docker, managed with Git/GitHub, and automatically built using a Jenkins Pipeline.

---

#  Project Architecture

```text
Developer
    │
    ▼
VS Code
    │
git add / git commit / git push
    │
    ▼
GitHub Repository
    │
    ▼
Jenkins Pipeline
    │
    ▼
Docker Image Build
    │
    ▼
Docker Container
    │
    ▼
Nginx Web Server
    │
    ▼
Application Running
```

---

#  Technologies Used

- Linux
- Git
- GitHub
- Jenkins
- Docker
- Nginx
- HTML

---

#  Project Structure

```
devops-project/
│── Dockerfile
│── Jenkinsfile
│── index.html
│── README.md
│── .gitignore
└── screenshots/
```

---

#  Features

- Version Control using Git
- Source Code hosted on GitHub
- Dockerized Web Application
- Jenkins Pipeline as Code (Jenkinsfile)
- Automatic Docker Image Build
- Nginx Web Server

---

#  Build Docker Image

```bash
docker build -t devops-project:v1 .
```

---

#  Run Docker Container

```bash
docker run -d --name devops-container -p 8081:80 devops-project:v1
```

---

#  Access Application

```
http://localhost:8081
```

---

#  Jenkins Pipeline

The Jenkins pipeline performs the following steps:

- Clone source code from GitHub
- Read Jenkinsfile
- Build Docker Image
- Complete the build successfully

---

#  Project Screenshots

## Jenkins Pipeline Success

<img width="1907" height="1025" alt="Screenshot 2026-07-10 224303 J" src="https://github.com/user-attachments/assets/7435380c-4427-4d55-a79f-ee34d0507d7e" />

---

## Docker Images

<img width="1077" height="622" alt="image" src="https://github.com/user-attachments/assets/58176c0f-762f-44a5-98eb-eed27eb5d903" />

---

## Running Docker Container

<img width="1077" height="121" alt="image" src="https://github.com/user-attachments/assets/2a477e3e-e482-4f52-82ff-5b7d07c41d0e" />

---
## Application Output

<img width="1900" height="1020" alt="Screenshot 2026-07-10 080056 1" src="https://github.com/user-attachments/assets/5e3fcfa9-37c0-4091-bc14-f277a57fcd24" />


---

#  Current Workflow

```text
VS Code
   │
   ▼
Git Push
   │
   ▼
GitHub
   │
   ▼
Jenkins
   │
   ▼
Docker Build
```

---

#  Upcoming Improvements

- Push Docker Image to Docker Hub
- Deploy Application on AWS EC2
- GitHub Webhook Integration
- Automatic Deployment
- Monitoring with Prometheus & Grafana

---

#  Author

**Tanisha Yadav**

Junior DevOps Engineer

- Linux
- Git & GitHub
- Docker
- Jenkins
- AWS (Learning)

---

⭐ If you found this project useful, don't forget to star this repository.
