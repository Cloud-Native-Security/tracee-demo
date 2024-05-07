# Tracee Demo and Example

This repository includes several example to use [Tracee.](https://github.com/aquasecurity/tracee)

This GitHub repository is part of the Tracee Kubernetes series on:

* [My blog](https://anaisurl.com/tracee-ebpf-helm-installation/)
* The Aqua Open Source YouTube Channel -- [Link to Playlist](https://youtu.be/YQdEvf2IS9k?si=ukORYGrNj0drwOhL)

Additional ebpf related tutorials:

* [Introduction to ebpf](https://youtu.be/MQ1fel5lU0k?si=JrBSPqm5FSLid_2b)
* [Getting started with eBPF in Kubernetes - Tracee Installation Guide](https://anaisurl.com/tracee-ebpf-helm-installation/)

## Installation

Installing Tracee on a [Kubernetes cluster.](https://aquasecurity.github.io/tracee/latest/docs/install/)

```
helm upgrade --install tracee aqua/tracee --namespace tracee-system --create-namespace 
```
