# COMANDO KUBERNETES

kubectl run <name-pod> --image=<image-name>:<version>
kubectl delete pod <name-pod>
kubectl describe pod <name-pod>
kubectl edit pod <name-pod>
kubectl get pods --watch
kubectl get pods -o wide
kubectl apply -f <path-file>
kubectl delete -f <path-file>
kubectl exec -it <name-pod> -- bash
kubectl get svc
kubectl get configmap
kubectl describe configmap <name-configmap>
kubectl get node -o wide