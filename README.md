# 🚀 Deploying a Dockerized Web App on AWS Elastic Beanstalk

This project demonstrates how to containerize a static web application with **Docker** and deploy it to **AWS Elastic Beanstalk** (PaaS). The goal is to showcase skills in containerization, cloud deployment, and environment management.

---

## 📂 Project Structure
my-eb-docker-app/
├── Dockerfile # Defines the container build instructions
├── index.html # Static webpage served by Nginx
├── docs/
  └── Deploy an App with Docker.docx # Detailed project notes + screenshots

---

## 🛠️ Tools & Technologies
- **Docker** → for building container images  
- **Nginx** → lightweight web server for static content  
- **AWS Elastic Beanstalk** → platform-as-a-service (PaaS) for app deployment  
- **AWS S3** → storage for application versions  
- **AWS IAM** → permissions and access control  

---

## ⚡ How It Works
1. Write a `Dockerfile` using `nginx:latest` as the base image.  
2. Copy `index.html` into Nginx’s web root directory.  
3. Build and run the container locally with Docker.  
4. Package the app and deploy to AWS Elastic Beanstalk.  
5. Access the live app via the EB environment URL.  

---

## 🔍 Key Learnings
- Difference between **container images** (blueprint) and **containers** (running instances).  
- How Elastic Beanstalk manages resources like EC2 and S3 automatically.  
- IAM permissions needed to delete S3 buckets linked to EB.  
- Importance of updating application versions for redeployment.  

---

## 📖 Extended Notes
See [`/docs/Deploy an App with Docker.docx`](https://github.com/feaq-00/eb-docker-app/blob/0465c6b7fdd460e7b656093eb2b902dd3bc68623/eb-docker-app/Deploy%20an%20App%20with%20Docker.docx) for a full walkthrough with detailed explanations.  

---

## 🏷️ Topics
`docker` `aws` `elastic-beanstalk` `nginx` `cloud` `devops`  
