# Task 2: FastAPI + MySQL on Kubernetes (ConfigMap, Secret, PV/PVC & Ingress)



## Folder Structure

```
task-2/
├── webapp/                  # FastAPI app + Dockerfile (provided)
├── mysql/                   # MySQL image + Dockerfile (provided)
├── mysql-secret.yaml        # Secret with MySQL credentials
├── webapp-configmap.yaml    # ConfigMap with app settings
├── mysql-pv-pvc.yaml        # PV + PVC 
├── mysql-deploy.yaml        # MySQL Deployment
├── mysql-service.yaml       # MySQL Service
├── webapp-deploy.yaml       # App Deployment
├── webapp-service.yaml      # App Service
├── webapp-ingress.yaml      # Ingress
└── imgs/                    # Screenshots
```


## Screenshots

### Ingress created and Pods running
![Pods running](imgs/1.png)

### Port-forward to the Ingress Controller
![Port forward](imgs/2.png)

### App home page 
![App home](imgs/3.png)


![Guestbook](imgs/4.png)

### All resources in `webapp-stack`
![kubectl get all](imgs/5.png)

