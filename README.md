# Dockerized Static Web Application 🐳

This project demonstrates a complete workflow of taking a static web application from a Git repository, containerizing it using Docker, and deploying it with Nginx.

## 🚀 Quick Start

To run this application locally, you only need to have Docker installed on your machine.

### 1. Clone the repository

git clone [https://github.com/Blahodir/my_docker_app.git](https://github.com/Blahodir/my_docker_app.git)
cd my_docker_app

### 2. Build the Docker image

docker build -t my-git-app .

### 3. Run the container

docker run -d -p 9000:80 --name my-running-app my-git-app

### 4. Now, open your browser and navigate to: http://localhost:9000
