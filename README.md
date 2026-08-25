# Darwin-GRC-Multi-Framework-Control-Crosswalk

## Project Overview

This project simulates a multi-framework Governance, Risk, and Compliance control-mapping exercise across several major security and privacy frameworks.

The goal is to identify common control themes, compare framework expectations, document overlap, identify gaps, and create a reusable common control library.

Frameworks included:

- SOC 2
- ISO 27001
- NIST CSF 2.0
- NIST SP 800-53
- PCI DSS
- HIPAA Security Rule
- GDPR

This project demonstrates how one security control may support multiple compliance requirements while still recognizing that each framework has different language, scope, and implementation expectations.

---

## Business Scenario

A fictional organization called **Orion Digital Services** operates across multiple industries and handles customer, employee, payment, and regulated data.

The organization is trying to reduce duplicated compliance work by mapping common security controls across multiple frameworks.

Instead of implementing completely separate controls for every framework, the GRC team wants to build a centralized common control library and understand where framework requirements overlap.

---

## Project Objectives

This project focuses on:

- Cross-framework control mapping
- Common control identification
- Framework overlap analysis
- Gap analysis
- Control ownership
- Evidence reuse
- Audit readiness
- Compliance efficiency
- Risk-based control design
- Remediation planning

---

## Control Areas Reviewed

The crosswalk focuses on common security and compliance areas including:

- Access control
- Privileged access
- Multi-factor authentication
- Security awareness training
- Audit logging
- Change management
- Vulnerability management
- Incident response
- Risk assessment
- Third-party risk
- Data protection
- Encryption
- Backup and recovery
- Policy management
- Asset management
- Privacy governance

---

## Crosswalk Methodology

Each control is reviewed using the following process:

1. Define the common security objective
2. Identify related requirements across frameworks
3. Compare differences in scope and intent
4. Identify reusable evidence
5. Assign a common control owner
6. Determine implementation status
7. Identify framework-specific gaps
8. Document remediation actions

---

## Framework Mapping Principle

This project does not assume that controls are identical across frameworks.

A mapped control indicates that the frameworks share a related security or compliance objective.

The exact requirement, scope, evidence, and implementation expectations may still differ.

---

## Example Crosswalk

| Common Control | SOC 2 | ISO 27001 | NIST CSF 2.0 | NIST SP 800-53 | PCI DSS | HIPAA | GDPR |
|---|---|---|---|---|---|---|---|
| Access Control | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| MFA | Yes | Yes | Yes | Yes | Yes | Related | Related |
| Audit Logging | Yes | Yes | Yes | Yes | Yes | Yes | Related |
| Incident Response | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| Risk Assessment | Yes | Yes | Yes | Yes | Yes | Yes | Yes |
| Third-Party Risk | Yes | Yes | Yes | Yes | Yes | Yes | Yes |

---

## Common Control Library

The project includes a reusable common control library containing:

- Common Control ID
- Control Name
- Control Objective
- Control Owner
- Framework Coverage
- Evidence Requirements
- Implementation Status
- Risk Level
- Gap Status
- Remediation Recommendation

---

## Evidence Reuse

Where appropriate, the same evidence may support multiple frameworks.

Examples include:

- Access review reports
- MFA configuration
- Security awareness completion reports
- Vulnerability scan reports
- Incident tickets
- Backup test results
- Vendor assessments
- Risk registers
- Policies
- Audit logs
- Change tickets

Evidence reuse can reduce duplicate compliance effort when the evidence genuinely supports multiple control objectives.

---

## Gap Analysis

The project identifies gaps such as:

- Control implemented for one framework but not another
- Evidence missing for one framework
- Scope differences
- Privacy-specific requirements
- Industry-specific requirements
- Incomplete control ownership
- Weak remediation tracking

---

## Repository Structure

Darwin-GRC-Multi-Framework-Control-Crosswalk/
│
├── README.md
├── multi_framework_control_crosswalk.csv
├── control_mapping_notes.md
├── framework_overlap_matrix.csv
├── common_control_library.csv
├── gap_analysis.csv
├── cross_framework_findings.md
├── remediation_plan.md
└── evidence/

---

## Skills Demonstrated

- GRC
- Multi-Framework Mapping
- Control Crosswalking
- SOC 2
- ISO 27001
- NIST CSF 2.0
- NIST SP 800-53
- PCI DSS
- HIPAA
- GDPR
- Control Rationalization
- Audit Evidence Reuse
- Gap Analysis
- Risk Assessment
- Control Ownership
- Remediation Planning
- Compliance Documentation

---

## Project Goal

The goal of this project is to demonstrate how GRC teams can reduce duplicated compliance effort by mapping shared control objectives across multiple frameworks while still accounting for framework-specific requirements.

This is a simulated portfolio project and does not represent compliance work performed for a real organization.
