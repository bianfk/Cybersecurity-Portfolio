# 📘 Chapter 14: Monitoring and Incident Response

📅 **Date Completed:** 2026-03-07  
📚 **Topic:** Security monitoring, alerting, SIEM, and the IR lifecycle

---

## 🔑 Key Concept

- **Security Monitoring:** Collecting and analyzing telemetry (logs, alerts, NetFlow) to detect threats. SIEM aggregates and correlates data from across the environment.

- **Indicators of Malicious Activity:** Account lockout, concurrent session usage, impossible travel, resource consumption, resource inaccessibility, out-of-cycle logging, missing logs — each hints at potential compromise.

- **Incident Response Lifecycle:** Preparation → Detection → Analysis → Containment → Eradication → Recovery → Lessons Learned. Each phase has specific activities and goals.

- **Threat Hunting:** Proactively searching for threats that evaded detection — using hypotheses, intelligence, and curiosity to find hidden adversaries.

- **Alert Management:** Tuning, escalation, quarantine, and validation — not every alert is an incident; analysts must triage efficiently.

---

## 🛠️ Tools/Techniques

- SIEM (Aggregation, alerting, scanning, reporting, archiving)
- NetFlow and metadata analysis
- Monitoring sources (Systems, applications, infrastructure)
- Indicators (Account lockout, impossible travel, out-of-cycle logging, missing logs)
- Alert response (Quarantine, tuning, validation)
- Incident Response process (Preparation, Detection, Analysis, Containment, Eradication, Recovery, Lessons Learned)
- Testing (Tabletop, simulation)
- Root cause analysis and threat hunting

---

## 🛡️ SOC Relevance

- This is the SOC's core function — monitoring, triage, and response.
- SIEM dashboards and alert queues are the primary workspace — master them.
- Impossible travel, concurrent sessions, and resource consumption are key indicators.
- IR phases guide every decision — contain first, then investigate.
- Threat hunting goes beyond alerts to proactive discovery — hunt regularly.

---

## 📝 Summary

Monitoring and IR are the heartbeat of SOC operations. I learned that SIEM isn't just a tool — it's a workflow. Alert fatigue is real, so tuning matters. IR playbooks turn chaos into procedure. For a SOC Analyst, this chapter is the daily playbook — know the phases, know the tools, stay calm.
