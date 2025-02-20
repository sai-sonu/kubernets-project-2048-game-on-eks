# 2048 App

## Create Fargate profile

```
eksctl create fargateprofile \
    --cluster <cluster-name> \
    --region <region-details(us-east-1)> \
    --name alb-sample-app \
    --namespace game-2048
```

## Deploy the deployment, service and Ingress

```
kubectl apply -f https://raw.githubusercontent.com/sai-sonu/kubernets-project-2048-game-on-eks/refs/heads/main/2048_full.yaml
```





![2048-Game](https://github.com/sai-sonu/kubernets-project-2048-game-on-eks/blob/0cdb26bc8b0e02c334584ed4b4b222e29a153430/2048_screenshot.jpg)
