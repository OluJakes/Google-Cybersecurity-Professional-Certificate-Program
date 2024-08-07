Here's a revised version of your security audit writeup, rephrased to avoid plagiarism:

---

# Botium Toys Security Audit Report

## Table of Contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Internal Security Audit Workflow](#internal-security-audit-workflow)
4. [Controls Assessment](#controls-assessment)
5. [Compliance Checklist](#compliance-checklist)
6. [Stakeholder Memorandum](#stakeholder-memorandum)
7. [Conclusion](#conclusion)

## Introduction

This internal security audit for Botium Toys—a fictional toy company—was conducted as part of my cybersecurity portfolio and as a component of Google's Cybersecurity Professional Certificate on Coursera, specifically within the Play It Safe: Manage Security Risks course.

The objective of this audit is to evaluate Botium Toys’ cybersecurity framework. This involves aligning their current business practices with industry standards and best practices. The audit aims to identify vulnerabilities classified as “high risk” and provide recommendations for enhancing the company’s security posture. The audit team is tasked with documenting findings, suggesting remediation strategies, and communicating results to stakeholders.

## Scenario

Botium Toys, a small U.S.-based toy company, operates from a single physical location. However, its expanding online presence has attracted a global customer base. The company’s IT department faces increasing demands to support international operations.

The IT manager has initiated an internal IT audit due to concerns about the lack of a comprehensive plan for business continuity and compliance amidst the company’s growth. The manager believes that an internal audit will enhance the security of their infrastructure and help identify and address potential risks, threats, or vulnerabilities affecting critical assets. Additionally, the manager is keen on ensuring compliance with regulations governing online payments and business operations within the European Union (E.U.).

The audit's goals are as follows:
- Implement the National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)
- Improve compliance processes
- Strengthen system controls
- Apply the principle of least privilege to user credential management
- Develop and formalize policies and procedures
- Ensure adherence to compliance requirements

## Internal Security Audit Workflow

The internal security audit is divided into two main parts, each with distinct steps:

### Part 1

1. Review the audit scope, goals, and risk assessment.
2. Conduct the audit.
3. Complete the controls assessment.
4. Identify and prioritize controls that need implementation.
5. Finalize the compliance checklist.
6. Justify the necessity of adhering to selected compliance regulations and standards.

### Part 2

1. Review and assess the results and deliverables from Part 1.
2. Document findings.
3. Summarize recommendations clearly for stakeholders.
4. Communicate findings and recommendations to stakeholders in a concise format.

## Controls Assessment

### Current Assets

The IT Department manages the following assets:

- **On-premises equipment** for office operations.
- **Employee equipment** including desktops, laptops, smartphones, remote workstations, and various peripherals.
- **Systems, software, and services** such as accounting, telecommunication, database, security, ecommerce, and inventory management.
- **Internet access** and **internal network**.
- **Vendor access management** and **data center hosting services**.
- **Data retention and storage**.
- **Legacy system maintenance** for end-of-life systems.

### Administrative Controls

| Control Name                  | Control Type and Explanation                                                         | Needs to be Implemented (X) | Priority |
|-------------------------------|----------------------------------------------------------------------------------------|------------------------------|----------|
| Least Privilege               | Preventive; limits access to only what is necessary for job functions                   | X                            | High     |
| Disaster Recovery Plans       | Corrective; ensures business continuity and minimal downtime in case of incidents       | X                            | High     |
| Password Policies             | Preventive; establishes rules for password strength to enhance security                 | X                            | High     |
| Access Control Policies       | Preventive; protects data confidentiality and integrity                                 | X                            | High     |
| Account Management Policies   | Preventive; minimizes risk from disgruntled/former employees                            | X                            | High     |
| Separation of Duties          | Preventive; prevents abuse of access rights by ensuring no single person has excessive control | X                            | High     |

### Technical Controls

| Control Name                  | Control Type and Explanation                                                         | Needs to be Implemented (X) | Priority |
|-------------------------------|----------------------------------------------------------------------------------------|------------------------------|----------|
| Firewall                      | Preventive; filters unwanted or malicious traffic                                      | NA                           | NA       |
| Intrusion Detection System (IDS) | Detective; identifies potential intrusions quickly                                   | X                            | High     |
| Encryption                    | Deterrent; secures confidential information (e.g., payment transactions)                | X                            | High     |
| Backups                       | Corrective; ensures data and productivity continuity                                    | X                            | High     |
| Password Management System    | Corrective; assists with password recovery, reset, and notifications                     | X                            | High     |
| Antivirus (AV) Software       | Corrective; detects and quarantines threats                                            | X                            | High     |
| Manual Monitoring and Maintenance | Preventive/Corrective; required for legacy systems to address threats and vulnerabilities | X                            | High     |

### Physical Controls

| Control Name                  | Control Type and Explanation                                                         | Needs to be Implemented (X) | Priority |
|-------------------------------|----------------------------------------------------------------------------------------|------------------------------|----------|
| Time-controlled Safe          | Deterrent; reduces impact of physical threats                                         | X                            | Medium/Low |
| Adequate Lighting             | Deterrent; reduces potential hiding spots                                              | X                            | Medium/Low |
| Closed-circuit Television (CCTV) | Preventive/Detective; monitors and investigates physical threats                      | X                            | High/Medium |
| Locking Cabinets              | Preventive; secures network gear from unauthorized access                               | X                            | High/Medium |
| Signage for Alarm Service     | Deterrent; reduces likelihood of successful attacks                                    | X                            | Low      |
| Locks                         | Preventive; enhances security of physical and digital assets                           | X                            | High     |
| Fire Detection and Prevention | Detective/Preventive; safeguards against fire-related damage                            | X                            | Medium    |

## Compliance Checklist

Botium Toys must adhere to the following standards:

### General Data Protection Regulation (GDPR)

GDPR, a regulation by the European Union, safeguards the processing of E.U. citizens' data and their privacy rights. In case of a data breach involving E.U. citizens, notification within 72 hours is required. As Botium Toys expands globally, GDPR compliance is crucial for handling financial and personal data of E.U. customers.

### Payment Card Industry Data Security Standard (PCI DSS)

PCI DSS is an international standard ensuring the secure handling of credit card information. Non-compliance can result in significant financial penalties, forensic audit costs, brand damage, and potential legal action. Botium Toys must comply with PCI DSS due to its online payment acceptance and international data processing.

### System and Organization Controls (SOC) Type 1 and Type 2

SOC 1 and SOC 2 reports assess user access policies and overall data safety. SOC 1 focuses on financial reporting controls, while SOC 2 evaluates information security controls. Compliance with these standards is essential for mitigating risks and ensuring data safety.

## Stakeholder Memorandum

**To:** IT Manager and Stakeholders  
**From:** Chris Jabbour  
**Date:** 06/09/2023  
**Subject:** Internal IT Audit Findings and Recommendations

Dear Colleagues,

Below is a summary of the internal audit findings for Botium Toys, including scope, goals, key issues, and recommendations.

### Scope

The audit covered systems including accounting, endpoint detection, firewalls, IDS, and SIEM tools. Evaluation included:
- User permissions
- Implemented controls
- Procedures and protocols
- Compliance with GDPR, PCI DSS, and other standards
- Technology and asset inventory

### Goals

- Implement the NIST CSF.
- Enhance system compliance.
- Strengthen system controls.
- Apply least privilege principles.
- Develop and formalize policies and procedures.
- Ensure compliance with relevant regulations.

### Critical Findings

Immediate attention required for:
- Implementation of Least Privilege and Separation of Duties
- Development of Disaster Recovery Plans
- Enforcement of Password, Access Control, and Account Management Policies
- Integration of an Intrusion Detection System (IDS) and Encryption
- Establishment of Backups and a Password Management System
- Manual Monitoring and Maintenance for Legacy Systems
- Enhancement of Physical Security Measures (e.g., CCTV, Locks)

### Recommendations

Addressing compliance issues related to PCI DSS and GDPR is crucial as Botium Toys expands internationally. Implement SOC1 and SOC2 guidelines to enhance user access controls and data safety.

Develop and implement disaster recovery plans and backups to support business continuity. Integrating IDS and AV software will improve threat detection and response. Strengthen physical security measures to protect assets.

### Findings for Future Consideration

Future improvements could include:
- Time-controlled safe
- Improved lighting
- Signage for alarm service providers

## Conclusion

This audit report concludes with a comprehensive overview of the current security posture and recommendations for improvements. I hope this analysis proves valuable. Feedback and suggestions for further enhancements are welcome.

**Self-Evaluation:** I found the task of identifying priority controls and understanding regulatory requirements challenging but rewarding. Improving the clarity and conciseness of my findings was a key learning experience. Understanding the broader implications of SOC standards on organizational policies was also an insightful aspect of this audit.

---
