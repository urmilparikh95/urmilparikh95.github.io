---
title: ":computer: A CI-CD Pipeline for automating Build and Deployment Process"
layout: post
date: 2018-04-20 00:00
tag: 
    - DevOps
    - Build
    - Deployment
    - Automation
image: assets/images/project/devops-pipeline/Jenkins_logo.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "This is a project demonstrating the DevOps Pipeline used automating Build and Deployment"
permalink: devops-pipeline
category: project
author: urmilparikh95
externalLink: false
---
<!--center>
<img src="https://raw.githubusercontent.com/sergiokopplin/indigo/gh-pages/assets/screen-shot.png" width="100%;">
</center-->
Created a DevOps pipeline to configure a Jenkins Build Server for 2 applications - [iTrust]() - a Hibernate application built on Java and [checkbox.io]() - a node.js express web application. Ensured build was successful by executing each individual test suites for the applications. Created a post build task to automatically provision and configure servers and deploy the applications. Implemented a [Kubernetes]() cluster for [containerised]() version of checkbox.io for better scalablity and monitoring. Implemented [canary release]() for Itrust deployment. Created a [Redis]() Server for managing feature flags.

---

Technology Stack

- Ansible
- Jenkins
- Docker
- Kubernetes
- AWS EC2
- Vagrant
- Redis
- Node.js
- Java
- MySQL
- MongoDB

---

[Check it out](https://github.com/urmilparikh95/DevOps-Pipeline) here.
