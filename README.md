# Create Kubernetes Cluster

<p align="center">
  <img src="https://img.shields.io/badge/Kubernetes-v1.20-blue?style=flat-square">
  <img src="https://img.shields.io/badge/Minikube-v1.17.1-brightgreen?style=flat-square">
  <img src="https://img.shields.io/badge/Docker-v20.10.2-blue?style=flat-square">
</p>

<p align="center">
  <strong>Create a Kubernetes cluster with Minikube in just a few simple steps.</strong>
</p>

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

<ul>
  <li><strong>kubectl</strong>: Command-line tool to interact with Kubernetes clusters.</li>
  <li><strong>Minikube</strong>: Tool that runs a local Kubernetes cluster.</li>
  <li><strong>Docker</strong>: Container platform to manage and deploy applications.</li>
</ul>

## Steps to Create a Kubernetes Cluster

### 1. Install Minikube

First, install Minikube by following the official instructions for your operating system:

```bash
# Linux
curl -Lo minikube https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
chmod +x minikube
sudo mv minikube /usr/local/bin/

# macOS
brew install minikube

# Windows
choco install minikube
