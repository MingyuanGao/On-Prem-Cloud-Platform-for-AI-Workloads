# On-Prem Cloud Platform for AI Workloads
This repo contains the engineering notes of an *On-Prem Cloud Platform for AI Workloads* with *Oracle Linux KVM*, *Oracle Linux Virtualization Manager (OLVM)*, *Docker*, *Podman*, *Kubernetes* (specically, Oracle Cloud Native Environment) and *MLOps and DevOps* tools (e.g., Kubeflow, ArgoCD) on top of the AMD EPYC 9655 CPUs and Nvidia H100 GPUs.

## Overview of the Platform
![Overview of the On-Prem Cloud Platform](<./figures/AI Platform.png>)


## Index
### Virtualizing the Nvidia H100 GPU in Oracle Linux for KVM VMs
### Virtualizing the Nvidia H100 GPU in Oracle Linux for Podman Containers via MIG Instances
### Creating LACP-mode Network Bonds to Boost Network Performance and Reliability
### Provisioning Ceph Block Storage to OLVM via NVMe/TCP
### Backing up Ceph Storage to TrueNAS to Amazon S3
### Enabling VNC Encryption via TLS
### Getting an SSO token from oVirt Engine to interact with its REST API for automation tasks
### Migrating VMs from VMware vSphere to OLVM with virt-v2v
### Migrating VMs from Sangfor Cloud Platform to OLVM with virt-v2v
