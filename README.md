# NIST CSF Control Mapping Lab

## Overview

This project demonstrates a simulated cybersecurity compliance assessment aligned with:

- NIST Cybersecurity Framework (CSF)
- NIST RMF
- NIST SP 800-53
- DISA STIG methodologies

The lab focuses on security control validation, STIG compliance scanning, audit logging review, gap assessment activities, and POA&M remediation tracking using a Windows 11 virtual machine.

---

# Objectives

The purpose of this project was to:

- Perform a STIG-based compliance assessment
- Review Windows audit logging configurations
- Identify security gaps and weaknesses
- Map technical findings to NIST 800-53 controls
- Create remediation tracking documentation
- Demonstrate continuous monitoring processes

---

# Technologies and Tools Used

| Tool | Purpose |
|---|---|
| Windows 11 Pro VM | Assessment target |
| SCAP Compliance Checker (SCC) | Automated compliance scanning |
| STIG Viewer 3.7 | STIG checklist analysis |
| Windows Event Viewer | Audit log validation |
| GitHub | Documentation repository |

---

# Assessment Activities

## Windows System Validation

- Verified hostname
- Reviewed OS version and system specifications
- Documented VM configuration

## Audit Log Review

Validated:
- Security logs
- Event ID 4624 successful logons
- Audit policy configurations

## SCC Compliance Scan

Performed automated STIG compliance scanning against:
- Windows 11 STIG Benchmark
- Microsoft Defender
- Windows Firewall
- Windows Updates

## STIG Viewer Analysis

Imported SCC scan results into STIG Viewer and reviewed:
- CAT I findings
- CAT II findings
- CAT III findings
- Compliance score
- Open vulnerabilities

## Control Mapping

Mapped technical findings to NIST 800-53 controls including:

- AU-2
- AU-6
- AU-12
- AC-2
- IA-5
- SC-28
- CM-8

## POA&M Tracking

Documented:
- Findings
- Severity levels
- Remediation recommendations
- Milestones
- Status tracking

---

# Repository Structure

```text
nist-csf-control-mapping-lab/
│
├── README.md
├── control-mapping-matrix.xlsx
├── gap-assessment-summary.md
├── poam-tracker.xlsx
│
├── screenshots/
│   ├── 07-windows-vm-info.png
│   ├── 10-event-viewer-security-logs.png
│   ├── 11-event-id-4624-successful-logon.png
│   ├── 13-scc-scan-results.png
│   ├── 14-scc-open-findings.png
│   ├── 15-stig-viewer-results-imported.png
│   └── 16-scc-generated-results-files.png
│
└── templates/
