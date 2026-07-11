# 📘 Chapter 12: Network Security

📅 **Date Completed:** 2026-02-18  
📚 **Topic:** Network architecture, segmentation, monitoring, Zero Trust, and deception technologies

---

## 🔑 Key Concept

- **Zero Trust:** Never trust, always verify. Control plane (adaptive identity, policy engine, policy administrator) enforces decisions; data plane (subjects, policy enforcement point) executes them.

- **Deception Technology:** Honeypots, honeynets, honeyfiles, and honeytokens — decoys designed to lure attackers and trigger high-fidelity alerts.

- **Network Attacks:** DDoS (amplified, reflected), DNS attacks, wireless attacks, on-path attacks, credential replay — each has distinct indicators.

- **Network Controls:** Firewalls (NGFW, WAF, UTM), IDS/IPS (inline/passive), segmentation (physical/logical), and secure communications (VPN, TLS, IPSec, SD-WAN, SASE).

- **Failure Modes:** Fail-open (allows traffic if control fails) vs. Fail-closed (blocks traffic) — critical design decision with security implications.

---

## 🛠️ Tools/Techniques

- Firewalls (NGFW, WAF, UTM, Layer 4/Layer 7)
- IDS/IPS (Inline, passive, signatures, trends)
- Segmentation (Physical/logical, microsegmentation)
- Deception (Honeypots, honeynets, honeyfiles, honeytokens)
- Secure communications (VPN, TLS, IPSec, SD-WAN, SASE)
- Network appliances (Jump servers, proxy, load balancers)
- Port security (802.1X, EAP)
- DNS filtering and email security (DMARC, DKIM, SPF)
- Network Access Control (NAC)

---

## 🛡️ SOC Relevance

- Firewall/IDS logs, NetFlow, and PCAPs are the SOC's bread and butter — learn to read them.
- DDoS and DNS attacks are common — understand amplification/reflection to triage quickly.
- Deception tech triggers high-fidelity alerts for attacker presence — low false positives.
- Zero Trust violations (policy engine/PA mismatches) need investigation.
- Segmentation violations (traffic crossing zones unexpectedly) are high-priority.

---

## 📝 Summary

Network security is foundational — controls are the moat. I learned that segmentation and Zero Trust limit blast radius, while deception reveals attackers early. For a SOC Analyst, network telemetry is core — knowing flows, zones, and failure modes (fail-open/close) is essential.
