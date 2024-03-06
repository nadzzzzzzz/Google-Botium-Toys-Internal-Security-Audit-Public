# Google-Botium-Toys-Internal-Security-Audit-Public

# Table of Contents

1. [Executive Summary](#executive-summary)
2. [Introduction](#introduction)
3. [Methodology](#methodology)
4. [Current Assets](#current-assets)
5. [Risk Assessment](#risk-assessment)
6. [Control Categories and Types](#control-categories-and-types)
7. [Findings and Recommendations](#findings-and-recommendations)
8. [Conclusion](#conclusion)
9. [Appendices](#appendices)

# Introduction <a name="introduction">

An internal security audit assessment done on Botium Toys, a fictitious toy company, completed as part of my cybersecurity portfolio and as part of Google's <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a> on Coursera in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> Play It Safe: Manage Security Risks </a> Course .
   
The goal is to perform an audit of Botium Toys’ cybersecurity program. The audit needs
to align current business practices with industry standards and best practices. The
audit is meant to provide mitigation recommendations for vulnerabilities found that are
classified as “high risk,” and present an overall strategy for improving the security
posture of the organization. The audit team needs to document their findings, provide
remediation plans and efforts, and communicate with stakeholders.

# Botium Toys Security Audit Documentation

## Scope and Goals of the Audit

### Scope
The scope of this audit encompasses the entire security program at Botium Toys. This includes all assets along with internal processes and procedures related to the implementation of controls and compliance with best practices.

### Goals
- To assess the existing assets.
- To complete the controls and compliance checklist.
- To identify the necessary controls and compliance best practices that need to be implemented to improve Botium Toys' security posture.

## Current Assets

Assets managed by the IT Department include:
- On-premises equipment for in-office business needs.
- Employee equipment, including:
  - End-user devices (desktops/laptops, smartphones).
  - Remote workstations, headsets, cables, keyboards, mice, docking stations.
  - Surveillance cameras.
- Storefront products available for retail sale on site and online, stored in the company's adjoining warehouse.
- Management of systems, software, and services, including accounting, telecommunication, database security, e-commerce, and inventory management.
- Internet access.
- Internal network.
- Data retention and storage.
- Legacy system maintenance: end-of-life systems that require human monitoring.

## Risk Assessment

### Risk Description
There is inadequate management of assets at Botium Toys, and the company may not be fully compliant with U.S. and international regulations and standards.

### Control Best Practices
Botium Toys should dedicate resources to:
- Identify assets to appropriately manage them.
- Classify existing assets and determine the impact of their loss on business continuity, in line with the first function of the NIST CSF, which is "Identify".

### Risk Score
The risk score is 8 out of 10, indicating a fairly high level of risk due to a lack of controls and adherence to compliance best practices.

### Additional Comments
The potential impact from the loss of an asset is rated medium, as the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high due to the lack of necessary controls and non-adherence to compliance regulations.

#### Specific Details:
- All employees have access to internally stored data, including cardholder data and customers’ PII/SPII.
- Lack of encryption for customer credit card information.
- Access controls and separation of duties are not properly implemented.
- Availability and data integrity controls are in place.
- A firewall and antivirus software are installed and monitored.
- No intrusion detection system (IDS) is installed.
- Lack of disaster recovery plans and backups of critical data.
- Notification plan for E.U. customers in the event of a security breach is in place.
- Privacy policies, procedures, and processes are developed and enforced.
- The existing password policy does not meet current minimum complexity requirements.
- No centralized password management system.
- Legacy systems are monitored but lack a regular schedule for maintenance.
- Physical security measures (locks, CCTV, fire detection, and prevention systems) are sufficient at the physical store location.

## Conclusion
This document outlines the scope, goals, current assets, and risk assessment of the security audit at Botium Toys. To improve the company's security posture, it is imperative to address the highlighted risks and implement the suggested control best practices.

# Security Audit Report for Botium Toys

## Table of Contents

- [Introduction](#introduction)
  - [Scope and Goals of the Audit](#scope-and-goals-of-the-audit)
  - [Current Assets](#current-assets)
- [Risk Assessment](#risk-assessment)
- [Control Categories and Types](#control-categories-and-types)
  - [Administrative/Managerial Controls](#administrativemanagerial-controls)
  - [Technical Controls](#technical-controls)
  - [Physical/Operational Controls](#physicaloperational-controls)

## Introduction

This document outlines the findings and recommendations of the security audit conducted for Botium Toys. The audit encompasses a thorough review of the organization's entire security program, including an assessment of all assets alongside internal processes and procedures related to the implementation of controls and compliance best practices.

### Scope and Goals of the Audit

#### Scope
The scope is defined as the entire security program at Botium Toys. This includes all assets alongside internal processes and procedures related to the implementation of controls and compliance best practices.

#### Goals
- Assess existing assets
- Complete the controls and compliance checklist
- Determine which controls and compliance best practices need to be implemented to improve Botium Toys’ security posture

### Current Assets

Assets managed by the IT Department include, but are not limited to:
- On-premises equipment for in-office business needs
- Employee equipment (e.g., desktops/laptops, smartphones)
- Storefront products available for retail
- Management of systems, software, and services (e.g., accounting, telecommunication)
- Internet access and internal network
- Data retention and storage
- Legacy system maintenance

## Risk Assessment

Botium Toys currently faces a high level of risk (score: 8/10) due to inadequate asset management and insufficient controls and compliance with regulations and standards. The potential impacts from loss of assets are considered medium, while the risk to assets or fines from governing bodies is high.

## Control Categories and Types

### Administrative/Managerial Controls

These controls address the human component of cybersecurity through policies and procedures that define how an organization manages data and employee responsibilities.

| Control Name              | Control Type | Control Purpose                                                                 | Need | Priority |
|---------------------------|--------------|---------------------------------------------------------------------------------|------|----------|
| Least Privilege           | Preventative | Reduce risk and overall impact of malicious insider or compromised accounts     | Yes  | High     |
| Disaster recovery plans   | Corrective   | Provide business continuity                                                     | Yes  | High     |
| Password policies         | Preventative | Reduce likelihood of account compromise                                         | Yes  | High     |
| Access control policies   | Preventative | Bolster confidentiality and integrity by defining data access                   | Yes  | High     |
| Account management policies | Preventative | Managing account lifecycle to reduce attack surface                             | Yes  | High     |
| Separation of duties      | Preventative | Reduce risk and impact of malicious insider or compromised accounts             | Yes  | High     |

### Technical Controls

Technical solutions such as firewalls, IDS/IPS, and encryption are utilized to meet organizational security objectives.

| Control Name                | Control Type | Control Purpose                                     | Need | Priority |
|-----------------------------|--------------|-----------------------------------------------------|------|----------|
| Firewall                    | Preventative | Filter unwanted or malicious traffic                | No   | Low      |
| IDS/IPS                     | Detective    | Detect and prevent anomalous traffic                | Yes  | High     |
| Encryption                  | Deterrent    | Provide confidentiality to sensitive information    | Yes  | High     |
| Backups                     | Corrective   | Restore/recover from an event                       | Yes  | High     |
| Password management         | Preventative | Reduce password fatigue                             | Yes  | High     |
| Antivirus (AV) software     | Preventative | Scan to detect and quarantine known threats         | Yes  | High     |
| Manual monitoring, maintenance, and intervention | Preventative | Identify and manage threats to outdated systems     | Yes  | High     |

### Physical/Operational Controls

Physical controls are used to limit physical access to assets by unauthorized personnel.

| Control Name                  | Control Type          | Control Purpose                                                   | Need | Priority |
|-------------------------------|-----------------------|-------------------------------------------------------------------|------|----------|
| Time-controlled safe          | Deterrent             | Reduce attack surface from physical threats                       | Yes  | Low      |
| Adequate lighting             | Deterrent             | Deter threats by limiting “hiding” places                         | Yes  | Medium   |
| Closed-circuit television (CCTV) | Preventative/Detective | Reduce risk of certain events occurring; inform on event conditions| Yes  | High     |
| Locking cabinets (for network gear) | Preventative    | Prevent unauthorized access or modification of network gear       | Yes  | High     |
| Signage indicating alarm service provider | Deterrent | Deter threats by making the likelihood of a successful attack seem low | Yes  | Low      |
| Locks                          | Deterrent/Preventative| Deter and prevent unauthorized physical access                     | Yes  | High     |
| Fire detection and prevention | Detective/Preventative| Detect and prevent damage from fire                                | Yes  | Medium   |

This report provides a comprehensive overview of the current security posture of Botium Toys and offers specific recommendations for improving its overall security framework.

## Conclusion

The security audit conducted for Botium Toys has revealed significant areas of concern regarding the organization's current security posture. The high risk score of 8 out of 10 underscores the urgent need for a comprehensive strategy to address inadequate asset management, insufficient implementation of controls, and non-compliance with regulatory standards. The findings highlight critical vulnerabilities that could potentially lead to unauthorized access to sensitive data, disruption of business operations, and financial losses due to fines and reputational damage.

To mitigate these risks, Botium Toys must prioritize the implementation of recommended controls, focusing on both immediate and long-term security improvements. Key recommendations include enhancing asset management processes, adopting robust technical controls such as intrusion detection systems and encryption, and strengthening physical security measures. Additionally, fostering a culture of security awareness and compliance among employees through administrative controls is vital.

Implementing these changes will not only reduce the organization's risk profile but also build a stronger foundation for safeguarding against future threats. It is imperative that Botium Toys commits to ongoing evaluation and adaptation of its security practices to keep pace with evolving cyber threats and regulatory requirements.

In conclusion, this audit serves as a call to action for Botium Toys to reinforce its security measures and protect its assets, employees, and customers from potential threats. By addressing the identified issues and adopting a proactive approach to security, Botium Toys can achieve a resilient and compliant security posture that supports its business objectives and fosters trust among its stakeholders.
