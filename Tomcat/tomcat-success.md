kubectl run my-tomcat --image=jsevans/tomcat-opensuse --replicas=2 --port=8080
kubectl expose deployment my-tomcat --port=8080 --type=NodePort
