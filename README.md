<h1 align="center">Hi, I'm Harun Kamande 👋</h1>
<h3 align="center">Cloud & DevOps Engineer | AWS Certified Solutions Architect | Information Security</h3>

<p align="center">
  I build and secure AWS infrastructure end-to-end from Terraform-provisioned networks to CI/CD pipelines that catch vulnerabilities before they ship. Currently finishing a BSc in Information Security & Forensics while shipping real infra and low-level systems projects.
</p>

---

### About Me

- **Currently:** Final-year Information Security & Forensics student at KCA University, Nairobi : building a DevSecOps CI/CD capstone with Vault-based secrets management and a C++/Python runtime detection agent
- **Cloud background:** DevOps Engineer Intern at Cloud Intelligence : cut MTTR by 25% through log analysis (Grafana, Uptime Kuma), automated Docker deployments, and hardened AWS environments (VPC, EC2, S3, IAM least-privilege)
- **Security-first:** Completed cybersecurity and IAM simulations with Deloitte and TCS (via Forage) : incident triage, anomaly detection, and IAM strategy aligned to business risk
- **Builds from first principles:** wrote a packet-inspection intrusion detection engine in C, and I'm currently building an HTTP server from scratch to deeply understand sockets, file descriptors, and the Linux syscall layer
- **Documents everything:** every project ships with a write-up : see my [blog](https://blogs-seven-umber-32.vercel.app/) for build logs on IDS internals, HTTP servers, and CI/CD pipeline design
- **Reach me:** [harunkamande780@gmail.com](mailto:harunkamande780@gmail.com) · [LinkedIn](https://linkedin.com/in/harun-kamande)

---

### Featured Projects

**[Signature-Based Intrusion Detection Engine](https://github.com/jaeger231)** : `C` · `GitLab CI` · `Valgrind` · `cppcheck`
Packet inspection engine built from first principles. Typed structs modeling network traffic per TCP/IP spec, pointer-based signature matching, and a hardened 2-target Makefile (`-fstack-protector-strong`, `-D_FORTIFY_SOURCE=2`). Backed by a 3-stage GitLab CI pipeline (static analysis → build → memory sanitization) that shifts security left.

**Secure Containerised Deployment with Monitoring** : `AWS` · `Terraform`
Complete AWS network (VPC, subnets, IGW, route tables, security groups) provisioned entirely via Terraform. Zero manual console work, fully reproducible.

**MarkdownNotes API — Serverless Backend** : `AWS Lambda` · `API Gateway` · `DynamoDB` · `Terraform`
Event-driven serverless API with IAM least-privilege access, fully provisioned as code.

**Hybrid Cloud Storage Solution** — `AWS Storage Gateway` · `S3` · `Terraform`
On-prem to S3 migration via Storage Gateway with multi-region replication and encryption in transit and at rest.

---

###  Tech Stack

**Cloud & Infra**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)

**Security & CI/CD**
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Vault](https://img.shields.io/badge/HashiCorp_Vault-000000?style=flat&logo=vault&logoColor=white)

**Languages**
![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnu-bash&logoColor=white)

**Observability**
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)

---

### 📜 Certifications

- AWS Certified Solutions Architect – Associate (SAA-C03)
- AWS Certified Cloud Practitioner (CLF-C02)
- API Security Fundamentals
- GitLab CI Fundamentals

---

<p align="center"><i>Building things from the syscall up, and writing about it along the way.</i></p>
