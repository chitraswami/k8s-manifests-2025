# K8s Manifests Repository

This repository contains Kubernetes manifests for AlphaTechx applications.

## Structure

```
alphatechx/
├── production/     # Production environment manifests
└── staging/        # Staging environment manifests
```

## Usage

This repository is used by the CI/CD pipeline to store generated Helm manifests.
ArgoCD monitors this repository for automatic deployments.

## Applications

- **alphatechx**: AI Technology Platform backend service 