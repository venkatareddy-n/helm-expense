commands to execute this project.

1. need to create namespace

kubectl apply -f namespace.yaml

2. create mysql using helm

helm install mysql .

3. Create backend using helm

helm install backend .

4. Create frontend using helm

helm install frontend .

kubens expense --> to set namespace as expense

kubectl get pods --> to see all pods 

kubectl get svc --> to se service url

helm list --> to list all helm 

To un-install
=============
helm uninstall frontend

helm uninstall backend

helm uninstall mysql
