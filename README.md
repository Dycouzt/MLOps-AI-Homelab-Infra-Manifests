# MLOps Platform Infrastructure Manifests

This repository contains all Kubernetes manifests for the AI-Augmented MLOps Platform.

## Structure
- `platform/` - Core platform services (ArgoCD, MLflow, Prometheus)
- `applications/` - ML application deployments (managed by ArgoCD)

## Clusters
- **GCP Cluster**: Platform services
- **k3d Cluster**: ML inference workloads

## GitOps Workflow
All changes to this repo are automatically synced to the clusters by ArgoCD.