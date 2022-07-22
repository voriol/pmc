# helm

- monitoring

```
kubectl create ns monitoring

helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update

helm install prometheus prometheus-community/kube-prometheus-stack -n monitoring
```

- products

```
kubectl create ns pmc

helm install product-review product-review -n pmc
helm install product-service product-service -n pmc
```
