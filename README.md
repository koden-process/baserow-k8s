# baserow-k8s

kubectl apply -f namespace.yaml
kubectl apply -f secret.yaml
kubectl apply -f postgre_deployment.yaml
kubectl apply -f postgre_service.yaml
kubectl apply -f deployment.yaml
kubectl apply -f service.yaml
kubectl apply -f ingress.yaml