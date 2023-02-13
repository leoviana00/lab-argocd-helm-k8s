## Implantação com Helm

```bash
helm repo add argocd https://argoproj.github.io/argo-helm
helm repo update
kubectl create ns argo-cd
kubectl label namespace argo-cd istio-injection=enabled --overwrite
helm install -name argocd argocd/argo-cd -f values.yaml -n argo-cd
```

## Arquivos istio - Gateway e Virtual Service

```bash
kubectl apply -f templates/
```

## Acessando

- URL: http://argocd.lab.k8s.io