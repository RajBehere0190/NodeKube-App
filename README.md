# NodeKube-App
NodeKubeApp is a sample Node.js application deployed on a Kubernetes cluster. This project demonstrates how to containerize a Node.js application using Docker and deploy it using Kubernetes. The application is built with Express.js, a minimal and flexible Node.js web application framework.



## Features

- **Node.js and Express.js**: The application is built using Node.js and Express.js, providing a simple web server.
- **Docker**: The application is containerized using Docker, making it easy to deploy and run in any environment.
- **Kubernetes**: The application is deployed on a Kubernetes cluster, showcasing how to manage and scale containerized applications.
- **Load Balancing**: The Kubernetes Service is configured to load balance traffic across multiple instances of the application.
- **External Access**: The application is exposed externally using a Kubernetes LoadBalancer service, allowing access from outside the cluster.

## Project Structure

- **Dockerfile**: Defines the Docker image for the Node.js application.
- **deployment-node-app.yml**: Kubernetes Deployment configuration for the Node.js application.
- **service-node-app.yml**: Kubernetes Service configuration to expose the Node.js application.

- **Minikube Dashboard**

 ![image](https://github.com/user-attachments/assets/6023c390-1a8b-4297-96cb-ae4ead51a339)

**Note :** Here I have used the image of the node-demo-app from philippaul docker repository but if wants to customize own image I have provided the Dockerfile.

## Prerequisites

- Docker
- Minikube
- kubectl
