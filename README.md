# hackazon-k8s - Description
A collection of YAML files to deploy Hackazon in k8s with NGINX Ingress Controller in a Kubernetes Cluster. 

This specific version of the yaml files collection will assume that we can create a k8s PV and PVC over a Gluster Filesystem exporting a volume called "k8s-udf-storage". 

As another prerequisite, in that specific volume on the GlusterFS Server, an "hackazon" directory must be present and filled with content taken from this repository (rapid7/hackazon)[https://github.com/rapid7/hackazon] 

The "hackazon" directory's ownership must be www-data:www-data
