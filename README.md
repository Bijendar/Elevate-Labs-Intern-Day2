
# 🚀 Task 2 – DevOps CI/CD Pipeline using Jenkins & Docker

This project is part of my DevOps internship at **Elevate Labs**. In this task, I have created a Jenkins pipeline to build and deploy a Node.js application using Docker.

---

## 📁 Project Structure

```


 node-demo-app/
│       ├── app.js
│       ├── package.json
│       ├── Dockerfile
│       └── Jenkinsfile ✅
```

---

## 🛠 Tech Stack Used

- 🧠 **Jenkins** – CI/CD tool to automate build & deploy
- 🐳 **Docker** – To containerize and run the application
- 🔗 **GitHub** – Code repository
- 🌐 **Node.js** – Demo application used for deployment

---

## 🔁 CI/CD Pipeline Stages (via Jenkins)

### 1. **Checkout Code**
- Jenkins pulls the code from this GitHub repository:
  ```
  https://github.com/Bijendar/node-demo-app
  ```

### 2. **Build Docker Image**
- Docker builds an image using the Dockerfile inside `node-demo-app` directory.

### 3. **Deploy Application**
- The image is run as a container using:
  ```bash
  docker run -d -p 3000:3000 node-demo-app-image:latest
  ```

---


## 🧠 Learnings

Through this task, I learned:
- How Jenkins automates the CI/CD lifecycle
- How Docker simplifies deployment
- Importance of automation in real-world DevOps

---

## 📎 Repository Link

👉 [Click to view full code](https://github.com/Bijendar/node-demo-app)

---

## 🙌 Thank You!

> This task was a great hands-on experience in building production-like CI/CD pipelines.  
> Excited for what's next in the internship journey! 🚀
