                                                     ⭐ Project Title 
Kubernetes Mini Project: Deploying a Dockerized Web App using Minikube
                                                   
                                                    ⭐Project Description⭐
Deployed a Dockerized static web application on Kubernetes using Minikube.
Created Kubernetes Deployment and Service (NodePort) to manage application lifecycle, scaling, and accessibility.
Tested Kubernetes self-healing by simulating pod failure and verified automatic pod recreation.

                                                    🛠 Tools & Technologies
.Kubernetes (Minikube)
.Docker
.kubectl
.Nginx
.Linux

                                                   🔄 Project Flow
Docker Image → Kubernetes Deployment → Pod → Service (NodePort) → Browser 

What IMAGES to Add (VERY IMPORTANT)
 Image 1 – Pods Running
Command:
⭐ kubectl get pods
<img width="1222" height="296" alt="image" src="https://github.com/user-attachments/assets/e68a8a8b-3044-45c6-a854-772f538cd846" />

Kubernetes pods running successfully

Image 2 – Service Details
Command:
⭐ kubectl get svc
<img width="876" height="114" alt="image" src="https://github.com/user-attachments/assets/f113c103-abfa-47dc-b255-0b9ff803b43f" />
Show NodePort service with port 30007
Exposing application using NodePort service

Image 3 – Application in Browser
Browser open showing:
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/5b1ea74b-81a3-4f0a-8e5a-fb79306d641c" />

Hello from Kubernetes 🚀
Application accessed via Kubernetes Service

Image 4 – Scaling Demo
Command:
⭐ kubectl scale deployment web-deployment --replicas=7

⭐ kubectl get pods

<img width="1230" height="319" alt="image" src="https://github.com/user-attachments/assets/3347c6cd-0f26-4863-ac7d-2bf656603fd1" />
Scaling application pods using Kubernetes


🚀 Steps
1. Build Docker image
2. Create Kubernetes Deployment
3. Expose app using NodePort Service
4. Test scaling & self-healing

🚀 Outcome
- Successfully deployed application
- Verified Kubernetes auto-healing and scaling
