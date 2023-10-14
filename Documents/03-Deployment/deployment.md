#Deployent

Overview:

![depl drawio](https://github.com/jyotirraval/EKS-Training/assets/31502473/e460e5d4-9a7d-4572-8237-3d05f0a6646c)

Few commands: <br />
kubectl get deployments <br />
kubectl get deployments -o wide <br />
kubectl describe deploy <DEPLOYMENT_NAME> <br />
kubectl get deployments <br />
kubectl create -f deployment-definition.yaml <br />
kubectl create deployment --image=nginx nginx --replicas=4 --dry-run=client -o yaml > nginx-deployment.yaml <br />
