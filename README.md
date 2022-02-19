# yabetsu-grafana

grafana resources using kustomize

### How to build this kustomize?

1. Prod - kustomize build manifest/overlays/prod | kubectl apply -f -
2. QA - kustomize build manifest/overlays/qa | kubectl apply -f -
