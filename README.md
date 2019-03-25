# hicollege-demo

Install Azure CLI: https://docs.microsoft.com/en-us/cli/azure/install-azure-cli

Azure login:
```
$ az login
```
 
Docker:
```
$ az acr login –name hicollege
$ docker run hicollege.azurecr.io/weather:v1
```
Kubernetes:
```
$ az aks install-cli --subscription HiCollege
$ az aks get-credentials --resource-group Microservices-2019 –name demo
```

