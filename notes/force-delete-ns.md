## Delete Namespace Force

- Em uma sessão:

```bash
kubectl proxy
```

- Em outra sessão:

```bash
kubectl get ns <bad-namespace> -o json | jq '.spec.finalizers=[]' | curl -X PUT http://localhost:8001/api/v1/namespaces/<bad-namespace>/finalize -H "Content-Type: application/json" --data @-