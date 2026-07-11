# 📘 Chapter 7: Cryptography and the PKI

📅 **Date Completed:** 2025-11-23  
📚 **Topic:** Encryption, hashing, digital signatures, certificates, and cryptographic attacks

---

## 🔑 Key Concept

- **Public Key Infrastructure (PKI):** A system of certificates, CAs, and revocation methods (CRL/OCSP) that establishes trust. It uses public/private key pairs to encrypt, sign, and verify identities.

- **Encryption Types:** Symmetric (same key for encrypt/decrypt — AES, ChaCha20) and Asymmetric (public/private key pairs — RSA, ECC). Both are used depending on speed and security needs.

- **Hashing & Salting:** Hashing creates fixed-length digests (SHA-2, SHA-3) for integrity verification. Salting adds random data to prevent rainbow table attacks.

- **Digital Signatures:** Provide non-repudiation — proving who signed something and that it hasn't been altered.

- **Cryptographic Attacks:** Downgrade attacks (forcing weaker crypto), collision attacks (finding different inputs with same hash), and birthday attacks (exploiting probability in hash collisions).

---

## 🛠️ Tools/Techniques

- Symmetric encryption (AES, ChaCha20)
- Asymmetric encryption (RSA, ECC)
- Hashing algorithms (SHA-2, SHA-3) and salting
- Digital signatures and key stretching
- Certificate authorities (CAs), CSRs, CRLs, OCSP
- Self-signed, third-party, and wildcard certificates
- Steganography and obfuscation methods
- Hardware Security Modules (HSMs) and key escrow
- Blockchain and open public ledgers

---

## 🛡️ SOC Relevance

- Expired certificates cause outages — monitoring certificate lifecycles is a daily SOC task.
- Weak cipher suites or outdated TLS versions indicate misconfigurations or active downgrade attacks.
- Hashing helps verify file integrity during incident response (e.g., comparing malware hashes to known good files).
- CRL/OCSP failures may indicate PKI infrastructure issues or active attacks.
- Cryptographic attack indicators (e.g., protocol downgrades) appear in authentication and VPN logs.

---

## 📝 Summary

This chapter taught me that cryptography is both a math-heavy science and an operational discipline. PKI keeps the internet's trust model running, but it requires vigilant management — expired certs, weak ciphers, and poor key handling create openings. For a SOC Analyst, crypto health checks become routine: TLS versions, cert expiry, and hash verification are daily habits.
