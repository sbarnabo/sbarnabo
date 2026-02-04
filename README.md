<div align="center">
  <h1>Hey there, I'm sbarnabo 👋</h1>
  <h3>DevOps Engineer | Security Practitioner | Self-Hosting Enthusiast</h3>
  <p>I build secure, automated, and reproducible infrastructure from the ground up.</p>
</div>

---

## 🔭 I'm Currently Building: Project Bastion

I am the architect and sole developer of **Project Bastion**, a fully sovereign, self-hosted development ecosystem built on a Raspberry Pi cluster. The mission is to create an "Infrastructure as Code" factory that is independent of public cloud services for its core operations.

This factory's primary product is a **Windows 11 ARM Digital Forensics Lab**, a golden image automatically built and configured for security analysis.

### The Factory: `bastion-iac`
The infrastructure itself is defined as code using Ansible, deploying a complete suite of services:

| Component | Technology | Purpose |
| :--- | :--- | :--- |
| **Source Control** | Gitea | Private, self-hosted Git service |
| **Artifact Storage** | MinIO | S3-compatible repository for build assets |
| **CI/CD** | Drone CI | Automated build and test orchestration |
| **Identity Management**| Authentik | Centralized SSO / IAM for all services |
| **Threat Intelligence**| OpenCTI | Structured database for CTI analysis |
| **Network Services** | Pi-hole, Nginx Proxy Manager| Local DNS resolution and secure traffic routing|
| **Management** | Portainer | Web UI for Docker container management |

### The Product: `Win11-arm-forensics-lab`
A fully automated Packer and Ansible pipeline that produces a secure, analysis-ready Windows 11 ARM VM with a comprehensive toolkit, including:
- **Analysis Platforms:** Autopsy, Volatility 3
- **Cloud & Mobile Forensics:** AWS/Azure/M365 tooling, iLEAPP/ALEAPP
- **Triage & Collection:** KAPE, Magnet RAM Capture
- **Security Posture:** Hardened with Sysmon and a disabled AV for forensic soundness.

---

## 💡 My Core Principles

My work is guided by a few key philosophies:

*   **Infrastructure as Code (IaC) First:** Every component, from a virtual machine to the physical server it's built on, should be defined as code. I use **Packer** for image creation and **Ansible** for configuration management to ensure 100% reproducibility.
*   **Digital Sovereignty:** I believe in owning and controlling the entire development pipeline. By self-hosting services like **Gitea**, **MinIO**, and **Drone CI**, I eliminate reliance on external providers, enhancing security and resilience.
*   **Security by Design:** Security isn't an afterthought. I integrate tools like **Ansible Vault** for secrets management, `pre-commit` hooks for code quality, and network hardening (UFW, Fail2ban) directly into the development process.
*   **Pragmatic Automation:** I choose the right tool for the job. For Project Bastion, I selected **Docker Compose** for its simplicity and resource efficiency on ARM hardware, intentionally deferring the operational complexity of Kubernetes until it is truly needed.

---

## 💻 My Toolbox

### IaC & Automation
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-7B42BC?style=for-the-badge&logo=packer&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Shell Script](https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white)

### Containerization & CI/CD
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Drone CI](https://img.shields.io/badge/Drone_CI-212121?style=for-the-badge&logo=drone&logoColor=white)
![Gitea](https://img.shields.io/badge/Gitea-34495E?style=for-the-badge&logo=gitea&logoColor=white)

### Platforms & Services
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C92A42?style=for-the-badge&logo=minio&logoColor=white)

---

<div align="center">

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=radical)](https://github.com/anuraghazra/github-readme-stats)

</div>
