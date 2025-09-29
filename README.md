# Kubernetes Minikube Deployment

## Overview
This project demonstrates deploying an NGINX application on a local Kubernetes cluster using Minikube on Amazon Linux.

## Steps performed:
1. Installed Minikube, kubectl, and Docker on Amazon Linux.
2. Started Minikube with Docker driver.
3. Created `deployment.yaml` to deploy nginx with 4 replicas.
4. Created `service.yaml` to expose nginx using NodePort.
5. Applied the YAML files using `kubectl apply -f`.
6. Verified running pods with `kubectl get pods`.
7. Verified services with `kubectl get services`.
8. Took screenshots of pods and services output.

## Files
- `deployment.yaml`: Deployment manifest for nginx.
- `service.yaml`: Service manifest exposing nginx.
- `screenshots/`: Contains terminal output screenshots.


