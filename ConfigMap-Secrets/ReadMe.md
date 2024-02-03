1. Create a deployment.
2. Create a ConfigMap and define the environment,
3. Configure the deployment file,
4. Now apply the changes.
5. Login into pod using $ kubectl exec -it pod-name -- /bin/bash,
6. Check env is created or not using $ env | grep env-name.
7. If we do any changes in env, it won't get changed inside the container so create a Volume for it.
8. Apply the changes and get into the Container then check it,
9. We don't want to restart the pods if we use volumes. 
