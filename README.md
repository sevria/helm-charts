# helm-charts

```shell
helm registry login ghcr.io

helm package ./service

helm push service-0.1.0.tgz oci://ghcr.io/sevria/helm-charts
```
