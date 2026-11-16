
# The Paperclip Incident: From Breach to Policy

**Texas State University | ISAN 4350 – Offensive Security Capstone | October 2026**

## Project Overview

This project was completed for my Ethical Hacking course at Texas State University. The assignment was to investigate the August 2026 Paperclip security incident and develop security policies that could have prevented the vulnerabilities from being exploited.

Paperclip is an open-source platform designed to manage autonomous AI agents. In August 2026, several security vulnerabilities were disclosed, including CVE-2026-41679, a critical vulnerability with a CVSS score of 10.0 that could allow an attacker to execute commands on the server.

The goal of this assignment was to understand how the attack worked, identify where security controls failed, and develop policies and procedures that could help prevent similar incidents in the future.

## What I Worked On

Throughout this assignment, I researched the vulnerabilities involved in the Paperclip incident and developed security recommendations based on the weaknesses I identified.

My work included:

- **Incident Analysis:** Examined the attack chain for CVE-2026-41679, identified the security controls that failed, and connected those weaknesses to their corresponding CWE classifications.

- **Vulnerability Assessment:** Analyzed the CVSS 3.1 score to understand the severity of the vulnerability and its potential impact on confidentiality, integrity, and availability.

- **Threat Modeling:** Created a data-flow diagram and attack tree to visualize how the attacker moved through the system. I also used the STRIDE framework to identify potential threats and recommend ways to address them.

- **Security Policy Development:** Wrote policies covering user authentication, API credential approval, access privileges, credential expiration, and secure agent execution.

- **Incident Response Planning:** Developed monitoring requirements and a response plan outlining how a security team should contain an attack, preserve evidence, review compromised credentials, and prepare for recovery.

- **Security Ethics:** Examined coordinated vulnerability disclosure and the legal and ethical responsibilities involved in identifying and reporting security vulnerabilities.

## Key Takeaways

One of the biggest things I learned from this assignment was how several smaller security weaknesses can work together to create a much larger vulnerability.

In the Paperclip incident, the attacker was able to take advantage of multiple security failures involving user registration, credential approval, authorization, and agent execution. While each weakness presented its own security risk, combining them allowed the attacker to eventually execute commands on the server.

This project helped me better understand how cybersecurity involves more than just finding vulnerabilities. It also requires understanding how attacks happen, developing policies to prevent them, and having procedures in place to respond when something goes wrong.

## Project Documentation

The full report includes my vulnerability analysis, threat models, security policies, incident response procedures, and supporting research.

**[View Full Paperclip Security Analysis Report](Final%20Report.pdf)**

---

*This project was completed as an academic security analysis and policy-writing assignment. No live exploitation or penetration testing was performed.*
