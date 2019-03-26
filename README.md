# hicollege-demo

Install Azure CLI: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli

Azure login:
```
$ az login
```
 
Docker:
```
$ az acr login –name hicollege
$ docker run hicollege.azurecr.io/weather:0.0.1-SNAPSHOT
```

Run locally with Docker Compose:
```
$ docker-compose up
```

Kubernetes:
```
$ az aks install-cli --subscription HiCollege
$ az aks get-credentials --resource-group Microservices-2019 –name demo
```

Deploy:
```
$ kubectl create -f demo.yaml
```

Check status:
```
$ kubectl get svc
$ kubectl get pod
$ kubectl describe pod hello
```


Un-deploy:
```
kubectl delete -f demo.yaml
```
