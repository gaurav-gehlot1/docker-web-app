\# Dockerizing a Simple Web Application



\## 1. Project Overview



This project demonstrates how to package and run a simple HTML web application using Docker and Nginx.



\## 2. Objectives



\- Create a simple web application.

\- Write a Dockerfile.

\- Build a Docker image.

\- Run the application inside a Docker container.

\- Publish the Docker image to Docker Hub.



\## 3. Technologies Used



\- HTML

\- Docker

\- Docker Hub

\- Nginx

\- Git

\- GitHub



\## 4. Project Structure



```text

docker-web-app/

├── Dockerfile

├── index.html

└── README.md

```



\## 5. Build the Docker Image



```bash

docker build -t my-first-devops-app:1.0 .

```



\## 6. Run the Container



```bash

docker run -d --name devops-web -p 8080:80 my-first-devops-app:1.0

```



Open `http://localhost:8080` in your browser to access the application.



\## 7. Verify the Container



```bash

docker ps

```



\## 8. Docker Hub



Docker Hub repository: `YOUR\_DOCKERHUB\_USERNAME/my-first-devops-app`



\## 9. Stop and Remove the Container



```bash

docker stop devops-web

docker rm devops-web

```



\## 10. Conclusion



This project demonstrates the fundamentals of containerization, including creating a Docker image, running a container, and preparing an application for distribution through Docker Hub.

