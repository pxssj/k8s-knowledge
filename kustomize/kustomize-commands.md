```
$ kubectl kustomize ./nginx/
$ kubectl apply -k nginx
$ kubectl get deployments
$ vim nginx/kustomization.yaml 
$ kubectl apply -k nginx
$ kubectl get deployments
$ kubectl rollout history deployment nginx-deployment
$ kubectl get pods,svs,deployments
$ kubectl kustomize ./registry/overlays/dev/
$ kubectl apply -k ./registry/overlays/dev/
$ kubectl get rs,pods,deployments
$ kubectl kustomize ./registry/overlays/prod/
$ kubectl apply -k ./registry/overlays/prod/
$ kubectl get rs,pods,deployments
$ kubectl diff -k ./registry/overlays/prod/
$ kubectl delete -k ./registry/overlays/prod/
$ kubectl delete -k ./registry/overlays/dev/
$ kubectl get rs,pods,deployments
```
