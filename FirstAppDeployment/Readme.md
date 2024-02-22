Deploying first App on Cluster:

1. Install Kubectl for managing K8S Cluster,
2. Install Minikube for Creating K8S Cluster,
3. Start Minikube: $minikube start --memory=2046 --driver=docker,
4. Check node is created using: $kubectl get nodes,
5. Create pod and specify the things in it: $touch pod.yml then edit it,
6. Run the pod.yml file using: $kubectl create/apply -f pod.yml,
7. Check whether the pod is created using: $kubectl get pods and to see detailed of the running pod use $kubectl get pods -o wide,
8. Log into it and run the pod using: $minkube ssh and $curl ip of the pod,
9. Pod will show the result.
10. You can debug it using: $kubectl describe pod pod-name to see the state & details of the pod and $kubectl logs pod-name to see logs of it.
11. For deleting the pod use: $kubectl delete pod pod-name.
