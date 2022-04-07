### Kubernetes Labs

### Minike

*minikube start --driver=docker*

*minikube status*

*minikube delete*


### Pods

*kubectl  run nginx --image name*

*kubectl describe pod name*

*kubectl get pods -o wide*

*kubectl get pods*

*kubectl apply -f pod.yaml* or kubectl create -f pod.yaml* pod is the name file yaml

### ReplicaSets

*kubectl get replicasets*

*kubectl get replicationcontroller*

*kubectl describe replicasets*

*kubectl scale replicaset name-rs --replicas=4*

### Deployments

*kubectl create -f deployments.yaml*

*kubectl get replicaset*

*kubectl get pods*

*kubectl get deployment*

*kubectl get all*

*kubectl create -f frontend.yaml --save-config --record*

*kubectl rollout status deployment/frontend-dp*

*kubectl rollout history deployment/frontend-dp*

*kubectl describe deployment frontend-dp*

### Networks
>It is a connection test of web pod in a mysql pod by command line

*kubectl get pods*

*kubectl describe pod mysql-pod*

*kubectl exec -it webapp-5499f96d5d-5xnhq -- bash* (webapp-5499f96d5d-5xnhq - it is name pod)

*apt search mysql-client*

*apt install default-mysql-client -y*

*mysql -h 172.17.0.3 -uroot -ppassword schooldb*

> FQDN - Fully Qualified Domain Name

*kubectl get all -n kube-system*

*apt update*

*apt install dnsutils -y*

*nslookup kuberntes*
