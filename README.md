# kubernetes_docker_notes
This contains important documentation and notes
## resources/webs links
1. [companion to ore'lly course on kubernetes] (https://github.com/DickChesterwood/k8s-fleetman)
2. [ore'lly course on kubernetes] (https://learning.oreilly.com/videos/kubernetes-microservices/10000DIHV201804/10000DIHV201804-kube_u04m03/)
3. [AWS ECS/EKS with EC2 and FarGate] (https://www.youtube.com/watch?v=AYAh6YDXuho)

### What is difference between docker image and container?

### What is minikube

### Why container orchestration is needed? 
Imagine that you are running your microservices in containers. There are following opertional aspects you need to consider while running these containers:
1. Who will restart the container in case it crashed?
2. Lets say, you need to spin off new containers in case of spike in the usage. Who takes resposibility of monitoring the compute and storage resources on the machines and spin new containers. 
3. Similar to point#2, how do you kill the containers in case of under usage?
It seems, we need an automation tool to manage the operational aspect of running containers. That is where Kubernetes comes in to picture.
<br> 
Examples of container orchestration tools are: AWS ECS, Kubernetes, Hashicorp Nomad etc

### Understanding ECS with EC2 and Fargate and EKS with EC2 and Fargate
ECS is a competitor of EKS. EKS is built on Kubernetes
With EKS you have two options of running container applications:
1. with EC2 fleet of machines
2. with Fargate
