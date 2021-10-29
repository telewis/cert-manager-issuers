# cert-manager-issuers
Issuers for use with cert-manager

## Install cert-manager
```
$ helm install cert-manager jetstack/cert-manager --namespace cert-manager --create-namespace --version v1.6.0 --set installCRDs=true
```

## Deploy ClusterIssuer
```
$ kubectl apply -f letsencrypt.yaml
```

