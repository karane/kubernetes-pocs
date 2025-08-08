# Kubernetes Hello World

## How to Run

```bash
kubectl apply -f hello-deployment.yaml        
kubectl apply -f hello-service.yaml
kubectl get pods # it shows pods running
kubectl get services # it shows available services, check for hello-world
kubectl port-forward svc/hello-service 8080:80
```

Now, go to your browser for `localhost:8080`. It should show the "Welcome to nginx" page.