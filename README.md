# k8s-management V2


## Initial Setup

You can use the following commands to set up argoCD and the k8s-management repo.

```bash
# Install ArgoCD CLI
kubectl create namespace argocd
kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/refs/tags/v2.14.10/manifests/install.yaml
kubectl kustomize . | kubectl apply -f -
```
