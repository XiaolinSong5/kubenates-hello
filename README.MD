minikube start --vm-driver=hyperkit
kubectl get all
kubectl get configmap
kubectl get secret
To see log of the pod: kubectl logs webapp-deployment-649d7fb885-nwbzv(name of the pod )
To see minikube Interal-ip: kubectl get node -o wide
To see service service port: kubectl get svc

minikube logs --file=logs.txt