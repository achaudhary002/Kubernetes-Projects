# 📂 Kubernetes Projects Collection

## This repository contains a collection of hands-on projects focused solely on Kubernetes.  This was the project I did quite time ago. I was learning Kubernetes at the time. I have learnt to use manifests (.yml files), how to write them, understand the metadata, deploying pods, inspecting pods, reading log files of individual pods, creating namespaces, services and all.  
---

## **1. multi-tier project **
** multi-tier project ** [multi-tier](./multi-tier)  
The multi-tier project Covers all the essential components of Orchestration tool. The project is designed on simple way. Each folder (frontend and backend) contains their source code for the app. and its Dockerfile that kubernetes uses to build their pods. In addition, folder (manifests) has .yml files for deployments, services, secrets and env values. K3 reads the metadata inside these .yml files and builds the services. I have also included the commands and architecture of the overall project on the .png file. Please check it out. 
- 

--- 
## ⭐ Learn More on Next Steps:
1. Clone the repository:

```bash
git clone https://github.com/achaudhary002/Kubernetes-Projects.git
```
2. Read The Documentation:
    Each projects include the project documentation file. It explains in detail about all the steps, commands, and troubleshooting