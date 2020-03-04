List Master nodes
```
kubectl get nodes --selector='node-role.kubernetes.io/master'
```
List worker nodes
```
kubectl get nodes --selector='!node-role.kubernetes.io/master'
```
kubectl config get-contexts
```

kubectl config set-context kubesys --namespace=kube-system --user=kubernetes-admin --cluster=kubernetes
```
kubectl config current-context
```
kubectl config use-context kubesys
```
