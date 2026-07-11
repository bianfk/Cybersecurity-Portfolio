# 📘 Chapter 15: Digital Forensics

📅 **Date Completed:** 2026-03-20  
📚 **Topic:** Forensic investigation, evidence handling, and legal considerations

---

## 🔑 Key Concept

- **Digital Forensics:** The process of preserving, analyzing, and reporting digital evidence. Key practices ensure evidence is admissible in court.

- **Chain of Custody:** Documentation that tracks evidence from collection to presentation — who handled it, when, and why. Protects integrity and admissibility.

- **Acquisition:** Creating forensically sound copies of data (disk, memory, network) without altering the original. Tools like FTK, Autopsy, and Volatility.

- **Legal Hold:** Preserving evidence when litigation is anticipated — stopping normal data retention/deletion policies.

- **E-Discovery:** Identifying and producing electronic evidence in legal proceedings — often broad and time-consuming.

- **Reporting:** Documenting findings clearly for non-technical stakeholders (legal, management, court).

---

## 🛠️ Tools/Techniques

- Legal hold and e-discovery
- Chain of custody documentation
- Acquisition (Disk, memory, network) — FTK, Autopsy, Volatility
- Preservation and imaging
- Reporting and expert testimony
- Data sources (Firewall logs, application logs, endpoint logs, packet captures)
- Timeline reconstruction

---

## 🛡️ SOC Relevance

- IR transitions to forensics when legal action is possible — know when to switch modes.
- Chain of custody and documentation protect investigation integrity — document everything.
- Analysts often collect initial evidence (logs, images) for handoff to forensic specialists.
- Understanding forensics helps scope incidents and preserve critical data before it's lost.
- Missing logs or out-of-cycle logging may indicate tampering — investigate.

---

## 📝 Summary

Forensics is the detective work of security. I learned that preservation comes first — don't accidentally destroy evidence. Chain of custody isn't just paperwork; it protects the case. For a SOC Analyst, even if you're not doing deep forensics, knowing how to preserve and hand off evidence is essential.
