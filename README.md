# Create and Delete Resources
```dockerfile
kubectl apply -f pod.yml
cat pod.yml | kubectl apply -f -

kubectl delete -f pod.yml
kubectl delete pod hello-world
```