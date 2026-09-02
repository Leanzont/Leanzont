# Leandro Zenteno — Junior Cloud/DevOps Engineer

**Building production-grade AWS infrastructure from Cochabamba, Bolivia 🇧🇴 | Open to remote worldwide**

I don't watch courses and take notes. I provision VPCs, harden IAM policies, break things in AWS Free Tier, and fix them with Terraform. Every project is containerized, documented, and pushed to GitHub.

---

## 🚀 What I'm Building Now

**[TechFlow Cloud Toolkit](https://github.com/Leanzont/techflow-cloud-toolkit)** — My main project. A complete AWS environment that I designed, deployed, secured, and automated from scratch.

- **6 Terraform modules**: VPC (2 AZs), ALB, EC2, RDS PostgreSQL, S3, IAM
- **Security hardening**: IMDSv2 enforcement, least-privilege IAM with `aws:SecureTransport`, S3 deny-by-default encryption policies, SG egress restricted to 443/53
- **NAT Gateway** with Elastic IP for private subnet outbound access
- **Containerized Flask API** with 3 endpoints (`/health`, `/data`, `/drift`) running on Docker
- **Python drift detector** (Boto3) that audits live AWS state against declared Terraform config
- **CI/CD pipelines**: GitHub Actions for Terraform (`fmt` → `validate` → `plan`) and Docker (build on PR, build + push on merge)
- **Remote state** in S3 with native locking (`use_lockfile = true`)

---

## 🛠️ What I've Built

| Project | What It Is | Stack |
|---------|-----------|-------|
| **[techflow-cloud-toolkit](https://github.com/Leanzont/techflow-cloud-toolkit)** | End-to-end AWS infrastructure with security hardening and drift detection | Terraform, AWS, Docker, Python/Boto3, GitHub Actions |
| **[terraform-aws-labs](https://github.com/Leanzont/terraform-aws-labs)** | 10 progressive labs from single EC2 to modular infrastructure with CI/CD | Terraform, AWS, GitHub Actions |
| **[python-projects-scripts](https://github.com/Leanzont/python-projects-scripts)** | AWS automation scripts and CLI tools | Python, Boto3, REST APIs, OOP |

---

## 📊 My Stack

**Cloud & IaC:** AWS (VPC, EC2, RDS, S3, ALB, IAM, NAT Gateway, CloudWatch) · Terraform · Infrastructure as Code · Remote State Management 

**Security:** IAM hardening · Least privilege · IMDSv2 · S3 encryption policies · Security group referencing  

**Automation:** Python · Boto3 · Bash · GitHub Actions · CI/CD pipelines  

**Containers:** Docker · Docker Compose · Multi-stage builds  

**OS:** Linux (Arch Linux daily driver)

---

## 🎯 Currently

- **AWS Solutions Architect Associate (SAA-C03)** — in progress, target December 2026
- **Studying with:** Adrian Cantrill's SAA course + AWS Free Tier labs
- **Learning method:** Write code alone first → explain in my own words → receive correction → refactor

---

## 📫 Contact

- **Email:** leandrozentenosoliz16@gmail.com
- **LinkedIn:** [linkedin.com/in/leanzont](https://linkedin.com/in/leanzont)
- **Location:** Cochabamba, Bolivia (UTC-4) | **Open to remote worldwide**

---

> *"I don't have a degree. I have results."*
