- to check the version of kubectl
kubectl version --client
- to start/run minikube
minikube start
- to check the status of minikube
minikube status
- to check the number of nodes you have
kubectl get nodes
- to know more about the nodes
kubectl get nodes -o wide
- to check namespace 
kubectl get ns
- to create namespace
kubectl create ns <new ns>
- to check your pods
kubectl get pods
- to deploy your pods
 kubectl apply -f deployment.yaml
- to know more about the pods
kubectl describe pod nginx-deployment-bf744486c-kccvz 
- to go inside the pod that is running
kubectl exec -it nginx-deployment-bf744486c-kccvz -- sh
- to run the minikube service/app
minikube service nginx
- to get the service
kubectl get svc
- to delete the service
kubectl delete service nginx