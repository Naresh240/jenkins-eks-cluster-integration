# jenkins-eks-cluster-integration
## Pre-requisites
```sh
1. EKS Cluster
2. Jenkins Sever

Install below softwares in Jenkins Server
- Install Java
- Install GIT
- Install Maven
- Install Docker
- Install Kubectl
```

```Note```:
1. we need to add jenkins user to docker group
```sh
usermod -aG docker jenkins
```

2. Add docker pipeline plugin
3. Add Dockerhub credentials in jenkins with the name of "docker_credentials"

## Run Jenkinsfile
```sh
1. Add role to jenkins server to communicate with EKS Cluster
2. provide cluster name and region as parameter while running pipeline
```
