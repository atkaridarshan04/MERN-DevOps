# **MERN DevOps Project**

This project is designed to facilitate the deployment of a MERN (MongoDB, Express, React, Node.js) application. By leveraging modern technologies such as **Docker** for containerization, **Kubernetes** for orchestration, **Jenkins** for continuous integration and delivery (CI/CD), and **ArgoCD** for GitOps-based continuous deployment, this project aims to streamline the entire software development lifecycle.

---

## **Overview**

The MERN DevOps project includes:

- **Dockerization**: Building and running containers for the frontend, backend, and MongoDB using Docker.
- **Kubernetes Deployment**: Deploying the application on a Kubernetes cluster using `kubectl` and YAML configurations.
- **CI/CD Pipeline**: Automating the build, test, and deployment processes using Jenkins.
- **Helm Deployment**: Managing Kubernetes deployments using Helm charts for MongoDB, backend, and frontend services.
- **ArgoCD GitOps**: Continuously deploying and synchronizing the application with the GitHub repository to ensure that the live environment reflects the latest code changes.

---

## **Project Deployment Flow**

![workflow-gif](./assets/workflow.gif)

---

## **Documentation**

To understand the various components of this project, refer to the following documentation:

- **[Docker.md](./docs/Docker.md)**:  
  Detailed instructions on how to build and run the MERN stack application using Docker, including creating a Docker network, building images, and managing containers.

- **[Kubernetes.md](./docs/Kubernetes.md)**:  
  Detailed instructions on deploying the MERN stack application using Kubernetes, including how to set up persistent storage, deploy services, and access the application.

- **[Jenkins.md](./docs/Jenkins.md)**:  
  A comprehensive guide on the Jenkins CI/CD pipeline, outlining the various stages, parameters, prerequisites, and tools used to automate the integration and deployment processes.

- **[Helm.md](./docs/Helm.md)**:  
  Instructions on how to deploy the MERN stack application using Helm, including installation, chart customization, and deployment of MongoDB, backend, and frontend services.

- **[ArgoCD.md](./docs/ArgoCD.md)**:  
  A step-by-step guide on installing, configuring, and using ArgoCD to deploy the application by Connecting ArgoCD to the GitHub repository.

---