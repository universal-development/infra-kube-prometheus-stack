# infra-kube-prometheus-stack
Repository to deploy kube-prometheus-stack helm chart

```
helm repo add prometheus-community https://prometheus-community.github.io/helm-charts
helm repo update

helm -n <namespace> upgrade --install <name> prometheus-community/kube-prometheus-stack --values values.yaml

```

## References

https://github.com/prometheus-community/helm-charts/tree/main/charts/kube-prometheus-stack
