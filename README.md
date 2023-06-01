Kubernetes manifests for deploying the thumbnail caching service

### Usage

```bash
kubectl apply -k .
```

### Prep Cert Manager

Pre-setup (already done)
```bash
cmctl x install --dry-run > cert-manager.custom.yaml
```

The cert manager yaml has already been created and is in `certs`