# Secure Cloud Infrastructure

**Internship Project | Internee.pk**

## Project Overview

This project focuses on strengthening cloud infrastructure security through security auditing, Identity and Access Management (IAM) hardening, Web Application Firewall (WAF) protection, and multi-region disaster recovery planning.

The project combines cloud security concepts with practical lab-based testing to identify potential vulnerabilities, improve access control, protect web applications, and support infrastructure resilience.

## Objectives

- Assess cloud infrastructure security configurations and identify potential risks.
- Apply IAM security principles and least-privilege access control practices.
- Develop and test a custom Web Application Firewall (WAF) in a local lab environment.
- Explore protection against common web application attacks.
- Design a multi-region backup and disaster recovery strategy.
- Document security findings, testing activities, and recommendations.

## Project Components

### 1. Cloud Security Audit
Review of cloud account and infrastructure configurations to identify security weaknesses and recommend improvements.

### 2. IAM Hardening
Focus on access control, least privilege, secure identity management, and reducing unnecessary permissions.

### 3. Web Application Firewall (WAF)
A custom Python-based WAF prototype developed for local lab testing. It includes request processing, normalization, security rules, rate limiting, and logging.

The rule modules address attack patterns associated with:
- SQL Injection (SQLi)
- Cross-Site Scripting (XSS)
- Command Injection
- Local and Remote File Inclusion (LFI/RFI)
- Suspicious HTTP headers and protocol patterns

### 4. Multi-Region Resilience
A disaster recovery design covering cross-region backup concepts, data availability, and recovery planning to improve resilience against infrastructure failures.

## Technologies and Concepts

- Python
- Cloud Security
- Identity and Access Management (IAM)
- Web Application Firewall (WAF)
- HTTP Request Inspection
- Rate Limiting and Security Logging
- SQL Injection and XSS Detection
- Backup and Disaster Recovery Planning

## Repository Structure

```text
Secure-Cloud-Infrastructure/
├── WAF/
│   ├── config.py
│   ├── engine.py
│   ├── logger.py
│   ├── normalizer.py
│   ├── proxy.py
│   ├── rate_limiter.py
│   └── rules/
├── Secure_Cloud_Infrastructure_Report.docx
└── README.md
```

*Note: The repository structure may vary depending on the files uploaded.*

## Security Testing

The WAF component was evaluated in a local lab environment using simulated web attack patterns. The project focuses on request inspection, rule-based detection, normalization, rate limiting, and event logging.

The cloud security and multi-region resilience sections document audit considerations, hardening recommendations, and disaster recovery design.

## Key Learning Outcomes

- Understanding cloud infrastructure security risks.
- Applying IAM hardening and least-privilege principles.
- Developing rule-based web request inspection logic in Python.
- Understanding common web application attack patterns.
- Improving security documentation and incident-prevention practices.
- Planning for backup, recovery, and infrastructure resilience.

## Limitations

The custom WAF was developed for local lab testing and should not be considered a production-ready security solution. The multi-region recovery component represents a design unless deployment evidence is provided. Cloud controls should be independently verified before being considered implemented.

## Conclusion

This project demonstrates a structured approach to cloud infrastructure security by combining security auditing, IAM hardening concepts, local WAF development, and disaster recovery planning. It provides practical learning experience in identifying security risks and designing measures to improve infrastructure protection and resilience.

## Author

**Hajra Sarfraz**

Cybersecurity Intern | Internee.pk

## Disclaimer

This project is intended for educational and authorized security-testing purposes only. All security testing should be conducted in controlled environments or on systems for which explicit permission has been granted.
