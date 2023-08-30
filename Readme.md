# K8 commands line
docker images
docker build -t hello-world-flask .


kubectl apply -f deployment.yml

curl localhost   

kubectrl delete service hello-world-flask-service 
kubectl get services     
kubectl delete deployment hello-world-flask
kubectl delete deployment deployment.yml
kubectl explain service