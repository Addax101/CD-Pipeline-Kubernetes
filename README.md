# CD Pipeline Kubernetes

[![Build Status](https://img.shields.io/jenkins/build?jobUrl=https%3A%2F%2Fjenkins.example.com%2Fjob%2Fcd-pipeline-kubernetes%2F&style=flat-square)](https://jenkins.example.com/job/cd-pipeline-kubernetes/)
[![License](https://img.shields.io/github/license/Addax101/cd-pipeline-kubernetes?style=flat-square)](https://github.com/Addax101/CD-Pipeline-Kubernetes/blob/main/LICENSE)

CD Pipeline Kubernetes is an end-to-end pipeline that automates the deployment of software to production using Jenkins, Docker, Kubernetes, Prometheus, Grafana, and Slack. The pipeline includes various stages such as build, test, deploy, and release, and is designed to support continuous delivery best practices. 


## Getting Started
To get started with CD Pipeline Kubernetes, you'll need to clone the repository and install the necessary tools and dependencies.

## Prerequisites
You'll need the following tools and dependencies installed:

* Git
* Jenkins
* Docker
* Kubernetes
* Prometheus
* Grafana
* Slack

## Installing
1. Clone the repository:`git clone https://github.com/Addax101/cd-pipeline-kubernetes.git`

2. Install the necessary dependencies using your package manager of choice: `npm install`
3. Set up the required environment variables and Jenkins credentials: 
```bash
export ENVIRONMENT=production
export DOCKER_REGISTRY=your-registry-url
export KUBECONFIG=path/to/your/kubeconfig
export JENKINS_USERNAME=your-jenkins-username
export JENKINS_PASSWORD=your-jenkins-password
export SLACK_WEBHOOK_URL=your-slack-webhook-url

```
