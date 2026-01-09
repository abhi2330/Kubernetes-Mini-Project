# ⭐ Kubernetes Mini Project  
## Deploying a Dockerized Web Application using Minikube 🚀

---

## 📌 Project Description
This project demonstrates the deployment of a **Dockerized static web application** on a **Kubernetes cluster using Minikube**.  
It covers core Kubernetes concepts such as **Deployments, Services (NodePort), scaling, and self-healing**, showcasing how Kubernetes manages application lifecycle and availability in a real-world scenario.

---

## 🛠 Tools & Technologies
- **Kubernetes** (Minikube)
- **Docker**
- **kubectl**
- **Nginx**
- **Linux**

---

## 🔄 Project Flow
Docker Image → Kubernetes Deployment → Pod → Service (NodePort) → Browser
---

## 🧪 Key Features
- Containerized a static web application using Docker
- Deployed application using Kubernetes Deployment
- Exposed application externally using NodePort Service
- Verified Kubernetes **self-healing** by deleting pods
- Demonstrated **horizontal scaling** by increasing replicas

---

## 📸 Screenshots & Demonstration

### 🖼 Image 1 – Pods Running
**Command:**
```sh
kubectl get pods

```
<img width="876" height="114" alt="Service Details" src="https://github.com/user-attachments/assets/f113c103-abfa-47dc-b255-0b9ff803b43f" />

- ✔ NodePort service exposed on port 30007
- ✔ Application accessible externally

 🖼 Image 2 – Service Details
```
Command:

kubectl get svc
```
<img width="876" height="114" alt="Service Details" src="https://github.com/user-attachments/assets/f113c103-abfa-47dc-b255-0b9ff803b43f" />

- ✔ NodePort service exposed on port 30007
- ✔ Application accessible externally

  🖼 Image 3 – Application in Browser
<img width="1920" height="1080" alt="Application Output" src="https://github.com/user-attachments/assets/5b1ea74b-81a3-4f0a-8e5a-fb79306d641c" />

- ✔ Application successfully accessed via Kubernetes Service
- ✔ Output: Hello from Kubernetes 🚀

  🖼 Image 4 – Scaling Demo

```
Command:
kubectl scale deployment web-deployment --replicas=7
kubectl get pods
```

<img width="1230" height="319" alt="Scaling Demo" src="https://github.com/user-attachments/assets/3347c6cd-0f26-4863-ac7d-2bf656603fd1" />

- ✔ Application scaled horizontally using Kubernetes
- ✔ Multiple pods created automatically

🚀 Steps to Run
- Build Docker image
- Create Kubernetes Deployment
- Expose application using NodePort Service
- Test scaling and self-healing features

🎯 Outcome
- Successfully deployed a Dockerized application on Kubernetes
- Verified Kubernetes auto-healing by recreating failed pods
- Demonstrated scalability using replica scaling
- Gained hands-on experience with real Kubernetes workloads
