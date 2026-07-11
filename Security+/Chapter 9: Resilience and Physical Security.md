# 📘 Chapter 9: Resilience and Physical Security

📅 **Date Completed:** 2026-01-18  
📚 **Topic:** High availability, disaster recovery, backups, physical security controls, and site planning

---

## 🔑 Key Concept

- **High Availability:** Systems designed to stay operational through failures — using load balancing, clustering, and redundancy to eliminate single points of failure.

- **Disaster Recovery Sites:** Hot sites (fully operational), Warm sites (partially ready), and Cold sites (bare bones) — chosen based on RTO/RPO requirements.

- **Backups:** Onsite/offsite, full/incremental/differential, with encryption, snapshots, and replication. Frequency depends on business needs.

- **Physical Security Controls:** Bollards, fencing, access control vestibules, video surveillance, security guards, badges, lighting, and sensors (motion, environmental).

- **Testing:** Tabletop exercises, failover testing, simulation, and parallel processing ensure recovery plans actually work.

---

## 🛠️ Tools/Techniques

- High availability (load balancing, clustering)
- Site types (Hot, Warm, Cold, Geographic dispersion)
- Backups (onsite/offsite, frequency, encryption, snapshots, replication)
- Power (Generators, UPS)
- Testing (tabletop, failover, simulation, parallel processing)
- Physical controls (bollards, vestibules, fencing, lighting, guards, badges)
- Sensors (motion, environmental, RFID)

---

## 🛡️ SOC Relevance

- Physical security incidents (breaches, RFID cloning, environmental events) can lead to digital compromises.
- Backup failures or incomplete recovery impact incident response and business continuity.
- HA failures during attacks can create DDoS-like conditions — know your infrastructure.
- Understanding RTO/RPO helps prioritize response efforts during recovery phases.

---

## 📝 Summary

This chapter showed that security isn't just digital — physical controls and resilience are the bedrock. If the power dies or the datacenter floods, digital security means nothing. For a SOC Analyst, understanding the bigger picture (backups, failover, physical access) adds crucial context during incidents.
