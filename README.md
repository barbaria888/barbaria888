<!-- 💫 Hardik Arora's GitHub Profile README -->

<h1 align="center">

<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=rect&color=0:4285F4,50:34A853,100:FBBC05&height=3&section=header"
    width="100%"
  />
</p>


<h1 align="center">


<img 
src="https://capsule-render.vercel.app/api?type=rounded&color=0:991B1B,34:EF4444,66:F59E0B,82:FACC15,92:7DD3FC,100:F8FAFC&height=220&section=header&text=Hardik%20Arora&fontSize=48&fontColor=ffffff&animation=fadeIn"
/>

</h1>


<h2 align="center">
  <img 
    src="https://readme-typing-svg.demolab.com?font=Google+Sans&weight=600&size=34&duration=3200&pause=1400&color=58A6FF&center=true&vCenter=true&width=900&lines=Cloud+Native+Engineer;Kubernetes+%7C+DevOps+%7C+AI+Infrastructure;Building+Systems+That+Scale"
    alt="Typing SVG"
  />
</h2>
<br>



<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=rect&color=0:4285F4,50:34A853,100:FBBC05&height=3&section=header"
    width="100%"
  />
</p>


## 💡 Overview

I build cloud-native systems engineered for scale, reliability, and security — with a strong focus on AI infrastructure and DevSecOps.

Working across Kubernetes, Terraform, CI/CD, cloud platforms,Agentic Systems.
I translate complex ideas into production-grade systems designed for real-world workloads.

Currently exploring the intersection of **security, AI systems, and distributed cloud  infrastructure**, where resilience and intelligence converge with **optimal resource utilisation**.

---

## 🧭 Focus Areas

- Cloud-native system architecture
- AI infrastructure engineering
- Secure software supply chains
- Observability, reliability, and runtime resilience
---

## 🚧 Currently Working On


<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=rect&color=0:4285F4,50:34A853,100:FBBC05&height=3&section=header"
    width="100%"
  />
</p>


# 🛡️ Supply Chain Guardian AI  
Autonomous AI-driven CVE remediation and runtime validation system for containerized workloads.

Designed as a production-oriented GitHub Marketplace Action that detects vulnerabilities, generates secure Dockerfile patches using AI, validates fixes in ephemeral Kubernetes environments, and automatically opens review-ready pull requests.

---

### ⚙️ Core Workflow

- Detects container CVEs using Trivy  
- Generates remediation patches using local or cloud LLMs  
- Performs Docker build smoke validation  
- Deploys patched workloads into ephemeral KinD clusters  
- Re-scans images to verify remediation success  
- Creates automated pull requests with audit evidence  

---

### 🤖 Multi-Provider AI Engine

- Local Ollama inference for zero-data-egress remediation  
- Gemini and OpenAI integration for accelerated patch generation  
- Model-driven Dockerfile transformation pipeline  
- Secure side-by-side patch generation (`Dockerfile.patched`)  

---

### 🧠 Security & Runtime Validation

- Instruction-level hallucination defense engine  
- Docker syntax whitelist enforcement  
- Runtime validation through KinD Kubernetes clusters  
- CrashLoopBackOff detection and deployment verification  
- RBAC-aware Kubernetes deployment model  
- Secure-by-default container hardening policies  

---

### ⚙️ Architecture

**Scanning:** Trivy + SBOM generation  
**AI Layer:** Ollama / Gemini / OpenAI  
**Validation:** KinD ephemeral Kubernetes clusters  
**Orchestration:** GitHub Actions automation pipeline  
**Compliance:** Audit logs + remediation evidence artifacts  

---

### 🛡️ Security Principles

- Zero-trust deployment validation  
- Human-reviewable AI remediation workflows  
- Runtime verification before merge approval  
- Immutable auditability for AI-generated patches  
- Automated secure software supply-chain enforcement  

---

### 📌 Focus Areas

- Autonomous CVE remediation systems  
- AI-assisted infrastructure hardening  
- Secure software supply chains  
- Kubernetes runtime validation  
- AI + DevSecOps convergence  
- Self-healing infrastructure pipelines  

---

🔗 **Repository:**  
👉 https://github.com/barbaria888/SupplyChain-Guardian-AI-Github_Action

<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=rect&color=0:4285F4,50:34A853,100:FBBC05&height=3&section=header"
    width="100%"
  />
</p>



# 🤖 KubeOps-AI — Agentic AI for Kubernetes Operations

Cloud-native autonomous system for Kubernetes troubleshooting using local AI, observability tools, and secure execution pipelines.

It analyzes cluster issues, reasons about root causes, and safely suggests remediations through a human-approved workflow.

---

🧠 Core Workflow

- Detects issues using K8sGPT  
- Reasons with local LLMs (Ollama + Gemma)  
- Retrieves historical incidents via ChromaDB  
- Generates safe kubectl remediation commands  
- Executes only after human approval via dashboard  



⚙️ Architecture

Frontend: React + Vite (Nginx-served dashboard)  
Backend: FastAPI orchestration layer (agent-based system)  
AI Layer: Ollama (local inference) , Gemma:2b
Memory: ChromaDB (incident recall + context)  
Tools: K8sGPT + kubectl execution engine  

🛡️ Safety Model
- Guardrails prevent destructive operations  
- Human-in-the-loop approval before execution  
- Fully local inference (no external AI APIs)  
- RBAC-based cluster access control  
- Auditability via stored incident history  

📌 Focus Areas
- Agentic AI for infrastructure operations  
- Local LLM deployment in Kubernetes  
- Memory-augmented troubleshooting systems  
- Cloud-native AI system design (GKE / K3s)  

🔗 Repository  
https://github.com/barbaria888/KubeOps-AI

<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=rect&color=0:4285F4,50:34A853,100:FBBC05&height=3&section=header"
    width="100%"
  />
</p>


# 🔐 EduConnect – DevSecOps Kubernetes Deployment
A production-grade **DevSecOps + GitOps pipeline** with strong security and quality enforcement.

---

### ⚙️ Pipeline Stages
- **🔍 Code Security — CodeQL (SAST):** Detects vulnerabilities (injection, secrets, auth flaws, etc.)  
- **🧹 Linting — Code Quality Gate:** Enforces clean, maintainable code  
- **🧪 Automated Tests:** Prevents regressions across services  
- **🐳 Docker Build:** Secure, reproducible container builds  
- **🛡️ Container Security — Trivy Scan:** Detects OS/package vulnerabilities & CVEs  
- **📦 Artifact Distribution:** Pushes verified images to Docker Hub  

---

### 🚀 DevSecOps Principles
- Security embedded into CI/CD pipelines  
- Shift-left vulnerability detection  
- Secure software supply chain (SCA + SBOM)  
- GitOps-based deployments with declarative control  
- End-to-end pipeline gating for production readiness  

🔗 **Repository:**  
👉 https://github.com/Dhruvsahu1/Educonnect-D/




<p align="center">
  <img 
    src="https://capsule-render.vercel.app/api?type=rect&color=0:4285F4,50:34A853,100:FBBC05&height=3&section=header"
    width="100%"
  />
</p>



### 📌 Current Evolution
- ☁️ Deploying AI workloads on cloud(GCP) and localised ai inference and model serving.
- ⚡ Exploring real world monitoring using prometheus,grafana,otel,Datadog, metrics,traces,logs alerting.
- 🔐 Strengthening runtime security layers, throughout the SDLC
-   Moving toward fully automated, scalable AI platforms  

## 🧰 Tech & Tool Arsenal

<p align="center">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/kubernetes/kubernetes-plain-wordmark.svg" height="90" alt="Kubernetes" /> &nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" height="60" alt="Google Cloud" /> &nbsp;
<img src="https://raw.githubusercontent.com/barbaria888/barbaria888/main/gke-icon.png.png" height="70" alt="Google Kubernetes Engine"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" height="70" alt="AWS" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="60" alt="Docker" /> &nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/githubactions/githubactions-original.svg" height="70" alt="GitHub Actions" />&nbsp;
<img src="https://cdn.simpleicons.org/ollama/00000" height="60" alt="Ollama" />

<img src="https://k3s.io/img/k3s-logo-light.svg" height="30" alt="K3s" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" height="60" alt="Oracle Cloud" /> &nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" height="60" alt="Terraform" /> &nbsp;
<img src="https://raw.githubusercontent.com/argoproj/argo-cd/master/docs/assets/argo.png" height="60" alt="Argo CD" /> &nbsp;
<img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/OpenShift-LogoType.svg" height="60" alt="OpenShift" /> &nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" height="60" alt="Bash" /> &nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="60" alt="Linux" /> &nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="60" alt="Git" /> &nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="60" alt="GitHub" />
</p>

---

## 🪪 Certifications & Learning  

### ☁️ Cloud, Security & AI Infrastructure
- 🏗️ **Google Cloud** – Professional Cloud Architect (PCA) & Professional Cloud DevOps Engineer Tracks, Architecting with GKE Specialization, Logging & Monitoring
- 🔐 **IBM** – Monitoring and Observability for Development & DevOps, CI/CD pipelines (OpenShift/GitHub Actions)
- 🛡️ **AI Security & Agents** – Model Armor: Securing AI Deployments (OWASP LLM Top 10), Model Context Protocol (MCP Tools), Google ADK Agents
- 🧱 **AWS** – Cloud Essentials & Practitioner Professional Prep  
- 🧿 **Oracle Cloud** – OCI Foundations Associate Certified  
- 🦋 **Platform & GitOps** – Introduction to GitOps using Argo CD (Akuity), Vulnerability Management for Platform Engineers

---

## ⚙️ GitHub Stats Wall  

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=barbaria888&show_icons=true&theme=radical&hide_border=true" height="165" /> &nbsp;
<img src="https://github-readme-streak-stats.herokuapp.com/?user=barbaria888&theme=radical&hide_border=true" height="165" />
</p>

<p align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=barbaria888&theme=react-dark&hide_border=true" width="95%" />
</p>

---

## 🌐 Connect & Collaborate

<p align="center">
<a href="mailto:arorahardik0811@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.linkedin.com/in/hardik0811arora/"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://www.youtube.com/@hardikarora999">
  <img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" />
</a>
<a href="https://hardik-arora.hashnode.dev/"><img src="https://img.shields.io/badge/Hashnode-2962FF?style=for-the-badge&logo=hashnode&logoColor=white" /></a>
<a href="https://medium.com/@arorahardik0811"><img src="https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white" /></a>

</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=barbaria888&label=WATCHING&color=000000&style=for-the-badge" />
</p>

<p align="center">
<img width="64" height="64" alt="Scorpion" src="https://github.com/user-attachments/assets/c6e5289d-7152-49ab-a563-6bfd04bf375a" />
</p>

<p align="center">
  <b style="font-size: 45px; letter-spacing: 5px;">
    OBSERVE IN SILENCE · BUILD IN DEPTH · STRIKE WITH PRECISION
  </b>
</p>

<p align="center">
  <i>Engineered beneath the surface. Proven where it matters.</i>
</p>

---
