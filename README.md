# eks

eksctl create cluster -f eksctl-params.yaml

eksctl delete cluster --name Test-Cluster

kubectl apply -f deployment.yaml
kubectl apply -f ingress.yaml
