Flagsmith Helmchart for offline usage

helm install -n flagsmith --create-namespace flagsmith .\flagsmith2-helm-sb\flagsmith2-helm-sb\
kubectl -n flagsmith port-forward svc/flagsmith-frontend 8080:8080

helm install flagsmith --debug --dry-run .\flagsmith-charts-main\charts\flagsmith\

helm uninstall flagsmith -n flagsmith


# Flagsmith Charts

Official Helm charts for Flagsmith, [https://flagsmith.github.io/flagsmith-charts/](https://flagsmith.github.io/flagsmith-charts/)

- [Flagsmith](./charts/flagsmith/)

## Usage

Add this repository using:

```bash
helm repo add flagsmith https://flagsmith.github.io/flagsmith-charts/
```
