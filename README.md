# helm-charts
Helm charts for Kubernetes

- Copy chart files into docs
- Regenerate repo index
```bash
$ helm repo index docs --url https://juexun.github.com/helm-charts
```
- Add repo
```bash
$ helm repo add juexun https://juexun.github.com/helm-charts
$ helm repo update