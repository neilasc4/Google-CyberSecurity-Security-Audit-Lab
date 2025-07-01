# Botium Toys – Completed IT Audit Report

This report outlines the findings from Botium Toys’ internal security audit. It highlights where the company currently stands with its security controls and compliance practices and identifies areas that need improvement.

The audit looked at three key types of security controls—Administrative, Technical, and Physical—and checked how well Botium Toys is using each. It also reviews how the company is doing in meeting industry compliance standards like PCI DSS, GDPR, and SOC.

## Controls Assessment Summary

| Control | In Place? | Notes |
| --- | --- | --- |
| Least Privilege | No | All employees have access to internal data and cardholder information. |
| Disaster Recovery Plans | No | No disaster recovery or backup strategy implemented. |
| Password Policies | No | Policy exists but lacks complexity and enforcement. |
| Separation of Duties | No | No role-based access controls are in place. |
| Firewall | Yes | Firewall configured with defined rules. |
| Intrusion Detection System (IDS) | No | IDS has not been deployed. |
| Backups | No | No data backup or recovery system exists. |
| Antivirus Software | Yes | Installed and monitored regularly. |
| Legacy System Monitoring | No | Manual and inconsistent monitoring. |
| Encryption | No | Sensitive data is stored and transmitted without encryption. |
| Password Management System | No | No centralized system; causes productivity issues. |
| Locks | Yes | Sufficient locking mechanisms in place. |
| CCTV Surveillance | Yes | Operational closed-circuit surveillance systems. |
| Fire Detection/Prevention | Yes | Smoke detectors and fire suppression systems installed. |

## Compliance Checklist Summary

### PCI DSS

| Best Practice | In Place? | Notes |
| --- | --- | --- |
| Authorized access to cardholder data | No | All employees can access credit card information. |
| Secure storage and transmission of cardholder data | No | Environment lacks encryption and segregation. |
| Data encryption procedures implemented | No | Encryption not applied to payment data. |
| Secure password policies | No | Policies are not aligned with current standards. |

### GDPR

| Best Practice | In Place? | Notes |
| --- | --- | --- |
| Customer data privacy | No | PII/SPII stored in plaintext. |
| 72-hour breach notification | Yes | Policy and process confirmed. |
| Data classification and inventory | No | Not yet conducted. |
| Enforcement of privacy policies | Yes | Implemented by IT staff. |

### SOC Type 1 / 2

| Best Practice | In Place? | Notes |
| --- | --- | --- |
| User access policies | No | Lack of formal access control. |
| Confidentiality of sensitive data | No | Unrestricted access to SPII. |
| Data integrity | Yes | Controls ensure accurate and consistent data. |
| Data availability | Yes | System availability is adequate. |

## Recommendations

Here are a few practical steps the IT staff should consider:
- Limit access to sensitive data by setting up least privilege and separating duties between roles.
- Encrypt customer and payment information so it’s protected, both when stored and sent.
- Install an intrusion detection system (IDS) to spot suspicious activity early.
- Set up a reliable backup and disaster recovery plan so critical data isn’t lost in a breach.
- Use a password management tool to help staff create and use strong passwords without the hassle.
- Make a list of all sensitive data and label it properly so it’s easier to protect.
- Write down who can access what, and make sure those policies are followed.
