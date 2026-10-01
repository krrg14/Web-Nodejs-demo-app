# Web-Nodejs-demo-app. 
## ☕ Coffee Website - Node.js Demo Application

A simple web application built with **Node.js and Express.js**, containerized using **Docker**, and automated using **GitHub Actions CI/CD**.

## 🚀 Project Overview

This project demonstrates a basic DevOps workflow for a Node.js web application.

The application is developed using Node.js and Express.js and is packaged into a Docker image. GitHub Actions is used to automatically test, build, containerize, and push the application image to Docker Hub whenever changes are pushed to the `main` branch.

## 🛠️ Technologies Used

- Node.js
- Express.js
- JavaScript
- Docker
- Docker Hub
- Git
- GitHub
- GitHub Actions
- Linux

## 📁 Project Structure

```
Web-Nodejs-demo-app/
│
├── .github/
│   └── workflows/
│       └── demo-nodejs-app.yml
│
├── public/
│   └── Application web files
│
├── Dockerfile
├── package.json
├── package-lock.json
├── server.js
├── .gitignore
└── README.md

```

## 🚀 Project Overview

```

This project demonstrates a basic DevOps workflow:

Developer
    │
    │ git push
    ▼
GitHub Repository
    │
    ▼
GitHub Actions
    │
    ├── Checkout Code
    │
    ├── Setup Node.js
    │
    ├── Install Dependencies
    │
    ├── Run Tests
    │
    ├── Build Application
    │
    ├── Login to Docker Hub
    │
    ├── Build Docker Image
    │
    └── Push Docker Image
             │
             ▼
        Docker Hub

```
## Snapshot
<img width="1754" height="967" alt="Screenshot 2026-10-02 011751" src="https://github.com/user-attachments/assets/dbe08223-1c9e-4033-98e6-b70c3a231c34" />
