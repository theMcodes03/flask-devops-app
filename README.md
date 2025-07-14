# 🚀 Flask DevOps App

Welcome to the **Flask DevOps App** — a complete, end-to-end project demonstrating the lifecycle of a web application using modern DevOps practices. From development with Flask to containerization with Docker and cloud deployment using Render, this project encapsulates core skills every DevOps engineer should master.

> 🔗 **Live App:** [flask-devops-app-s0i7.onrender.com](https://flask-devops-app-s0i7.onrender.com)

---

## 📌 Project Overview

This project was created as part of a DevOps role assessment to demonstrate:

- Backend development with Flask
- Creating a modular, production-ready folder structure
- Containerizing the app using a custom `Dockerfile`
- Pushing code to GitHub and collaborating through version control
- Deploying to a live URL using **Render's GitHub-integrated CI/CD**
- Future-ready architecture for pipeline automation

This app serves a simple landing page with HTML & CSS styled frontend, but the core focus is on its **infrastructure and deployment process**.

---

## 🛠️ Tech Stack

| Layer              | Technology Used                  | Purpose                          |
|-------------------|----------------------------------|----------------------------------|
| 🧠 Backend         | Python + Flask                   | API and server logic             |
| 🎨 Frontend        | HTML5 + CSS3                     | UI presentation                  |
| 🐳 Containerization| Docker                           | Isolated app packaging           |
| ☁️ Cloud Hosting   | Render.com                       | Free and public deployment       |
| 📂 Version Control | Git + GitHub                     | Source code management           |
| 🔁 CI/CD           | GitHub Actions *(future-ready)*  | Workflow automation              |

---

## 📁 Folder Structure

flask-devops-app/
│
├── app.py                   # Main Flask server
├── requirements.txt         # Python dependencies
├── Dockerfile               # Docker image instructions
├── static/
│   └── styles.css           # Styling for the frontend
├── templates/
│   └── index.html           # Frontend HTML page
├── .gitignore               # Ignored files (e.g., venv/, __pycache__)
└── README.md                # Project documentation

## Live Deployment (Render)

This app is deployed live using Render, a cloud service that integrates directly with GitHub.

- CI/CD: Every push to GitHub triggers a new deployment.

- URL: https://flask-devops-app-s0i7.onrender.com

- Branch: main

**Render** was chosen for its ease of use, free tier, and GitHub integration for automatic deployments.

----------------------------------

Author
Manisha 
