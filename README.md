# Production CI/CD Case Study – Drupal (GitLab + Jenkins)

This repository documents a **real-world production CI/CD implementation** for a Drupal application.

⚠️ No application source code is included.  
This repository focuses on **architecture, automation strategy, security, and operational decisions**.

---

## 🚀 Project Summary

- Automated CI/CD pipeline using **GitLab + Jenkins**
- Zero-downtime production deployments
- Atomic releases with instant rollback
- Secure SSH-based deployment (no Docker)
- Developers have **no production access**

---

## 🏗 Architecture Overview

Developer → GitLab → Jenkins → Production Server

- Developers only push code to Git
- Jenkins handles build & deployment
- Production server is write-protected

---

## 🔑 Key Features Implemented

- Fully automated deployment on git push
- Atomic release directories (`releases/`)
- Symlink-based live switch (`current`)
- One-command rollback
- Separation of code and persistent data
- Secure deploy user (no root access)

---

## 📂 Documentation

- Architecture design
- CI/CD pipeline stages
- Deployment strategy
- Rollback strategy
- Security model
- Challenges faced and fixes

---






