# argo-playground


## kubectl Deploy

### Apply
```
kubectl apply -f deployments/nginx/namespace.yml
kubectl apply -f deployments/nginx/deployment.yml -f deployments/nginx/service.yml
```

### Delete
```
kubectl delete -f deployments/nginx/deployment.yml -f deployments/nginx/service.yml -f deployments/nginx/namespace.yml
```

## Argo Deploy

### Create Argo Application
```
kubectl apply -f argo/application.yml
```

### Delete Argo Application
```
kubectl delete -f argo/application.yml
```