# Shell Access To A Running Pod
```dockerfile
kubectl exec -it hello-world -- sh
kubectl exec -it hello-world -- bin/sh
kubectl exec -it hello-world -c hello-world -- bin/sh
kubectl exec hello-world -- ls /
kubectl exec hello-world -- ps aux
```