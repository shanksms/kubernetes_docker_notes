# kubernetes_docker_notes
This contains important documentation and notes
## resources/webs links
1. [companion to ore'lly course on kubernetes] (https://github.com/DickChesterwood/k8s-fleetman)
2. [ore'lly course on kubernetes] (https://learning.oreilly.com/videos/kubernetes-microservices/10000DIHV201804/10000DIHV201804-kube_u04m03/)

### What is difference between docker image and container?

### What is minikube

### Why container orchestration is needed? 
Imagine that you are running your microservices in containers. There are following opertional aspects you need to consider while running these containers:
1. Who will restart the container in case it crashed?
2. Lets say, you need to spin off new containers in case of spike in the usage. Who takes resposibility of monitoring the compute and storage resources on the machines and spin new containers. 
3. Similar to point#2, how do you kill the containers in case of under usage?

It seems, we need an automation tool to manage the operational aspect of running containers. That is where Kubernetes comes in to picture.
