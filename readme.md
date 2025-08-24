general kubectl commands

kubectl apply -f <file_name.yaml>

kubectl get deployment hello-minikube
kubectl get service hello-minikube

Get Minikube IP address:
minikube ip 

 If you did not specify a NodePort, you can find the assigned port using 
 kubectl get services hello-minikube

 
