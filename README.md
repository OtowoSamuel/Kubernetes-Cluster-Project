# My Web App

## Description

`my-web-app` is a web application designed to demonstrate basic Kubernetes deployment. This project includes a Node.js web application that is deployed and managed using Kubernetes.

## Features

- Dockerized Node.js application
- Deployed on a Kubernetes cluster
- Exposes a web service via NodePort

## Getting Started

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Kubernetes](https://kubernetes.io/docs/setup/)
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/OtowoSamuel/my-web-app.git
   cd my-web-app

2. **Build and Run Docker Container**

   ```bash
   docker build -t my-web-app .
   docker run -p 80:80 my-web-app

3.  **Deploy to Kubernetes**
   
    ```bash
    kubectl apply -f deployment.yaml
    kubectl apply -f service.yaml
    kubectl get pods
    kubectl get services

  

