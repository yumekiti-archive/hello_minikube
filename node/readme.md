
```
eval $(minikube docker-env)

docker build -t node/myapp .

kubectl apply -f deployment-service.yaml

kubectl port-forward service/myapp 8080:3000
```
