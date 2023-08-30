# Tracee Demo and Example

This repository includes several example to use [Tracee.](https://github.com/aquasecurity/tracee)

This GitHub repository is part of the Tracee Kubernetes series on:

* [My blog](https://anaisurl.com/tracee-ebpf-helm-installation/)
* The Aqua Open Source YouTube Channel -- [Link to Playlist](https://youtu.be/YQdEvf2IS9k?si=ukORYGrNj0drwOhL)

List of Examples in this repository:
1. [Tracee Policies](./policies/overview.md)

## Installation

Installing Tracee on a [Kubernetes cluster.](https://aquasecurity.github.io/tracee/v0.14/getting-started/kubernetes-quickstart/)

```
helm upgrade --install tracee aqua/tracee --namespace tracee-system --create-namespace 
```