# GitOps App

A simple repo for exploring GitOps using ArgoCD.

This contains:
- `deployment.yaml`: Deploys an Nginx pod
- `service.yaml`: Exposes the pod as a service (NodePort)

When this repo is connected to ArgoCD, any changes pushed here (like image version updates) will automatically get deployed to the cluster.
