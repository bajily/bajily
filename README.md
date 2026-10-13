# Anas Elgaili · Python Cybersecurity & Security Automation

Aspiring cybersecurity analyst building open-source defensive security tools for enterprise security evaluation.

This portfolio covers IAM access reviews, cloud security posture, network segmentation, TLS monitoring, software supply chain review, secret scanning, vulnerability prioritization, ransomware event triage and backup verification.

## Published security projects

| Project | Purpose |
|---|---|
| [Identity Access Review](https://github.com/bajily/identity-access-review) | Review normalized identity and group exports; explain inherited business and administrative permissions. |
| [Cloud IAM Policy Auditor](https://github.com/bajily/cloud-iam-policy-auditor) | Statically inspect exported IAM JSON before a reviewer approves access changes. |
| [Cloud Storage Exposure Audit](https://github.com/bajily/cloud-storage-exposure-audit) | Review a normalized storage inventory and prioritize exposure using data classification. |
| [Network Segmentation Auditor](https://github.com/bajily/network-segmentation-auditor) | Test a proposed ordered firewall policy against explicit expected traffic decisions. |
| [TLS Certificate Auditor](https://github.com/bajily/tls-certificate-auditor) | Review exported certificate inventory or connect to explicitly listed authorized TLS endpoints. |
| [Software Supply Chain Auditor](https://github.com/bajily/software-supply-chain-auditor) | Trace vulnerable dependencies from an application through a CycloneDX dependency graph. |
| [Secrets Exposure Scanner](https://github.com/bajily/secrets-exposure-scanner) | Detect likely credential material in a repository without printing matched secret values. |
| [Vulnerability Prioritizer](https://github.com/bajily/vulnerability-prioritizer) | Produce a reproducible patch queue from normalized vulnerability and asset exports. |
| [Ransomware Canary Detector](https://github.com/bajily/ransomware-canary-detector) | Correlate exported filesystem events and canary touches into host-level triage findings. |
| [Backup Restore Verifier](https://github.com/bajily/backup-restore-verifier) | Verify an exported backup manifest against a local snapshot before a recovery exercise. |
| [Linux Hardening Auditor](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/linux-hardening-auditor) | Review captured Linux configuration text and permission metadata against a documented baseline. |
| [Windows Security Baseline Auditor](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/windows-security-baseline-auditor) | Evaluate a normalized endpoint control export and report missing, disabled or unknown protections. |
| [Container Security Auditor](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/container-security-auditor) | Review Dockerfile text before merging an application container build. |
| [Kubernetes Manifest Guard](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/kubernetes-manifest-guard) | Review exported Kubernetes JSON resources and explain effective pod/container security-context gaps. |

## Validation and scope

Twenty initial project implementations have been developed and pass 269 automated tests locally. Synthetic SARIF reports for all twenty were validated against the OASIS SARIF 2.1.0 schema. Fourteen project bundles are published above; publication of the remaining six is pending GitHub write availability.

The ten standalone repositories include GitHub Actions tests on Python 3.11 and 3.14. The toolkit projects include independent test suites; deployment of the shared Actions matrix is pending.

Use accurate exports, company-specific policies and representative testing before operational reliance. These initial tools support review and triage; they do not provide a universal protection guarantee or compliance certification.

## Projects prepared for publication

API Access Log Detector · Audit Log Integrity Ledger · Security Configuration Drift · Phishing Email Triage · Threat Intelligence Matcher · Incident Response Orchestrator.

## بالعربية

أنا أنس، مهتم بالأمن السيبراني والبرمجة باستخدام Python والأتمتة الدفاعية. جهّزت 20 مشروعًا بكود وأمثلة واختبارات وتوثيق. الروابط أعلاه تخص 14 مشروعًا منشورًا بالكامل، ويجري استكمال نشر البقية عند توفر الكتابة على GitHub.

يلزم تقييم الأدوات على بيئة الشركة ومراجعة نتائجها قبل الاعتماد التشغيلي عليها.
