<div align="center">

# 🎯 Penetration Testing Reports

![Reports](https://img.shields.io/badge/Reports-2-brightgreen?style=for-the-badge)
![Type](https://img.shields.io/badge/Type-Black--box-red?style=for-the-badge)

Black-box penetration test write-ups against real HackTheBox machines — full recon-to-report engagements, not isolated vulnerability drills (see [`web-app-penetration-tests-1`](https://github.com/wojtekn24/web-app-penetration-tests-1) for those).

</div>

---

## Reports

| Target | Result | Highlights |
|---|---|---|
| [**DevHub**](reports/devhub/) | 🟢 Root | Unauthenticated RCE (CVE-2026-23744) → hardcoded creds → root-owned service leaks root's SSH key |
| [**Helix**](reports/helix/) | 🟢 Root | Virtual-host discovery → Apache NiFi RCE → SSH key pivot → user flag, OPC UA escalation path identified |

*Coursework labs (fundamentals: Kali setup, Nmap, Burp Suite/DVWA, service enumeration) — coming soon.*

---

## Tools & Technologies

`Nmap` · `ffuf` · `WhatWeb` · `OWASP ZAP` · `Burp Suite` · `Metasploit` · `linpeas.sh` · `chisel` · `Apache NiFi` · `Kali Linux` · `HackTheBox`

## Skills Demonstrated

- End-to-end black-box methodology: recon → enumeration → exploitation → privilege escalation → reporting
- Exploiting known CVEs and misconfigured/exposed developer tools for initial access
- Abusing legitimate application features (e.g. a workflow engine's command-execution processor) for RCE
- Post-exploitation enumeration, credential hunting, and pivoting (tunneling, token/key reuse)
- Formal report writing: risk classification (CVSS), remediation prioritization, attack-chain documentation
