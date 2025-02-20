# Install EKS



## Installing using Fargate

```
eksctl create cluster --name demo-cluster-name --region eu-north-1 --fargate
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster-name --region eu-north-1
```
