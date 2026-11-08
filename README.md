# Travelo - Deploiement Kubernetes

Application web 3-tiers (React, Spring Boot, MySQL) deployee sur un cluster Minikube.
Devoir 2 - Conteneurisation des Applications - INPT ASEDS.

## Ordre de deploiement

kubectl apply -f 00-namespace.yaml
kubectl apply -f 01-configmap.yaml -f 02-secret.yaml
kubectl apply -f 03-database.yaml
kubectl apply -f 04-backend.yaml -f 05-frontend.yaml
