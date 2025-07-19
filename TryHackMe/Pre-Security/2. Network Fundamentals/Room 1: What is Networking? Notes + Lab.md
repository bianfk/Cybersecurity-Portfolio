## Room Completed: What is Networking?

📅 **Date:** 2025-07-16

---

## ✅ Key Concepts

- A **computer network** can consist of two or more devices and can be:
  - **Private** (internal, local use)
  - **Public** (internet-facing)

- Devices are identified using:
  - **IP Addresses**
    - IPv4: `192.168.1.1` (limited to ~4.29 billion)
    - IPv6: `2001:0db8:85a3:0000:0000:8a2e:0370:7334` (virtually unlimited)
  - **MAC Addresses**
    - Unique hardware address (e.g., `a4:c3:f0:85:ac:2d`)
    - First 6 chars = manufacturer, last 6 = unique device ID
    - Can be spoofed by attackers

- The `ping` command uses **ICMP (Internet Control Message Protocol)** to:
  - Test if two devices are connected
  - Measure network performance and packet loss

---

## 🧪 Lab Completed: How to Ping?

![How to ping](../../assets/pinging1.png)

🔍 **Observation:**  
Pinging `8.8.8.8` resulted in 4 packets sent and received, with an average response time of 9.428 ms.

---

## 🛡️ Why This Matters for SOC Analysts

- Helps analysts **understand normal communication patterns** between devices.
- Crucial for detecting:
  - **Suspicious IP or MAC address activity**
  - **Spoofing or scanning behavior**
- Knowing basic network tools like `ping` is essential for:
  - **Connectivity verification**
  - **Troubleshooting during incident response**
