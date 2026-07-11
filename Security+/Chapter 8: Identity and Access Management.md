# 📘 Chapter 8: Identity and Access Management

📅 **Date Completed:** 2026-01-07  
📚 **Topic:** Authentication, authorization, access control models, and identity lifecycle

---

## 🔑 Key Concept

- **AAA (Authentication, Authorization, Accounting):** The foundation of IAM — verify who you are, what you can do, and track what you did.

- **Authentication Factors:** Something you know (password), have (token/phone), are (biometrics), or where you are (geolocation). MFA combines two or more.

- **Access Control Models:** Mandatory (MAC), Discretionary (DAC), Role-Based (RBAC), Attribute-Based (ABAC), and Rule-Based — each enforces permissions differently.

- **Federation & SSO:** Allow users to authenticate once and access multiple systems (SAML, OAuth, LDAP). Reduces password fatigue but creates a single point of failure.

- **Privileged Access Management (PAM):** Tools that manage admin access with just-in-time permissions, password vaulting, and ephemeral credentials.

---

## 🛠️ Tools/Techniques

- MFA implementations (biometrics, security keys, hard/soft tokens)
- SSO and federation (SAML, OAuth, OpenID Connect, LDAP)
- Access control models (MAC, DAC, RBAC, ABAC, Rule-based)
- Password best practices (length, complexity, expiration, password managers)
- Privileged Access Management (PAM) — JIT, vaulting, ephemeral credentials
- Identity proofing and attestation
- User provisioning and de-provisioning

---

## 🛡️ SOC Relevance

- IAM logs (Windows Event 4624/4625, Azure AD/Okta audits) are prime detection sources.
- Look for brute force, password spraying, and impossible travel anomalies.
- MFA enrollment changes or SSO activity from unusual locations often indicate account takeover.
- PAM logs reveal risky admin actions or overprivileged accounts.
- Least privilege violations are high-priority findings — escalate quickly.

---

## 📝 Summary

IAM is the perimeter in a Zero Trust world. Weak identity controls = breach waiting to happen. I learned that IAM isn't just about setting up MFA — it's continuous monitoring, least privilege enforcement, and understanding federation flows. As a SOC Analyst, I'll live in IAM dashboards daily.
