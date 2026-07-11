# 📘 Chapter 10: Cloud and Virtualization Security

📅 **Date Completed:** 2026-01-25  
📚 **Topic:** Cloud models, virtualization, containerization, shared responsibility, and cloud-native threats

---

## 🔑 Key Concept

- **Cloud Models:** SaaS (software), PaaS (platform), IaaS (infrastructure) — each shifts responsibility differently. Hybrid and multi-cloud add complexity.

- **Shared Responsibility:** The cloud provider secures the cloud (hardware, hypervisors); the customer secures what they put *in* the cloud (data, identities, configurations). Misconfigurations are the #1 cloud vulnerability.

- **Virtualization Risks:** VM escape (breaking out of a VM to the host) and resource reuse (data left behind after decommissioning) are unique threats.

- **Containerization:** Lightweight, portable environments (Docker, Kubernetes). Risks include insecure images, misconfigurations, and container breakout.

- **Infrastructure as Code (IaC):** Managing infrastructure through code (Terraform, CloudFormation) — great for consistency, but security scanning is essential.

---

## 🛠️ Tools/Techniques

- Cloud deployment models (SaaS, PaaS, IaaS, Hybrid, Multi-cloud)
- Virtualization (VM escape, resource reuse risks)
- Containerization and orchestration (Kubernetes, Docker)
- Serverless and microservices architectures
- Infrastructure as Code (IaC) — Terraform, CloudFormation
- Cloud responsibility matrix and shared security model
- Data sovereignty and geographic restrictions

---

## 🛡️ SOC Relevance

- Misconfigured S3 buckets, open ports, and overly permissive IAM are top cloud findings — monitor continuously.
- Cloud logs (CloudTrail, Flow Logs, O365 audit) are critical investigation sources.
- VM escape and container breakout are high-severity alerts — treat as critical.
- Shared responsibility means the SOC owns detection for customer-managed layers.
- Cloud-native logging is often the only visibility into cloud-based attacks.

---

## 📝 Summary

Cloud is where modern infrastructure lives, and security there demands a new mindset — ephemeral, API-driven, and fast. I learned that automation (IaC scanning, CSPM) is essential. For a SOC Analyst, cloud expertise is non-negotiable — cloud logs are now the norm, not the exception.
