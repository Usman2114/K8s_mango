# Kubernetes MongoDB + Mongo Express Deployment

This repository contains Kubernetes YAML configuration files to deploy MongoDB and Mongo Express using persistent storage.

It includes:
- MongoDB deployment
- Mongo Express deployment
- Kubernetes Secrets
- Persistent Volumes (PV)
- Persistent Volume Claims (PVC)

---

## 🚀 Features
- Secure MongoDB deployment using Kubernetes Secrets
- Persistent storage using PV and PVC
- Easy Mongo Express web-based UI access
- Production-style Kubernetes architecture

---

## 📂 Files in this Repository
| File Name              | Description                            |
|------------------------|----------------------------------------|
| mongo-deployment.yaml  | MongoDB Kubernetes deployment           |
| mongo-express.yaml     | Mongo Express Kubernetes deployment      |
| mongodb-secret.yaml    | Stores MongoDB credentials              |
| pv.yaml                | Persistent Volume configuration          |
| pvc.yaml               | Persistent Volume Claim configuration    |

---

## 🔐 Default Credentials (For Development Only)

⚠️ These are for learning/demo only.

- Username: **admin**
- Password: **pass**

---

## 🛠 How to Deploy

Run:

kubectl apply -f pv.yaml  
kubectl apply -f pvc.yaml  
kubectl apply -f mongodb-secret.yaml  
kubectl apply -f mongo-deployment.yaml  
kubectl apply -f mongo-express.yaml  

---

## 👤 Author
Usman Fazal  
