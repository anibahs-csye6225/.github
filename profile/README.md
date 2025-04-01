# User Management System on GCP  

This project is a scalable user management system designed and deployed on **Google Cloud Platform (GCP)**, featuring robust REST APIs, serverless functions for asynchronous processes, and infrastructure automation using Terraform.

## Features

### Web Application
- Built using **Node.js**, the web application provides:
  - **User Registration:** Securely register new users.
  - **Authentication:** Authenticate users with credentials.
  - **User Verification:** Verify users using unique UUID tokens.
  - **Health Check Endpoint:** Includes a `/healthz` API for system health monitoring.

### Serverless Function
- Designed for **asynchronous user verification**, leveraging UUID tokens for secure and efficient processing.

### Infrastructure as Code (IaC)
- Fully automated deployment using **Terraform** and GitHub Actions:
  - Deployed a **Managed Instance Group (MIG)** with autoscaling and load balancer to ensure high availability and performance.

