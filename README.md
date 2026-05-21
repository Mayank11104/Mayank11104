<h1 align="center">Hi, I'm Mayank Chaudhari 👋</h1>

<p align="center">
  <b>Computer Science · 3rd Year · Cloud & DevOps focused</b><br/>
  I build real things on real infrastructure — not just tutorials.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mayankchaudhari2004"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:mayuchaudhari2004@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Mayank11104"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" /></a>
</p>

---

## ☁️ Cloud & Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-EC2-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-S3-569A31?style=flat-square&logo=amazons3&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-IAM-DD344C?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-VPC%20%7C%20NAT%20%7C%20IGW-FF9900?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
</p>

## ⚙️ DevOps & Tooling

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
</p>

## 🐧 Systems & Scripting

<p>
  <img src="https://img.shields.io/badge/Linux-Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
</p>

---

## 🏅 Certifications

<a href="https://www.credly.com/badges/ca8807ea-ed3f-4530-92ba-11bebbcb8717/linked_in_profile">
  <img src="https://github.com/Mayank11104/Mayank11104/blob/main/aws-certified-cloud-practitioner.png" width="100" alt="AWS Certified Cloud Practitioner" />
</a>

**AWS Certified Cloud Practitioner**

---

## 🔥 Featured Project

### [Alchemyst AI — Distributed Inference on AWS](https://github.com/Mayank11104/alchemyst-devops-assignment-mayank)

Deployed a distributed LLM inference stack across 3 AWS EC2 VMs using Terraform.

```
Internet → Nginx (public subnet) → iii engine + TypeScript caller (private)
                                 → Python inference worker on separate VM (private)
```

- **VPC** with public + private subnets, NAT Gateway, Internet Gateway
- **Security groups** — workers unreachable from internet, API exposed on port 3111 only
- **Terraform IaC** — `terraform apply` builds the entire stack from scratch
- **Workers communicate over WebSocket RPC** — no direct connection between workers
- Fixed 9 real deployment issues: host binding, KVM sandbox, PyTorch OOM, Windows SSH ACL

---

## 🌱 What I'm learning

- **Kubernetes** — pods, deployments, services, ingress, kubectl basics
- **Jenkins** — pipelines, declarative syntax, CI/CD integration with GitHub
- **NLP & LLM deployment** — prompt engineering, GGUF quantized models, inference serving

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Mayank11104&show_icons=true&theme=tokyonight&hide_border=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mayank11104&layout=compact&theme=tokyonight&hide_border=true" height="150" />
</p>

---

## 👋 About

3rd-year CS student focused on building and deploying real systems. I enjoy the full cycle — designing the network, writing the IaC, debugging why Nginx is returning 502, and shipping something that actually works.

Currently looking for DevOps / Cloud internship opportunities.

📫 **mayuchaudhari2004@gmail.com**
