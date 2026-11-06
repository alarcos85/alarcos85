# Hi, I'm Carlos 👋

**Application Security · Web Pentesting · Vulnerability Research**

I test web applications and APIs, with a focus on **access control, authentication, payment flows, and business logic**. I enjoy manual testing, understanding why a flaw exists, and turning technical findings into clear, reproducible reports.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://es.linkedin.com/in/carlos-alarcos-mac%C3%ADas-661285163)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alarcos85@gmail.com)
[![eWPT](https://img.shields.io/badge/eWPT-Certified-2E7D32?style=for-the-badge)](https://certs.ine.com/cf06499c-d3b0-436b-8aed-26f6f394e20d#acc.ETMLecgy)
[![eJPT](https://img.shields.io/badge/eJPT-Certified-2E7D32?style=for-the-badge)](https://certs.ine.com/734d79d7-adcd-449f-b658-67f6fbae5f95#acc.xikNz7Hn)
[![Published CVEs](https://img.shields.io/badge/Published_CVEs-2-E67E22?style=for-the-badge)](#-published-vulnerabilities)

---

## 🏆 Published vulnerabilities

I discovered and responsibly reported **two high-severity vulnerabilities in [FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)**, an open-source billing and client management platform. Both involved missing validation between payment transactions and invoices, and both were fixed in **version `0.8.8`**.

| Official advisory | What could go wrong | CWE | CVSS 4.0 |
|---|---|---|---|
| **[CVE-2026-111051](https://github.com/FOSSBilling/FOSSBilling/security/advisories/GHSA-8qj7-53mp-qgxv)** — Stripe | A completed one-time payment could be credited to a different client's invoice. | CWE-639 | ![8.2 High](https://img.shields.io/badge/8.2-High-E67E22?style=flat-square) |
| **[CVE-2026-111050](https://github.com/FOSSBilling/FOSSBilling/security/advisories/GHSA-6h67-77vv-rhx8)** — PayPal | A legitimate payment could be credited to another client's invoice instead of the intended one. | CWE-639 | ![7.1 High](https://img.shields.io/badge/7.1-High-E67E22?style=flat-square) |

The official GitHub Security Advisories document the technical impact, affected versions, fixes, and my acknowledgement as **[@alarcos85](https://github.com/alarcos85) (Reporter)**.

---

## 🔍 Areas of focus

- **Web application pentesting:** broken access control (including IDOR), authentication, session management, injection, and business logic.
- **API security:** object-level authorization (BOLA), endpoint testing, and data exposure.
- **Payment workflow security:** transaction-to-invoice binding, callback validation, and trust boundaries.
- **Open-source vulnerability research:** manual verification, safe proofs of concept, and coordinated disclosure.
- **Technical reporting:** reproducible evidence, impact assessment, CWE classification, and CVSS 4.0.

## 🛠️ Tools & methodologies

A selection of the tools I use most in **web and API security testing**:

**Web & API**

![Burp Suite Pro](https://img.shields.io/badge/Burp_Suite_Pro-FF6633?style=for-the-badge&logo=burpsuite&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Browser DevTools](https://img.shields.io/badge/Browser_DevTools-4285F4?style=for-the-badge)

**Discovery & validation**

![ffuf](https://img.shields.io/badge/ffuf-37474F?style=for-the-badge)
![Nuclei](https://img.shields.io/badge/Nuclei-1E88E5?style=for-the-badge)
![sqlmap](https://img.shields.io/badge/sqlmap-B71C1C?style=for-the-badge)
![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=for-the-badge)

**Scripting & methodology**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![OWASP WSTG](https://img.shields.io/badge/OWASP_WSTG-000000?style=for-the-badge&logo=owasp&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)

<details>
<summary><strong>Other tools & ongoing learning</strong></summary>

- **Additional web / infrastructure tools:** SoapUI, Subfinder, Gobuster, Dirsearch, Wfuzz, Nikto, Nessus, Metasploit, Wireshark, and Groovy.
- **Mobile security (learning):** Frida, objection, Drozer, jadx, apktool, Ghidra, MobSF, and adb; guided by OWASP MASVS / MASTG.
- **Platforms:** Linux and Windows.

</details>

## 🎓 Certifications & education

| Credential | Status |
|---|---|
| **eWPT** — Web Application Penetration Tester · INE Security | [Verify certificate ↗](https://certs.ine.com/cf06499c-d3b0-436b-8aed-26f6f394e20d#acc.ETMLecgy) |
| **eJPT** — Junior Penetration Tester · INE Security | [Verify certificate ↗](https://certs.ine.com/734d79d7-adcd-449f-b658-67f6fbae5f95#acc.xikNz7Hn) |
| **ASIR** — Higher Vocational Degree in Network Systems Administration | Final year · expected 2027 |
| **eMAPT** — Mobile Application Penetration Tester · INE Security | In preparation |

## 🧭 How I work

- **Manual-first:** automation helps with coverage, but I validate findings by examining real requests and application behavior.
- **Evidence over assumptions:** I prioritize verified impact and reproducible steps over long lists of possible issues.
- **Scope-driven:** testing is performed only with authorization and within an agreed scope.
- **Responsible disclosure:** I report privately to maintainers and coordinate public disclosure after remediation.

---

*Security research should leave systems safer than it found them.*
