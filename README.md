# k8s-management V2


## Initial Setup

You can use the following commands to set up argoCD and the k8s-management repo.

```bash
kubectl create namespace argocd
kubectl kustomize --enable-helm  . | kubectl apply -f -
```
