# microcks-kustomize-manifests
This repo is using kustomize to deploy microcks helm charts in your K8S cluster

## Installation
```
$ kubectl kustomize --enable-helm | kubectl apply -f - 
```

## Issues
- https://github.com/keycloak/keycloak/issues/11133
