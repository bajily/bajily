# Anas Elgaili · Python Cybersecurity & Security Automation

Aspiring cybersecurity analyst building open-source tools for enterprise security evaluation, defensive analysis and repeatable security automation.

This portfolio includes **20 independently runnable Python security projects** covering IAM access reviews, cloud security posture, network segmentation, TLS monitoring, DevSecOps, endpoint baselines and incident response planning.

Each project includes a documented input contract, configurable policies, synthetic examples, automated tests, and JSON, SARIF 2.1.0 and Markdown reports. The implementations use the Python standard library.

Ten projects have standalone repositories. Ten are organized as independent projects in the [Enterprise Python Cybersecurity Toolkit](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise).

## Enterprise security project directory

### Identity and cloud

| Project | What it helps review |
|---|---|
| [Identity Access Review](https://github.com/bajily/identity-access-review) | Review normalized identity and group exports; explain inherited business and administrative permissions. |
| [Cloud IAM Policy Auditor](https://github.com/bajily/cloud-iam-policy-auditor) | Statically inspect exported IAM JSON before a reviewer approves access changes. |
| [Cloud Storage Exposure Audit](https://github.com/bajily/cloud-storage-exposure-audit) | Review a normalized storage inventory and prioritize exposure using data classification. |

### Infrastructure

| Project | What it helps review |
|---|---|
| [Network Segmentation Auditor](https://github.com/bajily/network-segmentation-auditor) | Test a proposed ordered firewall policy against explicit expected traffic decisions. |
| [TLS Certificate Auditor](https://github.com/bajily/tls-certificate-auditor) | Review exported certificate inventory or connect to explicitly listed authorized TLS endpoints. |
| [Backup Restore Verifier](https://github.com/bajily/backup-restore-verifier) | Verify an exported backup manifest against a local snapshot before a recovery exercise. |
| [Linux Hardening Auditor](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/linux-hardening-auditor) | Review captured Linux configuration text and permission metadata against a documented baseline. |
| [Windows Security Baseline Auditor](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/windows-security-baseline-auditor) | Evaluate a normalized endpoint control export and report missing, disabled or unknown protections. |
| [Security Configuration Drift](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/security-config-drift) | Compare two reviewed configuration snapshots and prioritize changed security-relevant paths. |

### Software delivery

| Project | What it helps review |
|---|---|
| [Software Supply Chain Auditor](https://github.com/bajily/software-supply-chain-auditor) | Trace vulnerable dependencies from an application through a CycloneDX dependency graph. |
| [Secrets Exposure Scanner](https://github.com/bajily/secrets-exposure-scanner) | Detect likely credential material in a repository without printing matched secret values. |
| [Container Security Auditor](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/container-security-auditor) | Review Dockerfile text before merging an application container build. |
| [Kubernetes Manifest Guard](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/kubernetes-manifest-guard) | Review exported Kubernetes JSON resources and explain effective pod/container security-context gaps. |

### Detection and response

| Project | What it helps review |
|---|---|
| [Vulnerability Prioritizer](https://github.com/bajily/vulnerability-prioritizer) | Produce a reproducible patch queue from normalized vulnerability and asset exports. |
| [Ransomware Canary Detector](https://github.com/bajily/ransomware-canary-detector) | Correlate exported filesystem events and canary touches into host-level triage findings. |
| [API Access Log Detector](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/api-access-log-detector) | Triage normalized request logs into explainable client and route activity findings. |
| [Audit Log Integrity Ledger](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/audit-log-integrity-ledger) | Verify a log export against a protected signing key and an independently stored final-head anchor. |
| [Phishing Email Triage](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/phishing-email-triage) | Analyze bounded MIME email content without opening attachments or following links. |
| [Threat Intelligence Matcher](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/threat-intelligence-matcher) | Match normalized observations against a maintained local indicator dataset. |
| [Incident Response Orchestrator](https://github.com/bajily/Python-Cybersecurity-Toolkit/tree/main/enterprise/incident-response-orchestrator) | Validate a declarative incident playbook and generate an auditable local response plan. |

## Validation and practical scope

The initial release passes **269 automated tests** locally. Synthetic SARIF reports for all 20 projects were validated against the official OASIS SARIF 2.1.0 schema. GitHub Actions runs the project suites on Python 3.11 and 3.14.

These tools support controlled review and triage. They require accurate exports, company-specific policies, false-positive evaluation and independent review before operational reliance. They do not provide a universal protection guarantee or compliance certification.

## Previous learning projects

[SOC authentication triage](https://github.com/bajily/SOC-Portfolio-) · [File integrity monitoring](https://github.com/bajily/file-integrity-monitor) · [Python file automation](https://github.com/bajily/automation-workbench) · [Python terminal game](https://github.com/bajily/Python-game)

## الأمن السيبراني والبرمجة والأتمتة

أنا أنس، مهتم بالأمن السيبراني والبرمجة باستخدام Python. يضم هذا الحساب 20 مشروعًا دفاعيًا لفحص الصلاحيات والسحابة والشبكات والحاويات وسلسلة توريد البرمجيات، وتحليل السجلات والتصيّد ومؤشرات التهديد والتخطيط للاستجابة للحوادث.

لكل مشروع كود قابل للتشغيل، ومدخلات وسياسات موثقة، وأمثلة تجريبية واختبارات. يلزم تقييم الأدوات على بيئة الشركة قبل الاعتماد التشغيلي عليها.
