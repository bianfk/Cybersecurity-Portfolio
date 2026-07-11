# 📘 Chapter 13: Wireless and Mobile Security

📅 **Date Completed:** 2026-03-01  
📚 **Topic:** Securing Wi-Fi, Bluetooth, and mobile devices in enterprise environments

---

## 🔑 Key Concept

- **Wireless Risks:** Eavesdropping, rogue access points, evil twin attacks, deauthentication attacks, and KRACK. Strong protocols (WPA3) and AAA/RADIUS are essential.

- **Mobile Risks:** Jailbreaking (iOS) and rooting (Android) bypass security controls. Sideloading apps introduces malware risks. Lost/stolen devices expose data.

- **Deployment Models:** BYOD (employee-owned), COPE (corporate-owned, personally enabled), CYOD (choose your own device) — each has different security implications and privacy considerations.

- **MDM:** Mobile Device Management enforces policies — device encryption, passcode requirements, app whitelisting, remote wipe, and compliance monitoring.

- **Site Planning:** Site surveys and heat maps ensure proper wireless coverage — reducing dead zones that force users to use insecure networks.

---

## 🛠️ Tools/Techniques

- Wireless security (WPA3, AAA/RADIUS, cryptographic protocols)
- Mobile Device Management (MDM) — enrollment, policy, wipe
- Deployment models (BYOD, COPE, CYOD)
- Connection methods (Cellular, Wi-Fi, Bluetooth)
- Site surveys and heat maps
- Hardening targets (Mobile devices, IoT, embedded)
- Geofencing and geolocation

---

## 🛡️ SOC Relevance

- Mobile device logs show jailbreak/root detections, sideloaded apps, and policy violations.
- Wireless attacks (evil twin, deauth, KRACK) appear as authentication anomalies or disconnections.
- MDM compliance alerts identify devices out of policy — investigate quickly.
- Geolocation data helps with impossible travel investigations and physical security correlation.
- Bluetooth attacks (BlueBorne, Bluejacking) appear in endpoint logs.

---

## 📝 Summary

Mobile and wireless are everywhere, and they expand the attack surface significantly. I learned that MDM, strong wireless auth (WPA3/802.1X), and thoughtful deployment models are critical. For a SOC Analyst, mobile alerts are growing — and physical proximity matters more than ever.
