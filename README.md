# Learn Kubernetes

## Install

- Via Docker Desktop

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/enable-kubernetes.PNG" width="512" alt="Enable Kubernetes">

- Via Minikube

https://github.com/kubernetes/minikube
https://kubernetes.io/docs/tasks/tools/#kubectl

## Commands

### Check Kubernetes is running

`kubectl version`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/kubectl-version.PNG" width="512" alt="kubectl version">

### Get List Node

`kubectl get node`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/get-node.PNG" width="512" alt="Get List Node">

### Get Description Node

`kubectl describe node nodename`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/describe-node-nodename.PNG" width="512" alt="Get Description Node">

### Create Pod

`kubectl create -f filepod.yaml`

Example:

`kubectl create -f .\examples\create-pod.yaml`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/create-pod.PNG" width="512" alt="Create Pod">

### Get List Pod

`kubectl get pod`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/get-pod.PNG" width="512" alt="Get List Pod">

### Get List Detail Pod

`kubectl get pod -o wide`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/get-pod-o-wide.PNG.PNG" width="512" alt="Get List Detail Pod">

### Get Description Pod

`kubectl describe pod podname`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/describe-pod-podname.PNG.PNG" width="512" alt="Get Description Pod>

### Access Pod

`kubectl port-forward podname portAccess:portPod`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/port-forward-pod.PNG.PNG" width="512" alt="Access Pod">

Example:

`kubectl port-forward nginx 8080:80`

<img src="https://github.com/suriyadi15/learn-kubernetes/raw/main/assets/port-forward-pod-example.PNG.PNG" width="512" alt="Access Pod Example">
