---
date: '4'
title: 'Developing and Hosting a Cloud Based Chat Service'
cover: './chat.png'
external: 'https://medium.com/@manishsombansh/wecloud-chat-as-a-service-c32c6ef90ba6'
tech:
  - Java Spring Suite
  - Redis Pub/Sub
  - MySQL
  - Docker
  - Kubernetes
  - Helm & YAML
  - Google Container Registry & Kubernetes Engine
  - Azure Kubernetes Cluster
  - Terraform
  - GCP & Azure
showInProjects: false
---

Created a WeChat like application with Microservices pattern : Designed and developed 3 services, login, group chat, and profile; Modeled the interaction between services as directed acyclic graph. Implemented the REST APIs of login, group chat and the profile service using Java, Spring web-socket, Helm and used Redis Pub/Sub as a messaging service to improve the scalability of the group chat service. Deployed the services using Docker, Kubernetes, and Helm across multiple cloud platforms (GCP and Azure) for fault-tolerance; Monitored the CPU utilization metrics and automatically augmented the pods and added the auto-scaling feature with Kubernetes HPA.
