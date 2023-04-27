# arkLB - Helm

Helm charts for arkLB - an eBPF/XDP load balancer for microservices.

[Link to Repo](https://github.com/ark-7/ark-rust)

[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/arklb)](https://artifacthub.io/packages/search?repo=arklb)

## Instructions to use Helm charts

1. Install Helm CLI

2. Add the repo to Helm CLI

```bash
helm repo add arklb https://ark-7.github.io/arkLB-helm/
```

3. Install the chart

```bash
helm install [namespace] arklb/arklb 
```
