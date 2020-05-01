$ vim deployment-nginx.yaml 
$ kubectl apply -f deployment-nginx.yaml 
$ kubectl get deployments -w
$ kubectl get deployments,rs,pods -w
$ kubectl get rs,pods -w
$ kubectl get rs,pods
$ kubectl get rs,pods,deployments
$ kubectl edit deployment nginx-deployment
$ kubectl get rs,pods,deployments
$ kubectl rollout status deployment nginx-deployment
$ kubectl get rs,pods,deployments
$ cat deployment-nginx.yaml 
$ kubectl annotate deployment nginx-deployment kubernetes.io/change-cause="image updated to 1.18.0"
$ vim deployment-nginx.yaml 
$ kubectl apply -f deployment-nginx.yaml 
$ kubectl get rs,pods,deployments
$ kubectl annotate deployment nginx-deployment kubernetes.io/change-cause="scale up to 3 replicas"
$ kubectl describe deployment
$ kubectl describe deployments
$ kubectl rollout history deployment nginx-deployment
$ kubectl rollout undo deployment nginx-deployment
$ kubectl get rs,pods,deployments
$ kubectl rollout history deployment nginx-deployment
$ kubectl rollout undo deployment nginx-deployment --to-revision=2
$ kubectl get rs,pods,deployments
$ kubectl delete deployment nginx-deployment
