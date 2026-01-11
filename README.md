# go-web-app
End-to-end DevOps project demonstrating CI/CD, Docker, Kubernetes, Helm, Argo CD, and multi-environment deployment (staging &amp; production).

# Go Web App – DevOps Project

This repository contains an end-to-end DevOps implementation of a simple Go web application.

The project demonstrates:
- CI using GitHub Actions
- Docker image build
- Kubernetes deployment
- Helm-based application packaging
- GitOps-style CD using Argo CD
- Separate staging and production environments
- Multi-node Kubernetes cluster with dedicated DevOps/control plane

## High-Level Architecture

Developer → GitHub → CI → Container Registry → Kubernetes → Ingress → Users

