## Create EKS cluster

```
eksctl create nodegroup --config-file=1-2-node-group.yml

eksctl create cluster \
--name eksfar-demo \
--region us-east-2 \
--fargate \
--nodegroup-name eksfar5NodeGroup \
--node-type t2.medium \
--nodes 2 \
--nodes-min 2 \
--nodes-max 2 

```

## Check status from command line

```
aws eks --region us-east-2 describe-cluster --name eksfar-demo --query cluster.status

aws eks describe-cluster --name eksfar-demo

```

