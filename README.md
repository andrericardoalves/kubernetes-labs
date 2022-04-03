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
