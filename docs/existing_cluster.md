# Existing Cluster

If you already have a DC/OS 1.10+ cluster, Kubernetes is publicly available in the Catalog.  Please ensure your cluster satisfies the minimum [resource requirements](resource-requirements.md)

```
dcos package install beta-kubernetes
```

This will create a 3 node Kubernetes cluster via DC/OS.  