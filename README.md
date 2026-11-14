# 🛒 Ecostore

A cloud-native web application running on Google Cloud Run with automated GitOps CI/CD via GitHub Actions and Workload Identity Federation.

## 🚀 Live Demo

[![Launch Live App](https://img.shields.io/badge/LAUNCH-LIVE_APP-brightgreen?style=for-the-badge&logo=google-cloud&logoColor=white)](https://ecostore-app-srhl5wphma-uc.a.run.app)

Click the badge above or navigate to: https://ecostore-app-srhl5wphma-uc.a.run.app

## 🛠️ Architecture

* **Compute:** Google Cloud Run (Source-deployed Python / Flask App)
* **CI/CD:** GitHub Actions with Workload Identity Federation (Keyless OIDC authentication)
* **Governance:** Protected `main` branch with automated `managed-by: github-actions` deployment labeling
