```
helm repo add grafana https://grafana.github.io/helm-charts
helm repo update
```
```
helm install loki-stack grafana/loki-stack --namespace grafana
```
