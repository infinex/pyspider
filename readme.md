
## deploy a kubernates cluster for pyspider

create a configmap for config.json
```
kubectl create configmap config --from-file config.json
```

apply all the rest of the file mysql,rabbitmq... 
```
kubectl apply -f ...
```

