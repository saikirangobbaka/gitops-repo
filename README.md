# GitOps Repository - Kubernetes Manifests

This repository contains Kubernetes manifests for ArgoCD deployment.

## Files
- deployment.yaml - Application deployment
- service.yaml - Kubernetes service
- configmap.yaml - Configuration
- argocd-app.yaml - ArgoCD application definition

## GitOps Workflow
Jenkins updates deployment.yaml with new image tags → ArgoCD detects change → Auto-deploys to Minikube
