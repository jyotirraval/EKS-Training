#ReplicaSet

Oeverview:

![pod drawio (1)](https://github.com/jyotirraval/EKS-Training/assets/31502473/742f1b15-543e-46e5-9f9b-8267990a64fa)

ReplicaSet across the Nodes:

![pod drawio (2)](https://github.com/jyotirraval/EKS-Training/assets/31502473/8113e2ba-1d9e-426c-95d9-0d771d1e993e)


Few commands related to ReplicaSet: <br />
kubectl get replicaset <br />
kubectl get rs <br />
kubectl create -f replicaset-definition.yaml <br />
kubectl delete replicaset replica-set-name (deletes all underlying PODs with this replicaset) <br />
kubectl scale --replicas=6 replicaset replica-set-name <br />
