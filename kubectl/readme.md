### Namespace
- get all namespaces in a cluster
```
kubectl get ns
```
- change namespace with below cmd
```
kubectl config set-context $(kubectl config current-context) --namespace=<namespace-name>

```