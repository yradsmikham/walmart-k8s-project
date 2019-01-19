# walmart-k8s

AKS Manifest Repository for CI/CD Workflow

This respository contains:
- Kubernetes manifest files generated by [Fabrikate](https://github.com/Microsoft/fabrikate).

## Configuration

- A Personal Access Token is generated for this repository and stored as an encrypted Azure Pipeline build variable.
- This repository uses [Flux](https://github.com/weaveworks/flux) to retrieve updates made to manifest files.
