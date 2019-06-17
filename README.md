docker build -t atmohsin/nodedemo .

docker images

docker run -p 8080:8080 -d atmohsin/nodedemo

docker ps

docker logs <container_id>

docker exec -it <container id> /bin/bash

curl -i localhost:8080

docker login
docker push atmohsin/nodedemo:latest

kubectl get pods
kubectl get deployments
kubectl get services
kubectl apply -f deployment.yml
kubectl apply -f service.yml

curl http://localhost:8080

kubectl delete deployments/nodedemo
kubectl delete services/nodedemo