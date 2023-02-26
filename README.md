## kubernetes
Estudo sobre kubernetes

# comands
kubectl get pods --watch

kubectl get service

kubectl get svc

kubectl delete pod

kubectl apply -f ./name.yaml

kubectl -f ./name.yaml

kubectl describe pod 'namepod'

kubectl exec -it 'namepod' -- bash

# struct: news portal

pod: first-pod

# struct: theory

pod:
    - pod01
    - pod02
    - svc-pod-02

NodePort:
    - svc-pod-01

loadbalancer: 
    - svc-pod-01-loadbalancer