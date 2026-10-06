# Node.js CI/CD Demo

## Project Description

This project is a simple Node.js application containerized using Docker.

## Technologies Used

- Node.js
- Docker
- Git
- GitHub

## Application Output

The application runs on port 3000.

## Docker Build

Build the Docker image using:

```bash
docker buildx build --load -t nodejs-demo-app .

**Verify Application**
Open the following URL in a browser:
http://localhost:3000
Expected output:
Hello from Node.js CI/CD Demo!

**Docker Commands Used**
docker images
docker ps
docker buildx build --load -t nodejs-demo-app .
docker run -d --name nodejs-demo-container -p 3000:3000 nodejs-demo-app

**Project Structure**
nodejs-demo-app/
├── app.js
├── package.json
├── package-lock.json
├── Dockerfile
└── README.md

