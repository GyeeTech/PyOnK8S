# PyOnK8S
Simple Python app running on K8S

### Run:
1. 
kubectl apply -f https://raw.githubusercontent.com/GyeeTech/PyOnK8S/master/flask-deploy.yaml

2.
kubectl apply -f https://raw.githubusercontent.com/GyeeTech/PyOnK8S/master/flask_service.yaml

3. 
minikube service hello-python-service --url  

Get logs:
$ kubectl logs -f -l app=hello-python3
