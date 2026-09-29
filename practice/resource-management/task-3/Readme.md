# Resource Management Task 3 - Deploy compute resources

Lets see how the second demo app performs. Create the predefined manifest in the cluster:

```bash
kubectl apply -f deployment-demo-app-2.yaml
kubectl get deploy -n demo-app-2
```

Check if the deployment can scale to the desired number of replicas. In this case we should not have any issues. Check the amount of quotas and validate that there is still some space left.