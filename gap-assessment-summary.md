# Gap Assessment Summary

## Project Overview

This project demonstrates a simulated NIST CSF and RMF-aligned control assessment performed against a Windows 11 virtual machine using:

- SCAP Compliance Checker (SCC)
- STIG Viewer
- Windows Event Viewer
- Microsoft Windows 11 STIG Benchmark

The purpose of this assessment was to identify security control gaps, validate audit logging configurations, review STIG compliance posture, and document remediation activities through a POA&M process.

---

# Assessment Scope

## In Scope

- Windows 11 Pro Virtual Machine
- Local Security Policy
- Windows Event Logging
- Audit Policy Configuration
- SCC STIG Compliance Scan
- STIG Viewer Checklist Review

## Assessment Objectives

- Validate implementation of security controls
- Identify non-compliant configurations
- Map findings to NIST 800-53 controls
- Document remediation recommendations
- Demonstrate continuous monitoring activities

---

# Tools Used

| Tool | Purpose |
|---|---|
| SCAP Compliance Checker (SCC) | Automated STIG compliance scanning |
| STIG Viewer 3.7 | Review and manage STIG checklist findings |
| Windows Event Viewer | Validate audit logging and event generation |
| GitHub | Documentation and evidence repository |

---

# Key Findings

## Audit Logging Gaps

Several audit policy settings were either missing or improperly configured during the assessment.

### Related Controls
- AU-2
- AU-6
- AU-12

### Evidence
- Event ID 4624 successful logon events
- Windows Security Logs
- SCC scan findings

### Risk
Insufficient logging reduces visibility into unauthorized activity, failed logon attempts, and suspicious behavior.

### Recommendation
Enable advanced audit policies and centralize logs to a SIEM platform for monitoring and alerting.

---

## Password Policy Weaknesses

The SCC scan identified multiple password policy failures.

### Related Controls
- IA-5
- AC-2

### Risk
Weak password controls increase the likelihood of credential compromise and unauthorized access.

### Recommendation
Implement:
- Minimum password length requirements
- Password complexity enforcement
- Account lockout thresholds

---

## BitLocker Encryption Not Enabled

Disk encryption requirements failed during the STIG assessment.

### Related Controls
- SC-28
- MP-6

### Risk
Unencrypted systems increase exposure to data theft if systems are lost or compromised.

### Recommendation
Enable BitLocker with TPM and PIN protection.

---

# Assessment Results Summary

| Category | Result |
|---|---|
| Total Rules Reviewed | 223 |
| Open Findings | 128 |
| Not A Finding | 85 |
| Not Applicable | 10 |
| Compliance Score | 39.91% |

---

# RMF Alignment

This assessment supports several RMF activities:

| RMF Step | Activity |
|---|---|
| Categorize | Identify systems and data types |
| Select | Identify applicable controls |
| Implement | Configure technical safeguards |
| Assess | Perform SCC and STIG validation |
| Authorize | Support risk-based decision making |
| Monitor | Track findings and remediation |

---

# Continuous Monitoring Activities

The following continuous monitoring activities were demonstrated:

- Reviewing audit logs
- Monitoring Event ID 4624 logon events
- Running automated SCC scans
- Reviewing STIG compliance findings
- Tracking remediation activities in POA&M documentation

---

# Conclusion

This project demonstrates practical exposure to:

- NIST CSF concepts
- RMF processes
- STIG assessments
- SCC scanning
- Security control mapping
- POA&M management
- Continuous monitoring operations

The assessment identified several security gaps requiring remediation and provided documented evidence supporting cybersecurity compliance and governance activities.
