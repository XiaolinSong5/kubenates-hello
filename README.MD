minikube start --vm-driver=hyperkit
minikube start --driver=docker
minikube status
kubectl get node
echo -n mongouser | base64
kubectl get pods
kubectl apply -f mongo-config.yaml
kubectl apply -f mongo-secret.yaml
kubectl apply -f mongo.yaml
kubectl apply -f webapp.yaml
kubectl get all
kubectl get configmap
kubectl get secret
kubectl describe service webapp-service
To see log of the pod: kubectl logs webapp-deployment-649d7fb885-nwbzv(name of the pod )
minikube ip

To see minikube Interal-ip: kubectl get node -o wide
To see service service port: kubectl get svc
kubctl exec -it webapp-deployment-649d7fb885-nwbzv(name of the pod ) --bin/bash

minikube logs --file=logs.txt
kubctl apply configfilename

config file has 3 parts`;
metadata
spec
status(is generated)
To assign external address to a service:
minikube service mongo-express-service
Install namespaces:
brew install kubectx
minikube addons enable ingress
