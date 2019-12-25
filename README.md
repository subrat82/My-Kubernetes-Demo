# My-Kubernetes-Demo



Normal practice for Ingress:

Requisistes:
Namespace, ingress, service and deployment.

Also run :
The following Mandatory Command is required for all deployments.
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/mandatory.yaml

dfly-namespace-deployment.yaml
dfly-namespace-ingress.yaml
dfly-namespace-service.yaml
dfly-namespace.yaml

commands to create:
kubectl apply -f hotel-namespace.yaml
kubectl apply -f hotel-namespace-deployment.yaml
kubectl apply -f hotel-namespace-service.yaml
kubectl apply -f hotel-namespace-ingress.yaml

kubectl get ingress -n dfly-namespace



Refer to the following URL for Dockerfile and files related to nginx web page
https://github.com/nginxinc/NGINX-Demos/tree/master/nginx-hello
