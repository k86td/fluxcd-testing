This repository is to explore Fluxcd deployment and capabilities. 

A Kubernetes cluter is created using Kind, where I'm sharing its network with other containers that have the tools (flux, kubectl) installed to manipulate the cluster. The other containers are attaching their network to Docker `kind` net to interact with the cluster.
