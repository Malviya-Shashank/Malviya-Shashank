<div align="center">

<!-- HEADER BANNER -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=260&color=0:0d0d0d,40:0a1628,70:0d2137,100:112240&text=Shashank%20Malviya&fontSize=52&fontColor=58a6ff&animation=fadeIn&fontAlignY=38&desc=AWS%20DevOps%20Engineer%20%7C%20Cloud%20Infrastructure%20Architect&descAlignY=58&descSize=18&descColor=8b949e"/>

<br/>

<!-- TYPING ANIMATION -->
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=900&lines=☁+AWS+Cloud+Infrastructure+Engineer;☸+Kubernetes+Production+Operations;🏗+Infrastructure+as+Code+with+Terraform;🔁+CI%2FCD+%26+GitOps+Automation;🔐+DevSecOps+%26+Platform+Engineering;📊+Observability+%26+Monitoring+at+Scale" alt="Typing SVG" />

<br/>

<!-- BADGES ROW -->
<p>
  <img src="https://img.shields.io/badge/Experience-4%2B%20Years-58a6ff?style=for-the-badge&labelColor=0d1117&color=58a6ff"/>
  <img src="https://img.shields.io/badge/AWS-Certified-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=0d1117"/>
  <img src="https://img.shields.io/badge/Focus-DevSecOps-30c760?style=for-the-badge&labelColor=0d1117&color=30c760"/>
  <img src="https://komarev.com/ghpvc/?username=shashank-malviya&label=Profile+Views&color=58a6ff&style=for-the-badge&labelColor=0d1117"/>
</p>

</div>

---

<div align="center">

## 👨‍💻 About Me

</div>

```yaml
Name        : Shashank Malviya
Role        : DevOps / Cloud Infrastructure Engineer
Experience  : 4+ Years — Production-Grade Cloud Platforms
Location    : India 🇮🇳
Focus       : AWS · Kubernetes · Terraform · CI/CD · DevSecOps

Core Skills :
  Cloud     → AWS (EC2, EKS, ECR, ALB, CloudWatch, IAM, S3, Route53)
  Containers→ Docker · Kubernetes · Helm · ArgoCD
  IaC       → Terraform (Modules, Remote State, Workspaces)
  CI/CD     → GitHub Actions · Jenkins · GitOps
  Security  → DevSecOps · RBAC · IAM Policies · Secrets Management
  Observe   → Prometheus · Grafana · CloudWatch · ELK Stack

Philosophy  : "Automate Everything. Monitor Everything. Secure Everything."
```

---

## 🛠 Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,terraform,ansible,jenkins,githubactions,gitlab&theme=dark&perline=8"/>

<br/><br/>

<img src="https://skillicons.dev/icons?i=prometheus,grafana,python,bash,linux,git,github,nginx&theme=dark&perline=8"/>

</div>

---

## ☁ CI/CD Pipeline Architecture

```
╔══════════════════════════════════════════════════════════════════════════╗
║                     DEVOPS CI/CD PIPELINE                               ║
╚══════════════════════════════════════════════════════════════════════════╝

  👨‍💻 Developer                   🔀 Source Control
  ─────────────                   ──────────────────
  Code Changes          ────►     GitHub Repository
                                        │
                              ┌─────────┴─────────┐
                              ▼                   ▼
                        GitHub Actions         Jenkins
                              │                   │
                              └─────────┬─────────┘
                                        │
                              ┌─────────▼─────────┐
                              │   CI PIPELINE      │
                              │  ✔ Lint & Test     │
                              │  ✔ Security Scan   │
                              │  ✔ Build Docker    │
                              │  ✔ Push to ECR     │
                              └─────────┬──────────┘
                                        │
                              ┌─────────▼──────────┐
                              │   CD PIPELINE       │
                              │  Helm Chart Deploy  │
                              │  ArgoCD GitOps      │
                              └─────────┬───────────┘
                                        │
                          ┌─────────────▼─────────────┐
                          │    AWS EKS CLUSTER         │
                          │  ┌─────────────────────┐   │
                          │  │  NGINX Ingress       │   │
                          │  └──────────┬──────────┘   │
                          │  ┌──────────▼──────────┐   │
                          │  │  ┌──────┐ ┌──────┐  │   │
                          │  │  │ API  │ │ Web  │  │   │
                          │  │  │ Pods │ │ Pods │  │   │
                          │  │  └──────┘ └──────┘  │   │
                          │  └─────────────────────┘   │
                          └─────────────┬───────────────┘
                                        │
                          ┌─────────────▼─────────────┐
                          │   OBSERVABILITY STACK      │
                          │  Prometheus · Grafana      │
                          │  CloudWatch · Alertmanager │
                          └───────────────────────────┘
```

---

## 🏗 Terraform Infrastructure Architecture

```
╔══════════════════════════════════════════════════════════╗
║              TERRAFORM AWS INFRASTRUCTURE                ║
╚══════════════════════════════════════════════════════════╝

  terraform/
  ├── 📁 modules/
  │   ├── 🔹 vpc/          → Subnets, Route Tables, NAT Gateway
  │   ├── 🔹 eks/          → Managed Node Groups, OIDC, Addons
  │   ├── 🔹 iam/          → Roles, Policies, Service Accounts
  │   ├── 🔹 alb/          → Application Load Balancer, Target Groups
  │   └── 🔹 autoscaling/  → Launch Templates, ASG, Scaling Policies
  │
  ├── 📁 environments/
  │   ├── dev/
  │   ├── staging/
  │   └── prod/
  │
  └── 📁 remote-state/
      ├── S3 Bucket         → Encrypted State Storage
      └── DynamoDB Table    → State Locking & Consistency
```

---

## 🚀 Featured Projects

<div align="center">

| Project | Stack | Description |
|--------|-------|-------------|
| 🗓 **90 Days of DevOps** | Linux · Docker · K8s · Terraform · AWS | Hands-on DevOps learning journey from zero to production |
| 🏗 **Terraform AWS Infrastructure** | Terraform · EKS · VPC · IAM · ALB | Production-grade modular IaC with remote state & locking |
| ☸ **GitOps Kubernetes Deployment** | Helm · ArgoCD · GitHub · EKS | Full GitOps workflow with automated drift detection |

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=shashank-malviya&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e&border_radius=10"/>
&nbsp;&nbsp;
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shashank-malviya&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=8b949e&border_radius=10"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=shashank-malviya&theme=github-dark-blue&hide_border=true&background=0d1117&ring=58a6ff&fire=ff9900&currStreakLabel=58a6ff&border_radius=10"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=shashank-malviya&theme=github-compact&bg_color=0d1117&color=58a6ff&line=58a6ff&point=ff9900&hide_border=true&area=true&area_color=58a6ff"/>

</div>

---

## 🏆 GitHub Achievements

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=shashank-malviya&theme=algolia&no-frame=true&no-bg=true&margin-w=6&column=7"/>

</div>

---

## 📜 Certifications

<div align="center">

<img src="https://img.shields.io/badge/AWS-Solutions%20Architect-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=0d1117"/>
&nbsp;
<img src="https://img.shields.io/badge/Amazon%20Q-Developer%20Fundamentals-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=0d1117"/>

</div>

---

## 📚 Currently Learning

<div align="center">

```
┌─────────────────────────────────────────────────────┐
│                 LEARNING ROADMAP                    │
├─────────────────────────────────────────────────────┤
│  🔧 Platform Engineering    [████████░░]  80%       │
│  🌐 Advanced K8s Networking [██████░░░░]  60%       │
│  📊 Observability Eng.      [███████░░░]  70%       │
│  ☁  Multi-Cloud DevOps      [█████░░░░░]  50%       │
└─────────────────────────────────────────────────────┘
```

</div>

---

## 🌐 Connect With Me

<div align="center">

<a href="https://www.linkedin.com/in/shashank-malviya-devops/">
  <img src="https://img.shields.io/badge/LinkedIn-Shashank%20Malviya-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0d1117"/>
</a>
&nbsp;&nbsp;
<a href="mailto:malviyashashank24@gmail.com">
  <img src="https://img.shields.io/badge/Gmail-malviyashashank24-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0d1117"/>
</a>

<br/><br/>

<!-- CONTRIBUTION SNAKE -->
<img src="https://github.com/platane/snk/raw/output/github-contribution-grid-snake-dark.svg"/>

</div>

---

<div align="center">

> **"Automate Everything · Monitor Everything · Secure Everything"**
>
> *Building scalable, resilient, production-grade cloud platforms — one commit at a time.*

<br/>

⭐ **[Shashank Malviya](https://github.com/shashank-malviya)** — DevOps Engineer

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:112240,50:0d2137,100:0a1628&height=120&section=footer"/>

</div>
