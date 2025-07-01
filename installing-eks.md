# Install EKS

Please follow the prerequisites doc before this.

## Install using Fargate

```
eksctl create cluster --name demo-cluster --region us-east-1 --fargate
```
####  --> the above command creates a eks cluster with fargate profile, one can change the cluster name as per need and also can change the region name 
####  --> typically cluster creation takes 25 to 30 mins of time


## Delete the cluster

```
eksctl delete cluster --name demo-cluster --region us-east-1
```



