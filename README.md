# Workshop Kubernetes

There are two quick ways of running locally kubernetes, either by using MicroK8s for linux users or by installing Minikube.

## Microk8s 

Install snap first if you are not running Ubuntu 16.04 LTS or 18.04 LTS :

https://docs.snapcraft.io/installing-snapd/6735

If you are using Ubuntu 16.04 LTS or 18.04 LTS : 

``` sudo snap install microk8s --classic ```
``` sudo microk8s.start ```

to check if it runs 

``` microk8s.kubectl get all --all-namespaces ```

Then you are ready for the exercices !

## Minikube installation : 

### Windows

As minikube will need to create a VM, you'll need to download hyperV and then you'll be able to install minikube itself.

HyperV:
https://minikube.sigs.k8s.io/docs/reference/drivers/hyperv/

Minikube : 
https://minikube.sigs.k8s.io/docs/start/windows/

kubectl : 
https://kubernetes.io/docs/tasks/tools/install-kubectl/#kubectl-install-curl-2

Virtual box is an option as well. 

### macOS

As minikube will need to create a VM, you'll need to download Hyperkit or if you use parallels, you can download the driver for parallels and then you'll be able to install minikube itself.

Hyperkit driver:
https://minikube.sigs.k8s.io/docs/reference/drivers/hyperkit/

parallels driver : 
https://minikube.sigs.k8s.io/docs/reference/drivers/parallels/

Minikube : 
https://minikube.sigs.k8s.io/docs/start/macos/
kubectl : 
https://kubernetes.io/docs/tasks/tools/install-kubectl/#kubectl-install-curl-0

Virtual box is an option as well. 

### Linux

As minikube will need to create a VM, you'll need to download KVM and then you'll be able to install minikube itself.

KVM : 
https://minikube.sigs.k8s.io/docs/reference/drivers/kvm2/

Minikube : 
https://github.com/kubernetes/minikube#linux

kubectl : 
https://kubernetes.io/docs/tasks/tools/install-kubectl/#kubectl-install-curl-1

Virtual box is an option as well. 

### Docker best practices

This should help you! : 
https://docs.docker.com/develop/develop-images/dockerfile_best-practices/
