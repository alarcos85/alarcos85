# Hi, I'm Carlos 👋

**Application Security · Web Penetration Testing · Vulnerability Research**

I test web applications and APIs, with a particular interest in access control, payment flows, and business logic. I prefer hands-on verification and clear, reproducible findings over scanner noise.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://es.linkedin.com/in/carlos-alarcos-mac%C3%ADas-661285163)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:alarcos85@gmail.com)
[![eWPT](https://img.shields.io/badge/eWPT-Certified-2E7D32?style=for-the-badge)](https://certs.ine.com/cf06499c-d3b0-436b-8aed-26f6f394e20d#acc.ETMLecgy)
[![eJPT](https://img.shields.io/badge/eJPT-Certified-2E7D32?style=for-the-badge)](https://certs.ine.com/734d79d7-adcd-449f-b658-67f6fbae5f95#acc.xikNz7Hn)
[![Published CVEs](https://img.shields.io/badge/Published_CVEs-2-E67E22?style=for-the-badge)](#published-vulnerabilities)

---

<a id="published-vulnerabilities"></a>
## 🏆 Published vulnerabilities

I discovered and responsibly reported **2 High-severity vulnerabilities in [FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)**, an open-source billing platform. Both issues involved incorrect binding of payment transactions to invoices, were addressed in **version 0.8.8**, and publicly credit me as **[@alarcos85](https://github.com/alarcos85)** (*Reporter*).

| CVE / Official advisory | Finding | Classification | CVSS v4.0 |
|---|---|---|---|
| **[CVE-2026-111051](https://github.com/FOSSBilling/FOSSBilling/security/advisories/GHSA-8qj7-53mp-qgxv)** | **Stripe:** a completed one-time payment could be credited to another client's invoice. | CWE-639 | **8.2 · High** |
| **[CVE-2026-111050](https://github.com/FOSSBilling/FOSSBilling/security/advisories/GHSA-6h67-77vv-rhx8)** | **PayPal:** a legitimate payment could be credited to another client's invoice instead of the intended one. | CWE-639 | **7.1 · High** |

Both vulnerabilities affected the **integrity of the billing process**. The links above lead to the official GitHub Security Advisories, including technical details, severity metrics, remediation information, and reporter credit.

---

## 🔍 Areas of focus

- **Web application pentesting:** access control (IDOR), authentication, session management, injection, and business logic.
- **API security:** object-level authorization (BOLA), endpoint testing, and data exposure.
- **Payment workflow security:** transaction-to-invoice validation and trust boundaries between integrations.
- **Open-source vulnerability research:** verification, proof of concept, and coordinated disclosure.
- **Technical reporting:** reproducible evidence, impact analysis, CWE references, and CVSS v4.0.

## 🧭 How I work

- **Manual-first testing:** I use automation for coverage, then investigate suspicious behavior with Burp Suite Pro and browser DevTools.
- **Clear evidence:** I document the smallest safe proof of impact and avoid reporting unverified findings.
- **Authorized testing:** I work within agreed scopes and report vulnerabilities privately before public disclosure.

## 🎓 Certifications & education

| Credential | Status |
|---|---|
| **eWPT** — Web Application Penetration Tester (INE) | [Verified credential](https://certs.ine.com/cf06499c-d3b0-436b-8aed-26f6f394e20d#acc.ETMLecgy) |
| **eJPT** — Junior Penetration Tester (INE) | [Verified credential](https://certs.ine.com/734d79d7-adcd-449f-b658-67f6fbae5f95#acc.xikNz7Hn) |
| **ASIR** — Higher Vocational Degree in Network Systems Administration | Final year · expected 2027 |
| **eMAPT** — Mobile Application Penetration Tester (INE) | In preparation |

## 🛠️ Tools & methodologies

| Area | Tools / methodologies |
|---|---|
| **Web & API testing** | Burp Suite Pro, OWASP ZAP, Postman, SoapUI, browser DevTools |
| **Recon & validation** | Subfinder, ffuf, Gobuster, Dirsearch, Wfuzz, Nuclei, Nikto, sqlmap |
| **Network & infrastructure** | Nmap, Nessus, Metasploit, Wireshark |
| **Scripting & automation** | Python, Bash, Groovy |
| **Standards & frameworks** | OWASP WSTG, CWE, CVSS v4.0 |
| **Operating systems** | Kali Linux, Linux, Windows |

<details>
<summary><b>Additional learning: mobile application security</b></summary>

Currently developing my Android/iOS testing skills using Frida, objection, Drozer, jadx, apktool, Ghidra, MobSF, and adb, guided by OWASP MASVS / MASTG.

</details>

---

## 🛡️ Responsible disclosure

I only test systems with authorization. My goal is to provide actionable findings that help maintainers fix vulnerabilities before they can be abused.
