
```
eval $(minikube docker-env)

docker build -t node/myapp .

kubectl apply -f deployment-service.yaml
```
