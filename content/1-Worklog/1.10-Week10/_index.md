---
title: "Week 10 Worklog"
date: 2026-03-22
weight: 10
chapter: false
pre: " <b> 1.10. </b> "
---

### Week 10 Objectives:

* Apply Shift-Left Security principles by conducting a comprehensive Penetration Test on the Microservices architecture deployed in the Local Docker environment.
* Identify, exploit, and report vulnerabilities based on the OWASP Top 10 to ensure remediation before the AWS deployment.

### Tasks Implemented During the Week:

| Day | Task | Start Date | Completion Date | Resource / Material |
| :--- | :--- | :--- | :--- | :--- |
| Mon | - Conducted reconnaissance on `fptevent.local`. Discovered infrastructure port exposure (8081-8086) and Database (3306).<br> - Exploited MySQL access, utilized Hashcat for Offline Cracking to demonstrate weak password hashing. | 16/03/2026 | 16/03/2026 | Local Environment / Nmap, Hashcat |
| Tue | - Tested APIs using Burp Suite: Bypassed internal authentication via `x-internal-call` header and found missing Rate Limiting on Forgot Password.<br> - Evaluated Frontend with OWASP ZAP: Exploited Source Code Disclosure and Client-side privilege escalation via LocalStorage. | 17/03/2026 | 17/03/2026 | Burp Suite, OWASP ZAP |
| Wed | - Consolidated Proof of Concepts (PoC) and assessed risk levels.<br> - Finalized the detailed "Penetration Test Report," providing remediation recommendations (in-transit encryption, secrets management, token security). | 18/03/2026 | 18/03/2026 | Project Documentation |
| Thu | - Directly handed over the Pentest Report to the development team. Monitored and expedited the root cause analysis and patching progress via the team's internal communication channels. | 19/03/2026 | 19/03/2026 | Pentest Report |
| Fri | - Supported the team in reviewing the newly applied security patches.<br> - Collaborated with DevOps to plan Security Group and AWS WAF configurations in preparation for the Production deployment. | 20/03/2026 | 20/03/2026 | Internal Team |

### Week 10 Achievements:

* Successfully conducted a hands-on Pentest (Black-box/Grey-box) on the project's Microservices architecture.
* Identified and successfully proved (PoC) 4 critical vulnerability groups across Infrastructure, Backend, and Frontend according to OWASP standards.
* Finalized a professional Penetration Test Report, delivering timely remediation solutions.
* Ensured the system meets baseline security standards before officially migrating to the AWS Cloud environment.