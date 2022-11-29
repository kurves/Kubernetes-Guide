# Kubernetes-Guide

#### This repository contains snippets and steps on how to install and use Kubernetes in your projects.

#### Feel free to refer to this repository when you encounter any challenge when using Kubernetes

#### The repository is well arranged and easily referenceable.

### Introduction

Kubernetes is an open-source system for production-grade container orchestration.

### Kubernetes features
- Automated rollouts and rollbacks
- Service discovery and load balancing
- Storage orchestration
- secret and configuration management
- Batch execution
- Horizontal scaling
- Self healing
- Designed for extensibility

with Kubernetes you can do the following:
- Deploy a containerized aplication on a cluster
- Scale the deployment
- Update the containerized application
- Debug the containerize application

### Kubernetes installation
- Follow the following steps to use Kubernetes on your machine

## Steps to follow
- Deploy a containerized application on a cluster
- Scale the deployment
- Update the containerized application with a new software version
- Debug the containerized appplication

# Using Kubectl to Create a Deployment

## Kubernetes Deployments

First you need a runing Kubernetes cluster and then deploy the containerized application on top of it, using a Kubernetes Deployment configuration

The deployment instructs Kubernetes how to create and update instances of your application.

A Deployment is responsible for creating and updating instaances of your apllication.

## Kubectl

You can create and manage the deployment by using the Kubernetes command line interface, **Kubectl**

Kubectl uses the Kubernetes API to interact with the cluster

When you create a Deployment, you'll need to specify the contaioner image for your appplication and the number of replicas that you want to run.

Applications need to be packaged into one of the supporyted conatiner formats to be deployed on kubernetes.

## Minikube and Katacoda

Minikube and katacoda are used to run apps on Kubernetes
Katacoda provoides a free, in browser Kubernetes environment

### steps
- Deplot a sample application to minikube
- Run the app
- View the application logs

## Steps 
Run ```minikube start``` if you have installed minikube locally

Open the Kuberenetes dashboard in a browser using ```minikube dashboard```

Open Dashboard with URL ```minikube dashbboard --url```
