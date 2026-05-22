
![License](https://img.shields.io/badge/License-MIT-green)
![Platform](https://img.shields.io/badge/Platform-Ubuntu-orange)
![DevOps](https://img.shields.io/badge/DevOps-Ready-blue)
![Automation](https://img.shields.io/badge/Automation-Enabled-blue)

# Nexoryx_Kubernetes_AI_Platform

Production-ready Kubernetes AI platform with:

- Ollama
- Open WebUI
- Qdrant
- PostgreSQL
- Redis
- Persistent Storage
- Services
- Ingress
- Autoscaling
- Resource Limits
- Secrets
- GPU-ready architecture

## Deploy

```bash
kubectl apply -f kubernetes/
```

## Namespace

```bash
nexoryx-ai
```

## Features

- Kubernetes-native AI infrastructure
- Persistent volumes
- Service discovery
- Horizontal Pod Autoscaler
- NGINX ingress
- Production-ready manifests
- Secret management
- Resource requests and limits
- Health probes

## Components

- Ollama
- Open WebUI
- PostgreSQL
- Redis
- Qdrant
- Ingress
- HPA

## Notes

Update passwords and domains before production deployment.


## Project Roadmap

- [ ] Kubernetes Helm charts
- [ ] GitOps support
- [ ] CI/CD improvements
- [ ] Monitoring dashboards
- [ ] Multi-cloud support
- [ ] Security hardening

## GitHub Actions

This repository includes:
- Shell validation
- Markdown linting
- Terraform validation (where applicable)

## Example Deployments

See:
- examples/
- docs/

## Related Nexoryx Projects

This repository is part of the Nexoryx infrastructure ecosystem.
