kubectl run my-apache --image=jsevans/apache-opensuse --replicas=2 --port=8080
kubectl expose deployment my-apache --port=8080 --type=NodePort
