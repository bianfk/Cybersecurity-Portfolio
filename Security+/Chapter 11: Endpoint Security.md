# 📘 Chapter 11: Endpoint Security

📅 **Date Completed:** 2026-02-08  
📚 **Topic:** Securing workstations, servers, mobile devices, IoT, and embedded systems

---

## 🔑 Key Concept

- **Endpoint Protection:** Endpoints (desktops, servers, IoT, ICS/SCADA) are the most targeted assets. Protection combines hardening, monitoring (EDR/XDR), patching, and lifecycle management.

- **Secure Baselines:** Standard configurations for each endpoint type — establish, deploy, and maintain to reduce attack surface.

- **Hardening:** Removing unnecessary software, disabling ports/protocols, changing defaults, enabling host-based firewalls/HIPS, and encryption.

- **Asset Lifecycle:** Acquisition → Assignment → Monitoring → Disposal/Decommissioning — with proper sanitization, destruction, and certification at the end.

- **Specialized Endpoints:** IoT (limited resources, hard to patch), ICS/SCADA (critical infrastructure, uptime priority), RTOS (real-time constraints), and embedded systems (hardcoded credentials).

---

## 🛠️ Tools/Techniques

- Endpoint Detection & Response (EDR) / Extended Detection & Response (XDR)
- Secure baselines (Establish, deploy, maintain)
- Hardening targets (Workstations, servers, IoT, ICS/SCADA, RTOS, embedded)
- Trusted Platform Module (TPM), HSM, key management
- Encryption (Full-disk, file, volume)
- Patch management and configuration enforcement
- Decommissioning (Sanitization, destruction, certification)
- Group Policy, SELinux for OS security

---

## 🛡️ SOC Relevance

- EDR alerts are primary incident sources — process trees, network connections, and file hashes tell the story.
- Patching status correlates with exploit attempts — track vulnerabilities.
- IoT/ICS logs may indicate physical impact scenarios (e.g., power grid manipulation).
- Asset lifecycle awareness helps with ownership, scope, and evidence preservation.
- Endpoint isolation is a critical containment action — know how to quarantine remotely.

---

## 📝 Summary

Endpoints are where attacks land — phishing, malware, credential theft. This chapter drilled that protection isn't just AV; it's baselines, monitoring, and lifecycle management. For a SOC Analyst, the EDR dashboard is a second home, and knowing asset context is half the investigation.
