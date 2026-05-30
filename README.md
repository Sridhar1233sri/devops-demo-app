 DevOps Demo App

## Project Description
This project demonstrates an end-to-end DevOps CI/CD pipeline using GitHub, Jenkins, Docker, and AWS EC2. Jenkins pulls the latest code from GitHub, builds a Docker image, deploys the container on EC2, and verifies the running container.

## Tech Stack
-	Git and GitHub
-	Jenkins
-	Docker
-	AWS EC2 Ubuntu
-	Nginx
-	Shell scripting

## Local Setup
```bash
git clone https://github.com/Sridhar1233sri/devops-demo-app.git cd devops-demo-app
docker build -t devops-demo .
docker run -d -p 80:80 --name devops-container devops-demo
```

Open the application:
```text http://localhost
```

## CI/CD Flow
1.	Developer pushes code to GitHub.
2.	Jenkins pulls the latest code using Pipeline from SCM.
3.	Jenkins builds the Docker image.
4.	Jenkins stops and removes the old container.
 
5.	Jenkins runs the latest container on port 80.
6.	Deployment is verified using docker ps and browser access.

## Deployment URL http://54.172.178.171


