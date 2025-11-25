minikube start
minikube status
kubectl delete deployment mynginx
kubectl create deployment mynginx --image=nginx
kubectl expose deployment mynginx --type=NodePort --port=80
kubectl get pods
kubectl scale deployment mynginx --replicas=3
kubectl get pods
kubectl port-forward svc/mynginx 8081:80
