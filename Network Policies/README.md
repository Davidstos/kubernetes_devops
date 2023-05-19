> **Note**
> By default there is no network isolation between all the pods of the cluster, that's why you have to set up networks policies. 
>You can find here some examples of network policies

To apply a policy :

```bash
kubectl apply -f NETWORK_POLICY_NAME.yaml -n NAMESPACE

# or 

kubectl apply -f NETWORK_POLICY_NAME.yaml

# it depends if in the manifest we specify the namespace and if we want to apply the rule at the cluster level
```