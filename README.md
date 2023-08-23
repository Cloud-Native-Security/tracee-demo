# Tracee Demo and Example

This repository includes several example to use [Tracee.](https://github.com/aquasecurity/tracee)

List of Examples:
1. [Tracee Policies](./policies/overview.md)

## Installation

Installing Tracee on a [Kubernetes cluster.](https://aquasecurity.github.io/tracee/v0.14/getting-started/kubernetes-quickstart/)

Install on arm

```
helm upgrade --install --set image.tag=aarch64-0.17.0 tracee aqua/tracee --namespace tracee-system --create-namespace 
```