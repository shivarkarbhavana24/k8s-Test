# Kubernetes Web Application Deployment

## Deployment Name
webapp-deployment

## Service Type Used
NodePort

![](./img/k8s-test-coding.png)

## Application Access URL
http://<NodeIP>:<NodePort>

Example:  
http://3.12.146.175:30007/

## Browser Output Screenshot

![Application Output]
![](./img/k8s-test-successfully.png)


## Verification
The application was successfully deployed using a Kubernetes Deployment with 2 replicas.  
All pods are in **Running** state.  
The application is exposed using a **NodePort Service** and is accessible from the browser using the above URL.
