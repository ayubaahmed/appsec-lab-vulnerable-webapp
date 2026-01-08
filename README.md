# Application Security Practice Lab – OWASP Security Shepherd

This repository is my personal lab for learning and practicing application security.  
It’s based on the OWASP Security Shepherd project and is intentionally vulnerable so I can safely experiment with different security tools, review code, and explore real-world vulnerabilities.

---

## WARNING – INTENTIONALLY VULNERABLE

This app is deliberately insecure.

- Only run it locally or in a controlled environment (VM, Docker, etc.)  
- Do not deploy it to production  
- Do not expose it to the public internet  
- All vulnerabilities are there on purpose to help me learn

---

## What I’m Practicing

This lab helps me get hands-on experience with:

- Common web and mobile app vulnerabilities, including OWASP Top 10  
- Static and dynamic analysis of code  
- Dependency and secret scanning  
- Container and Docker image security  
- CI/CD pipeline security and workflow testing  
- Threat modeling and secure coding practices

I also use it to experiment with different security tools and document my findings as part of building my AppSec skills.

---

## Tools and Techniques

Some of the tools I use with this lab:

- **Static Analysis:** Semgrep, CodeQL, OWASP Dependency-Check  
- **Secret / Dependency Scanning:** Trivy, Gitleaks  
- **Dynamic Testing:** OWASP ZAP, Burp Suite  
- **Container Security:** Docker Scout, Trivy image scanning  
- **CI/CD Security:** GitHub Actions workflows (intentionally vulnerable)

---

## Safety and Scope

- This lab runs locally or in Docker only  
- No real production credentials are used  
- Any “secrets” in the app are fake and meant for practice  
- Everything here is for learning purposes only

---

## About the Original Project

This lab is based on the official OWASP Security Shepherd project:  
https://github.com/OWASP/SecurityShepherd

Security Shepherd is designed to teach application security through hands-on exercises in a safe environment. It’s meant for both beginners and people looking to sharpen their penetration testing skills.

---

## Why I Use This Lab

I use this lab to learn, experiment, and document my AppSec findings.  
It’s a safe space to explore vulnerabilities, test security tools, and improve my understanding of web application security without risking real systems.
