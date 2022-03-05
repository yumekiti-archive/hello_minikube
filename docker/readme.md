
```
eval $(minikube docker-env)

docker build -t example/nginx:v1.0 .

kubectl apply -f webserver.yaml
```
