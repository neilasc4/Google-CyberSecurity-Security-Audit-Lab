# Botium Toys – Completed Security Audit Report

# Botium Toys – Completed Security Audit Report

This document summarizes the results of the internal IT audit for Botium Toys, based on the NIST Cybersecurity Framework (CSF), the company's current risk assessment, and the controls and compliance checklist. It addresses three primary control categories (Administrative, Technical, and Physical), evaluates each based on implementation status, and includes compliance analysis against PCI DSS, GDPR, and SOC standards.

## Controls Assessment Summary

## Compliance Checklist Summary

### PCI DSS

### GDPR

### SOC Type 1 / 2

## Recommendations

1. Implement least privilege and separation of duties to control data access.
2. Encrypt all sensitive data, including customer and payment information.
3. Deploy an Intrusion Detection System (IDS) to detect threats.
4. Establish and test a disaster recovery and data backup plan.
5. Introduce a secure password management system for all users.
6. Conduct full data classification and inventory to align with GDPR.
7. Define and enforce user access policies to support SOC compliance.

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

| Best Practice | In Place? | Notes |
| --- | --- | --- |
| Authorized access to cardholder data | No | All employees can access credit card information. |
| Secure storage and transmission of cardholder data | No | Environment lacks encryption and segregation. |
| Data encryption procedures implemented | No | Encryption not applied to payment data. |
| Secure password policies | No | Policies are not aligned with current standards. |

| Best Practice | In Place? | Notes |
| --- | --- | --- |
| Customer data privacy | No | PII/SPII stored in plaintext. |
| 72-hour breach notification | Yes | Policy and process confirmed. |
| Data classification and inventory | No | Not yet conducted. |
| Enforcement of privacy policies | Yes | Implemented by IT staff. |

| Best Practice | In Place? | Notes |
| --- | --- | --- |
| User access policies | No | Lack of formal access control. |
| Confidentiality of sensitive data | No | Unrestricted access to SPII. |
| Data integrity | Yes | Controls ensure accurate and consistent data. |
| Data availability | Yes | System availability is adequate. |
