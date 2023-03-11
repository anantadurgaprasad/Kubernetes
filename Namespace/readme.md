## NameSpace
NameSpace is a k8 object which can be used to group k8 objects.
- The k8 objects in one namespace can't access k8 objects in another namespace by default.
- "ns" is shortform for namespace in k8

    below is the kubectl command to view all namespaces in your cluster
    ```
    kubectl get ns
    ```