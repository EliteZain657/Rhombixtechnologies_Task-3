🚀 Kubernetes Deployment Project (NGINX on Local Cluster)

This project demonstrates a complete DevOps workflow using Kubernetes to deploy and manage a containerized application locally using Docker Desktop Kubernetes.

📖 Overview:

This project covers:

Kubernetes cluster setup using Docker Desktop
Application deployment using Deployment YAML
Service exposure using NodePort
Scaling application replicas
Self-healing container behavior

🧰 Tech Stack:

Kubernetes (v1.34+)
Docker Desktop
kubectl CLI
NGINX container

⚙️ Setup & Deployment Steps:

Check cluster status:
kubectl get nodes
Deploy application:
kubectl apply -f deployment.yaml
Create service:
kubectl apply -f service.yaml
Verify resources:
kubectl get pods
kubectl get deployments
kubectl get services
Access application in browser:
http://localhost:30080

📈 Features:

Kubernetes cluster management
Declarative deployment (YAML-based)
Service exposure using NodePort
Horizontal scaling (replicas)
Self-healing pods

🔥 Learning Outcome:

This project helped understand real-world DevOps practices like container orchestration, scaling strategies, and infrastructure automation.

🏢 Internship:

Developed as part of internship at Rhombix.

👨‍💻 Author:

Zain Shahid
