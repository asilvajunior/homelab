<p align="center">
<img src="assets/images/unicast_logo.png">
</p>

# Unicast Cloud Homelab

A repository to store and share the infrastructure, materials and codes, from my small self-hosting homelab. This repository contains everything I use to setup and run the devices in my homelab. For more details, see the README of the following directories.

**01** automated installation.
**02** roles for additional configuration and application installation.
**03** to manage my Kubernetes cluster.
**04** is a collection of scripts to ease the maintenance of all this.

<div> 
  <a href="https://www.linkedin.com/in/antoniocarlosjr" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=fflat&logo=linkedin&logoColor=white" target="_blank"></a>
  <a href="http://www.unicastlab.com.br/" target="_blank"><img src="https://img.shields.io/badge/-Website%2fBlog-blue?style=flat&logo=website&logoColor=white&link="_blank"></a> 
  <a href="https://discord.gg/S6zFKGA7hg" target="_blank"><img src="https://img.shields.io/badge/Discord-7289DA?style=flat&logo=discord&logoColor=white" target="_blank"></a> 
  <a href= "https://www.youtube.com/channel/UCYpdjQbbkBQpDWI1rapkVUA"><img src="https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white" target="_blank"></a>
  <a href="https://www.instagram.com/unicastlab/" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white" target="_blank"></a>
</div>

## ⚙️ Hardware

The below lists the hardware and some specs of my homelab & network infrastructure

| Device             | CPU        | RAM   | Storage              | Operating System              | Purpose    |
| -------------------|------------|-------|----------------------|-------------------------------|------------|
| Dell OptiPlex 3060 | I7-6700    | 16GB  | 500GB HDD            | WIN19K Datacenter             | Hypervisor |
| TP-Link TL-SG1008P | N/A        | N/A   | N/A                  | N/A                           | Switch PoE |
| MikroTik hAP Ac2   | IPQ-4018   | 128MB | 16MB                 | RouterOS                      | Router     |
| Raspberry Pi 3B+   | Cortex-A53 | 1GB   | 64GB SD Card         | Raspberry PI OS Lite (64-BIT) | Pi-hole    |
| Raspberry Pi 4B    | Cortex-A72 | 4GB   | 64GB + 2x1TB SD Card | Raspberry PI OS Lite (64-BIT) | OMV6 NAS   |

## ✨ Features

Project status: **Alpha**

- [ ] Fully automated with infrastructure as code 
- [ ] Modularized components stand on layered architecture
- [ ] Versioned and declarative infrastructure on top of GitOps
- [ ] Kubernetes cluster setup via k3s
- [ ] Distributed storage
- [ ] CI/CD platform
- [ ] Observability platform

## :wrench:&nbsp; Tech stack

My homelab uses the following software.

<table>
  <tr>
    <th>Logo</th>
    <th>Name</th>
    <th>Description</th>
  </tr>
  <tr>
    <td><img width="32" src="https://www.vectorlogo.zone/logos/ansible/ansible-icon.svg"></td>
    <td><a href="https://www.ansible.com">Ansible</a></td>
    <td>Server configuration</td>
  </tr>
  <tr>
    <td><img width="32" src="https://www.vectorlogo.zone/logos/debian/debian-icon.svg"></td>
    <td><a href="https://www.debian.org">Debian</a></td>
    <td>Base OS for all servers</td>
  </tr>
  <tr>
    <td><img width="32" src="https://www.vectorlogo.zone/logos/docker/docker-tile.svg"></td>
    <td><a href="https://www.docker.com">Docker</a></td>
    <td>Container runtime</td>
  </tr>
  <tr>
    <td><img width="32" src="https://www.vectorlogo.zone/logos/kubernetes/kubernetes-icon.svg"></td>
    <td><a href="https://kubernetes.io">Kubernetes</a></td>
    <td>Container orchestration</td>
  </tr>
  <tr>
    <td><img width="32" src="https://www.vectorlogo.zone/logos/terraformio/terraformio-icon.svg"></td>
    <td><a href="https://www.terraform.io">Terraform</a></td>
    <td>Provisioning</td>
  </tr>
</table>

## :memo: License

This project is under [MIT License](./LICENSE).
