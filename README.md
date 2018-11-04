# HC-BC

# Prereqs for Production
- kubectl
- a k8s cluster and the kubeconfig
- skaffold (optional to deploy all k8s files and building all images)

set kubectl context to prod
```
kubectl config use-context <context-name>
```

run skaffold
```
skaffold run
```

# Prereqs for Dev
- docker
- docker-compose
Run:
```
docker-compose up
```