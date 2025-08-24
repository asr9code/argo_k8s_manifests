general kubectl commands

kubectl apply -f <file_name.yaml>

kubectl get deployment hello-minikube
kubectl get service hello-minikube

Get Minikube IP address:
minikube ip 

 If you did not specify a NodePort, you can find the assigned port using 
 kubectl get services hello-minikube

 port forward to echo server from local
    kubectl port-forward hello-world-deployment-948d54d9-4pfx9 8088:8080 --namespace hello-world-namespace