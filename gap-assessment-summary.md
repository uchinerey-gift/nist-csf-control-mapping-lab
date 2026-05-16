# Gap Assessment Summary

## Overview
This gap assessment reviewed selected cybersecurity controls across NIST CSF, NIST 800-53, CIS Controls, and ISO 27001. The purpose was to identify control weaknesses, evidence gaps, and remediation priorities.

## Key Findings

### Finding 1: Asset Inventory Is Incomplete
The organization has a partial asset inventory, but it does not include all endpoints, owners, or criticality ratings.

Risk: Unknown or unmanaged assets may remain unpatched, unmonitored, or outside compliance scope.

Recommended Action: Implement a centralized asset inventory process and update it continuously.

### Finding 2: MFA Is Not Fully Enforced
MFA is enabled for administrators but not all standard users.

Risk: User accounts remain vulnerable to credential theft and unauthorized access.

Recommended Action: Enforce MFA for all users, especially remote access and privileged functions.

### Finding 3: Log Review Is Inconsistent
Logging is enabled, but evidence of consistent log review is incomplete.

Risk: Security events may go undetected or unresolved.

Recommended Action: Define log review procedures, assign ownership, and retain SIEM review evidence.

## Overall Conclusion
The organization has implemented several cybersecurity controls, but gaps remain in asset visibility, access control, MFA enforcement, and audit review. Remediation should be prioritized based on business impact and risk exposure.
