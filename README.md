# Access Pod via Port Forward
```dockerfile
kubectl port-forward hello-world 8080:80
kubectl port-forward pod/hello-world 8080:80
kubectl port-forward service/hello-world 8080:80
```