## Replica Set

### Scaling Replicasets

```bash
kubectl scale --replicas=6 -f <YAML file>
```

```bash
kubectl scale --replicas=6 replicaset my-app-replicaset
```

### get replica

```bash
kubectl get replicaset
```

### delete replica set

```bash
kubectl delete replicaset <replicaset name>
```

### replace replicaset

```bash
kubectl replace -f <defintion-file>
```

### get all resources

```bash
kubectl get all
```
