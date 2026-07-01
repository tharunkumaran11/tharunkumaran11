<h1 align="center">Hi 👋, I'm Tharun Kumaran M</h1>
<h3 align="center">AWS Cloud Engineer (Fresher) | DevOps | Kubernetes | GitOps | Serverless | IaC</h3>

<p align="center">
  <a href="https://linkedin.com/in/tharunkumaran11"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:tharunkumaranm@outlook.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <img src="https://komarev.com/ghpvc/?username=tharunkumaran11&style=for-the-badge&color=blue" alt="profile views">
</p>

<p align="center">
  <em>I build production-style cloud infrastructure — not tutorials. Below are 8 hands-on projects spanning Kubernetes, GitOps, IaC, serverless, and FinOps.</em>
</p>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:203A43,100:2C5364&height=90&section=header&text=Tech%20Stack&fontSize=30&fontColor=ffffff&animation=twinkling&fontAlignY=60" width="100%"/>
</p>

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![OCI](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![GitHubActions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![ArgoCD](https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:203A43,100:2C5364&height=90&section=header&text=Project%20Portfolio&fontSize=30&fontColor=ffffff&animation=twinkling&fontAlignY=60" width="100%"/>
</p>

### 📌 8 Projects

| # | Project | Focus Area | Key Tech |
|---|---------|-----------|----------|
| 1 | [CommerceOps Platform](https://github.com/tharunkumaran11/commerceops-platform) | GitOps / Cloud-Native | Argo CD, Helm, Terraform, Prometheus |
| 2 | [EKS 2048 on Fargate](https://github.com/tharunkumaran11/eks-2048-fargate-project) | Kubernetes / Serverless Compute | EKS, Fargate, IRSA, ALB Ingress |
| 3 | [AWS FinOps Platform](https://github.com/tharunkumaran11/aws-cost-monitoring-platform) | Cost Optimization | Lambda, EventBridge, Cost Explorer |
| 4 | [AWS DevOps Monitoring](https://github.com/tharunkumaran11/aws-devops-monitoring-project) | Observability / CI-CD | Jenkins, Prometheus, Grafana, SNS |
| 5 | [Terraform AWS Infrastructure](https://github.com/tharunkumaran11/terraform-aws-infrastructure) | Infrastructure as Code | Terraform, Remote State, DynamoDB |
| 6 | [Terraform + GitHub Actions](https://github.com/tharunkumaran11/aws-terraform-github-actions) | CI/CD Automation | Terraform, GitHub Actions |
| 7 | [AWS E-Commerce Architecture](https://github.com/tharunkumaran11/aws-ecommerce-architecture) | Cloud Networking | VPC, ALB, RDS, Security Groups |
| 8 | [Dockerized E-Commerce App](https://github.com/tharunkumaran11/dockerized-ecommerce-app) | Containerization | Docker, Docker Compose |

---

### 🔹 1. CommerceOps Platform — Cloud-Native DevOps Pipeline

![Argo CD](https://img.shields.io/badge/Argo_CD-GitOps-EF7B4D?style=flat-square&logo=argo) ![Helm](https://img.shields.io/badge/Helm-Packaging-0F1689?style=flat-square&logo=helm) ![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat-square&logo=terraform)

A Go application wrapped in a complete production-style pipeline: **CI → containerization → GitOps deployment → Kubernetes orchestration → monitoring.**
- Zero-touch deployments via Argo CD syncing directly from Git
- Versioned, rollback-ready releases via Helm
- Custom Prometheus metrics instrumented in-app, visualized in Grafana

🔗 [View Repository](https://github.com/tharunkumaran11/commerceops-platform)

---

### 🔹 2. 2048 Game Deployment — Amazon EKS with Fargate & ALB Ingress

![EKS](https://img.shields.io/badge/EKS-Kubernetes-326CE5?style=flat-square&logo=kubernetes) ![Fargate](https://img.shields.io/badge/Fargate-Serverless-FF9900?style=flat-square&logo=amazonaws) ![IRSA](https://img.shields.io/badge/IRSA-IAM-232F3E?style=flat-square&logo=amazonaws)

Fully serverless Kubernetes deployment with **zero EC2 nodes to manage.**
- Pod-level least-privilege AWS access via IRSA
- AWS Load Balancer Controller + Ingress for public access
- 6-subnet VPC across 3 AZs for high availability

🔗 [View Repository](https://github.com/tharunkumaran11/eks-2048-fargate-project)

---

<details>
<summary><strong style="font-size:1.25em">🔹 3. AWS FinOps Cost Optimization & Monitoring Platform (click to expand)</strong></summary>
<br>

![Lambda](https://img.shields.io/badge/Lambda-Serverless-FF9900?style=flat-square&logo=awslambda) ![Python](https://img.shields.io/badge/Python-Boto3-3776AB?style=flat-square&logo=python) ![SNS](https://img.shields.io/badge/SNS-Alerts-FF4F8B?style=flat-square&logo=amazonaws)

A serverless cost-governance tool catching wasted AWS spend automatically — most freshers skip this entirely.
- Detects unattached EBS volumes, unassociated Elastic IPs, stale snapshots
- Daily automated scans via EventBridge Scheduler
- Runs at **under $0.05/month**

🔗 [View Repository](https://github.com/tharunkumaran11/aws-cost-monitoring-platform)


<details>
<summary><strong style="font-size:1.25em">🔹 4. AWS DevOps Monitoring Project — Multi-Server Observability (click to expand)</strong></summary>
<br>

![Jenkins](https://img.shields.io/badge/Jenkins-CI-D24939?style=flat-square&logo=jenkins) ![Prometheus](https://img.shields.io/badge/Prometheus-Metrics-E6522C?style=flat-square&logo=prometheus) ![Grafana](https://img.shields.io/badge/Grafana-Dashboards-F46800?style=flat-square&logo=grafana)

Production-style multi-server AWS monitoring environment with OpenVPN-secured access.
- Jenkins auto-routes files to S3 (docs) or GitHub (code)
- Prometheus + Grafana dashboards for live infrastructure monitoring
- CloudWatch alarms, SNS email alerts, SQS queue tracking

🔗 [View Repository](https://github.com/tharunkumaran11/aws-devops-monitoring-project)
</details>

<details>
<summary><strong style="font-size:1.25em">🔹 5. Terraform AWS Infrastructure — IaC with Remote State (click to expand)</strong></summary>
<br>

![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat-square&logo=terraform) ![DynamoDB](https://img.shields.io/badge/DynamoDB-State_Locking-4053D6?style=flat-square&logo=amazondynamodb)

Infrastructure as Code project provisioning AWS resources with proper team-ready state management.
- EC2, VPC, Subnets, Security Groups provisioned via Terraform
- Remote state managed in S3 with DynamoDB locking
- Version-controlled, repeatable deployments

🔗 [View Repository](https://github.com/tharunkumaran11/terraform-aws-infrastructure)
</details>

<details>
<summary><strong style="font-size:1.25em">🔹 6. Terraform + GitHub Actions — Automated Infrastructure Deployment (click to expand)</strong></summary>
<br>

![Terraform](https://img.shields.io/badge/Terraform-IaC-7B42BC?style=flat-square&logo=terraform) ![GitHubActions](https://img.shields.io/badge/GitHub_Actions-CI/CD-2088FF?style=flat-square&logo=githubactions)

CI/CD-driven infrastructure automation — push to deploy.
- GitHub Actions triggers Terraform plan/apply on every push
- Secure AWS authentication via GitHub Secrets
- EC2 provisioning with automated user-data deployment

🔗 [View Repository](https://github.com/tharunkumaran11/aws-terraform-github-actions)
</details>

<details>
<summary><strong style="font-size:1.25em">🔹 7. AWS E-Commerce Architecture — Multi-Tier Cloud Networking (click to expand)</strong></summary>
<br>

![VPC](https://img.shields.io/badge/VPC-Networking-232F3E?style=flat-square&logo=amazonaws) ![RDS](https://img.shields.io/badge/RDS-Database-527FFF?style=flat-square&logo=amazonrds)

Core AWS networking fundamentals applied to a real architecture.
- Public/private subnets, Application Load Balancer, RDS
- Security Groups for layered access control
- Foundation-level AWS infrastructure design

🔗 [View Repository](https://github.com/tharunkumaran11/aws-ecommerce-architecture)
</details>

<details>
<summary><strong style="font-size:1.25em">🔹 8. Dockerized E-Commerce Application — Containerized Multi-Service App (click to expand)</strong></summary>
<br>

![Docker](https://img.shields.io/badge/Docker-Containers-2496ED?style=flat-square&logo=docker)

Multi-service e-commerce app fully containerized for portability.
- Custom Docker images and container lifecycle management
- Docker networks and volumes for service communication and persistence

🔗 [View Repository](https://github.com/tharunkumaran11/dockerized-ecommerce-app)
</details>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:203A43,100:2C5364&height=90&section=header&text=Career%20Highlights&fontSize=30&fontColor=ffffff&animation=twinkling&fontAlignY=60" width="100%"/>
</p>

> 🧩 Designed and shipped a full **GitOps delivery pipeline** — GitHub Actions → Docker → Argo CD → Kubernetes — with **zero manual deployment steps**.
>
> ☁️ Deployed a fully **serverless Kubernetes workload** on Amazon EKS with Fargate, IRSA, and ALB Ingress across a 3-AZ, 6-subnet VPC.
>
> 💰 Built a self-funded **AWS FinOps tool** running automated cost-optimization scans for **under $0.05/month**.
>
> 📦 Published **8+ public cloud & DevOps projects** demonstrating AWS, Kubernetes, Terraform, GitHub Actions, Docker, and serverless architectures.
>
> 🔄 Fast learner, comfortable working independently or collaboratively in fast-paced, Agile environments.

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:203A43,100:2C5364&height=90&section=header&text=Skill%20Matrix&fontSize=30&fontColor=ffffff&animation=twinkling&fontAlignY=60" width="100%"/>
</p>

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,kubernetes,docker,terraform,githubactions,jenkins,prometheus,grafana,python,go,linux,bash,git,vscode&theme=dark&perline=7" alt="skill icons"/>
</p>

<table align="center">
<tr>
<td valign="top" width="50%">

**☁️ Cloud & AWS**
`EC2` `S3` `VPC` `IAM` `RDS` `Lambda` `EKS` `Fargate` `ALB`
`Auto Scaling` `CloudWatch` `SNS` `SQS` `EventBridge`
`Cost Explorer` `CloudFront` `Route 53`

**⚙️ DevOps & CI/CD**
`GitHub Actions` `Jenkins` `Docker` `Git` `Argo CD (GitOps)`
`Agile/Scrum` `CI/CD Pipeline Design` `Deployment Automation`

</td>
<td valign="top" width="50%">

**🚢 Kubernetes & Containers**
`Kubernetes` `Helm` `EKS` `Fargate` `Docker Compose`
`IRSA` `Ingress (ALB Controller)`

**📐 Infrastructure as Code**
`Terraform (AWS & K8s Providers)` `Remote State (S3 + DynamoDB)`

**📡 Monitoring & Networking**
`Prometheus` `Grafana` `CloudWatch Logs` `SRE Fundamentals`
`TCP/IP` `DNS` `Security Groups` `Load Balancing`

</td>
</tr>
</table>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:203A43,100:2C5364&height=90&section=header&text=About%20Me&fontSize=30&fontColor=ffffff&animation=twinkling&fontAlignY=60" width="100%"/>
</p>

<table align="center">
<tr><td>🎓</td><td><b>Education</b></td><td>B.E. Electronics and Communication Engineering — Dhanalakshmi College of Engineering, Chennai (2021 – 2025) · CGPA 7.66</td></tr>
<tr><td>📍</td><td><b>Location</b></td><td>Chennai, India</td></tr>
<tr><td>💼</td><td><b>Role Target</b></td><td>Cloud Engineer / DevOps Engineer / SRE</td></tr>
<tr><td>🌱</td><td><b>Currently</b></td><td>Building production-style AWS + Kubernetes projects and sharpening GitOps workflows</td></tr>
<tr><td>🤝</td><td><b>Open To</b></td><td>Relocation & remote opportunities</td></tr>
</table>

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:203A43,100:2C5364&height=90&section=header&text=Certifications&fontSize=30&fontColor=ffffff&animation=twinkling&fontAlignY=60" width="100%"/>
</p>

✅ Oracle Cloud Infrastructure (OCI) Foundations Certified (2025) &nbsp;|&nbsp; ✅ AWS Training &nbsp;|&nbsp; ✅ Linux Training &nbsp;|&nbsp; ✅ DevOps Training &nbsp;|&nbsp; ✅ CCNA Training

---

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:203A43,100:2C5364&height=90&section=header&text=Open%20to%20Opportunities&fontSize=30&fontColor=ffffff&animation=twinkling&fontAlignY=60" width="100%"/>
</p>

I'm actively looking for **Cloud Engineer / DevOps Engineer / Site Reliability Engineer** roles. If your team is hiring freshers, I'd love to connect.

<p align="center">
  <a href="https://linkedin.com/in/tharunkumaran11"><img src="https://img.shields.io/badge/Connect_on-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:tharunkumaranm@outlook.com"><img src="https://img.shields.io/badge/Email-Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>
