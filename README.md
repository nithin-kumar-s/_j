http://localhost:8080/nithin
sudo snap install docker
sudo docker build -t my-java-app .
Sudo docker run -d -p 8080:8080 my-java-app
sudo docker compose up
sudo snap install minikube --classic
kubectl apply -f myapp.yml
kubectl get deployments
kubectl get services
minikube service myapp-service
