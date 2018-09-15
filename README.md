           ============  Kubernets ========
1. Introduction to Kubernets
2. Kubernets Basics
3. Advanced Topics
4. Kubernets Administration
5. Packaging and deploying on Kubernets
6. Serverless on Kubernets 
7. Microservices 
8. Installing Kubernets using kubeadm
9. on-prem or cloud agnostic Kubernets.


Chapter 1:- Introduction to Kubernets 

Installation of Minikube on MacOS.

1. brew cask install minikube

If we got an error from the above command, then there is an issue with existing minikube which is already installed. 

Warning: Cask 'minikube' is already installed.

To re-install minikube, run:
  brew cask reinstall minikube
try below 
2. brew cask reinstall minikube 

==> Satisfying dependencies
All Formula dependencies satisfied.
==> Downloading https://storage.googleapis.com/minikube/releases/v0.28.2/minikube-darwin-amd64
######################################################################## 100.0%
==> Verifying SHA-256 checksum for Cask 'minikube'.
==> Uninstalling Cask minikube
==> Purging files for version 0.28.1 of Cask minikube
==> Installing Cask minikube
==> Linking Binary 'minikube-darwin-amd64' to '/usr/local/bin/minikube'.
🍺  minikube was successfully installed!
BLRLA00149:~ vikekumar$ minikube start
Starting local Kubernetes v1.10.0 cluster...
Starting VM...
Getting VM IP address...
Moving files into cluster...
Setting up certs...
Connecting to cluster...
Setting up kubeconfig...
Starting cluster components...
Kubectl is now configured to use the cluster.
Loading cached images from config file.
