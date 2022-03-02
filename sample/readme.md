```
kubectl apply -f sample_nginx.yaml

kubectl expose deploy/nginx --port=80

kubectl port-forward svc/nginx 8080:80
```

```
kubectl delete deployment nginx

kubectl delete svc nginx
```