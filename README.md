# DevOps inter final assesment 

Name: Mubendiran K,

Date: 14.10.2025

This mini project demonstrates the working of complete DevOps workflow using git,docker,ci/cd,nomad and monitoring tools like grafana loki 

SCRIPT:
created a bash script for sysinfo and executed perfectly 
proof of attachment:
 ![alt text](image.png)

DOCKER:
created a dockerfile to container hello.py 
build the image and pushed to github 
proof of attachment:
 ![alt text](image-1.png)

 CI/CD :

 added a ci test workflow using github actions 

 Status badge : [![CI Pipeline](https://github.com/MUBENDIRAN/devops-intern-final/actions/workflows/docker-image.yml/badge.svg)](https://github.com/MUBENDIRAN/devops-intern-final/actions/workflows/docker-image.yml)

 NOMAD:

Created a Nomad job specification for deploying the containerized application.
Location: nomad/hello.nomad

Configuration:

Job type: service
Driver: Docker
Resources: 100 MHz CPU, 128 MB memory

proof of attachment:
![alt text](image-3.png)


GRAFANA LOKI:

Setup includes:

Running Loki in Docker
Configuring log forwarding from containers
Querying logs via API or Grafana

proof of attachment:
![alt text](image-2.png)
