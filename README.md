<h1 align="center">Moosa Baig</h1>

<p align="center">
  <b>Cybersecurity Professional · Vulnerability Assessment & Penetration Testing</b><br/>
  <sub>Web Application · API · Network · Infrastructure Security</sub>
</p>

<p align="center">
  <a href="https://moosabaig.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-moosabaig.github.io-00B4D8?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/moosa-baig-868240273"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="https://www.credly.com/badges/2f877584-935b-415b-a8ca-72ea5a2ecc48/public_url"><img src="https://img.shields.io/badge/APIsec-Certified%20Practitioner-1F2937?style=flat-square" alt="APIsec Certified Practitioner"/></a>
  <a href="https://www.credly.com/badges/4ca64578-c964-4f33-a16b-61d4b9636c13/public_url"><img src="https://img.shields.io/badge/Google-Cybersecurity%20Professional-1F2937?style=flat-square&logo=google&logoColor=white" alt="Google Cybersecurity Professional Certificate"/></a>
  <a href="https://catalog-education.oracle.com/ords/certview/sharebadge?id=C95B56B0BEB58ADF98888B09283031F3C7E0AC26FEFEC028E7989408549399FC"><img src="https://img.shields.io/badge/Oracle-OCI%20Foundations%202025-1F2937?style=flat-square&logo=oracle&logoColor=white" alt="Oracle Cloud Infrastructure Foundations 2025"/></a>
</p>

---

### Profile

Security professional focused on **Vulnerability Assessment and Penetration Testing (VAPT)**. I assess web applications, APIs, networks and infrastructure to identify exploitable weaknesses, validate their real-world impact, and deliver prioritised, actionable remediation guidance to engineering teams and stakeholders.

My work spans the full engagement lifecycle — scoping, testing, risk rating, reporting and retesting — with an emphasis on accurate findings, clear evidence and remediation that teams can actually implement.

---

### Areas of Expertise

| Domain | Scope |
|:--|:--|
| **Web Application Security** | Authentication & session management, access control, injection, business-logic flaws |
| **API Security** | REST API testing, authorisation (BOLA / BFLA), data exposure, rate limiting |
| **Network & Infrastructure** | Internal / external assessments, service enumeration, misconfiguration review |
| **Vulnerability Management** | Scanning, validation, false-positive triage, risk-based prioritisation |
| **Software Supply Chain** | SBOM generation (CycloneDX / SPDX), software composition analysis, license risk |
| **Reporting & Advisory** | Executive summaries, technical findings, proof-of-concept evidence, remediation plans |

---

### Featured Project

#### [SBOM Security Dashboard](https://github.com/moosabaig/sbom-security-dashboard)

A self-hosted **Software Composition Analysis (SCA)** tool that scans projects for dependency manifests, generates a **CycloneDX 1.5 SBOM**, matches components against known vulnerabilities and classifies license risk — presented in an interactive security dashboard.

<a href="https://github.com/moosabaig/sbom-security-dashboard">
  <img src="https://raw.githubusercontent.com/moosabaig/sbom-security-dashboard/main/docs/screenshots/dashboard.png" alt="SBOM Security Dashboard" width="100%"/>
</a>

- **Multi-ecosystem scanning** — npm, Maven/Gradle, PyPI, NuGet and Go, including transitive dependencies
- **Vulnerability intelligence** — OSV.dev matching with NVD CVSS/CWE enrichment and deps.dev license data
- **Risk scoring** — A–F risk grade per scan, severity trends and minimum fix-version upgrade guidance
- **SBOM import & validation** — CycloneDX / SPDX uploads (Black Duck, Syft, Trivy, cdxgen) and OWASP Dependency-Check false-positive triage
- **CI/CD gate** — `--fail-on <severity>` exit codes for GitHub Actions, Azure DevOps and Jenkins
- **Secure by design** — localhost-only binding, DNS-rebinding protection and CSRF-safe API
- **Three implementations** — Node.js, Python and Java, standard library only, sharing one spec and report format

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![CycloneDX](https://img.shields.io/badge/CycloneDX-1.5-1F2937?style=flat-square) ![OSV](https://img.shields.io/badge/OSV.dev-1F2937?style=flat-square) ![NVD](https://img.shields.io/badge/NVD-1F2937?style=flat-square)

---

### Methodology

```
Scoping  →  Reconnaissance  →  Vulnerability Discovery  →  Exploitation & Validation  →  Risk Rating  →  Reporting  →  Retesting
```

**Standards & frameworks:** OWASP Top 10 · OWASP API Security Top 10 · OWASP Web Security Testing Guide · CVSS

---

### Toolkit

| Category | Tools |
|:--|:--|
| **Testing** | ![Burp Suite](https://img.shields.io/badge/Burp%20Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white) ![OWASP ZAP](https://img.shields.io/badge/OWASP%20ZAP-00549E?style=flat-square&logo=owasp&logoColor=white) ![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logo=metasploit&logoColor=white) |
| **Scanning & Recon** | ![Nmap](https://img.shields.io/badge/Nmap-0E83CD?style=flat-square&logo=gnometerminal&logoColor=white) ![Nessus](https://img.shields.io/badge/Nessus-00C176?style=flat-square&logo=tenable&logoColor=white) ![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white) |
| **Scripting** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) |
| **Platforms** | ![Kali Linux](https://img.shields.io/badge/Kali%20Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Windows](https://img.shields.io/badge/Windows-0078D6?style=flat-square&logo=windows&logoColor=white) |
| **Cloud** | ![Oracle Cloud](https://img.shields.io/badge/Oracle%20Cloud-F80000?style=flat-square&logo=oracle&logoColor=white) |

---

### Certifications & Achievements

<table>
  <tr>
    <td align="center" width="25%">
      <a href="https://www.credly.com/badges/2f877584-935b-415b-a8ca-72ea5a2ecc48/public_url">
        <img src="https://raw.githubusercontent.com/moosabaig/Certificates/ba946a3e7f37e5c9bc0fabc9e1e4c564c8204a46/apisec-certified-practitioner.png" width="90" alt="APIsec Certified Practitioner"/>
      </a>
      <br/><b>APIsec Certified Practitioner</b>
      <br/><sub>APIsec University</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://www.credly.com/badges/4ca64578-c964-4f33-a16b-61d4b9636c13/public_url">
        <img src="https://raw.githubusercontent.com/moosabaig/Certificates/main/google-cybersecurity-professional-certificate-v2.png" width="90" alt="Google Cybersecurity Professional Certificate"/>
      </a>
      <br/><b>Cybersecurity Professional Certificate</b>
      <br/><sub>Google</sub>
    </td>
    <td align="center" width="25%">
      <a href="https://catalog-education.oracle.com/ords/certview/sharebadge?id=C95B56B0BEB58ADF98888B09283031F3C7E0AC26FEFEC028E7989408549399FC">
        <img src="https://img.icons8.com/color/96/oracle-logo.png" width="90" alt="Oracle Cloud Infrastructure Foundations 2025"/>
      </a>
      <br/><b>OCI Foundations 2025</b>
      <br/><sub>Oracle</sub>
    </td>
    <td align="center" width="25%">
      <a href="assets/htb-cyber-apocalypse-ctf-2025.pdf">
        <img src="assets/htb-cyber-apocalypse-ctf-2025.jpg" width="130" alt="Hack The Box Cyber Apocalypse CTF 2025"/>
      </a>
      <br/><b>Cyber Apocalypse CTF 2025</b>
      <br/><sub>Hack The Box</sub>
    </td>
  </tr>
</table>

---

### Contact

Open to opportunities in **penetration testing**, **application security** and **security consulting**.
Explore my work at **[moosabaig.github.io/Portfolio](https://moosabaig.github.io/Portfolio/)** or reach me on [LinkedIn](https://www.linkedin.com/in/moosa-baig-868240273).

<p>
  <a href="https://moosabaig.github.io/Portfolio/"><img src="https://img.shields.io/badge/View%20Portfolio-00B4D8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="View Portfolio"/></a>
  <a href="https://www.linkedin.com/in/moosa-baig-868240273"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
</p>
