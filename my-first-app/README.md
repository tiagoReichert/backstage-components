# my-first-app

My first Backstage-deployed app

## Deployment

Deployed via ArgoCD GitOps.

- **Namespace:** `my-first-app`
- **Replicas:** 2 - 10

## Access

```bash
kubectl port-forward -n my-first-app svc/my-first-app 8080:80
```

Open http://localhost:8080
