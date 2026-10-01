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

```text
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
