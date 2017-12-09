# kube-openproject

## Prerequisitions

- kubernetes cluster
- nfs for kubernetes persistent volume

## deployment

```sh
$ kubectl apply -f nfs-pv.yaml
$ kubectl apply -f postgres.yaml -f postgres-svc.yaml
$ kubectl apply -f openproject-po.yaml -f svc.yaml
```

