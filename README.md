# k8s-homelab

This repository contains the GitOps configuration for my home Kubernetes cluster using Flux.

## Repository Structure

```sh
├── apps
│   └── base
│       ├── kustomization.yaml
│       └── ...
│   └── home
│       ├── kustomization.yaml
│       └── ...
├── clusters
│   └── home
│       ├── flux-system
│       │   ├── kustomization.yaml
│       │   ├── ...
│       │   └── notifications
│       │       ├── kustomization.yaml
│       │       └── ...
│       │── apps.yaml
│       └── infrastructure.yaml
└── infrastructure
    ├── configs
│       ├── kustomization.yaml
│       └── ...
    └── controllers
│       ├── kustomization.yaml
│       └── ...
```

## Prerequisites

- Kubernetes cluster
- Flux CLI
- kubectl
