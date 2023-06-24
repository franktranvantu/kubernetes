# Rolling Update In Action
```dockerfile
kubectl apply -f deployments/deployment.yml
kubectl port-forward deploy/hello-world 8080:80
```