# Create pods Imperative Command
```dockerfile
kubectl run hello-world --image=amigoscode/kubernetes-hello-world --port=80
kubectl port-forward pod/hello-world 8080:80
kubectl get pods
```