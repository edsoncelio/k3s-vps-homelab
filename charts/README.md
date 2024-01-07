# Charts setup



## loki stack
```
helm upgrade --install loki --namespace loki-stack --create-namespace grafana/loki-stack -f charts/loki-stack.yaml
```