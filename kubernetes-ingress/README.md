# Kubernetes Ingress 

Cilium uses the standard Kubernetes Ingress resource definition, with an `ingressClassName` of `cilium`. 

*Note: that the ingress controller creates a service of LoadBalancer type, so your environment will need to support this. 

## Ingress HTTP example

The example ingress configration routes traffic to backend services from the `bookinfo` demo microservices app.  Deploy the demo app: 

```
kubectl apply -f https://raw.githubusercontent.com/istio/istio/release-1.11/samples/bookinfo/platform/kube/bookinfo.yaml
```

...

## Ingress example with TLS termination


## Ingress gRPC example




