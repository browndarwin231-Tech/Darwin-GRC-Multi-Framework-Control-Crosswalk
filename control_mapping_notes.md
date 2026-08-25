# Multi-Framework Control Mapping Notes

## Purpose

This document explains the mapping logic used in the simulated multi-framework GRC control crosswalk.

The goal is to show how related security and compliance objectives can support multiple frameworks without assuming that different standards are identical.

---

## Important Mapping Principle

A control marked as **Related** does not mean that the requirements are exactly the same.

It means the frameworks share a similar security, privacy, governance, or risk-management objective.

Each framework may still differ in:

- Scope
- Terminology
- Evidence expectations
- Implementation detail
- Industry context
- Regulatory obligation
- Audit criteria

---

## Mapping Methodology

Each common control was reviewed using the following process:

1. Define the common security objective
2. Identify related framework requirements
3. Compare purpose and scope
4. Identify differences
5. Determine reusable evidence
6. Assign an implementation owner
7. Identify framework-specific gaps
8. Document remediation needs

---

## Mapping Note 1: User Access Management

### Common Objective

Ensure user access is authorized, appropriate, reviewed, and removed when no longer required.

### Framework Relationships

**SOC 2**  
Logical access controls support protection of systems and information from unauthorized access.

**ISO 27001**  
Access-control practices support identity management, authentication, authorization, and access restriction.

**NIST CSF 2.0**  
Access management aligns primarily with the Protect function.

**NIST SP 800-53**  
AC-2 Account Management is a key related control.

**PCI DSS**  
Access controls are important for restricting access to cardholder-data environments.

**HIPAA**  
Access management supports protection of electronic protected health information.

**GDPR**  
Appropriate access controls support the security of personal data.

### Reusable Evidence

- Access requests
- Manager approvals
- User inventory
- Termination records
- Access review reports

---

## Mapping Note 2: Privileged Access

### Common Objective

Limit elevated access to authorized users with legitimate business need.

### Key Differences

Frameworks generally support least privilege, but implementation expectations may vary depending on:

- System sensitivity
- Environment risk
- Data classification
- Industry requirements
- Internal policy

### Reusable Evidence

- Privileged account inventory
- Business justification
- Access-review reports
- Approval records
- Access-removal evidence

---

## Mapping Note 3: Multi-Factor Authentication

### Common Objective

Use stronger authentication to reduce credential-based access risk.

### Mapping Consideration

MFA expectations may differ across frameworks and environments.

A crosswalk should not assume that every framework requires MFA in exactly the same circumstances.

Instead, the evaluator should determine:

- Who requires MFA
- What systems are in scope
- Whether privileged access is involved
- Whether remote access is involved
- Whether regulatory requirements apply

### Reusable Evidence

- MFA enrollment report
- Authentication policies
- Configuration screenshots
- Exception records

---

## Mapping Note 4: Security Awareness

### Common Objective

Ensure personnel understand security responsibilities and relevant threats.

### Shared Themes

Common themes include:

- Recurring awareness
- Role-based training when appropriate
- Phishing awareness
- Policy acknowledgment
- Training records

### Reusable Evidence

- Training completion reports
- Awareness materials
- Employee acknowledgments
- Phishing simulation results

---

## Mapping Note 5: Audit Logging

### Common Objective

Generate, retain, review, and investigate security-relevant events.

### Mapping Consideration

Logging requirements vary based on:

- System type
- Risk
- Data sensitivity
- Retention requirements
- Investigation needs

### Reusable Evidence

- SIEM dashboards
- Log-source inventory
- Log-review reports
- Incident tickets
- Retention settings

---

## Mapping Note 6: Change Management

### Common Objective

Ensure system changes are authorized, tested, documented, and approved.

### Common Evidence

- Change requests
- Test results
- Approvals
- Implementation logs
- Emergency-change documentation

### Mapping Risk

A common mistake is assuming a successful implementation proves that the control operated correctly.

Control effectiveness should be supported by process evidence.

---

## Mapping Note 7: Vulnerability Management

### Common Objective

Identify, prioritize, remediate, and track vulnerabilities.

### Common Elements

- Vulnerability scanning
- Severity classification
- Remediation timelines
- Exception handling
- Risk acceptance
- Closure evidence

### Reusable Evidence

- Scan reports
- Remediation tickets
- Aging reports
- Risk acceptance approvals

---

## Mapping Note 8: Incident Response

### Common Objective

Prepare for, identify, contain, investigate, recover from, and learn from security incidents.

### Shared Evidence

- Incident response plan
- Incident tickets
- Investigation notes
- Escalation records
- Tabletop reports
- Lessons learned

### Mapping Consideration

Some frameworks focus more heavily on documentation while others emphasize organizational capability or regulatory notification.

---

## Mapping Note 9: Risk Assessment

### Common Objective

Identify threats, vulnerabilities, likelihood, impact, and treatment decisions.

### Cross-Framework Difference

Risk methodology may differ, but strong risk documentation generally includes:

- Risk description
- Likelihood
- Impact
- Risk rating
- Owner
- Treatment decision
- Target date
- Residual risk

---

## Mapping Note 10: Third-Party Risk

### Common Objective

Understand and manage risk introduced by vendors, suppliers, and service providers.

### Common Evidence

- Security questionnaires
- Risk assessments
- Contracts
- Compliance reports
- Reassessment records
- Remediation tracking

### Framework-Specific Considerations

Different industries may place additional requirements on vendors handling:

- Payment-card data
- Health information
- Personal data
- Government information

---

## Mapping Note 11: Encryption

### Common Objective

Protect sensitive information from unauthorized disclosure.

### Mapping Consideration

Encryption requirements may differ depending on:

- Data type
- Data location
- Transmission method
- Storage method
- Regulatory scope

### Reusable Evidence

- TLS settings
- Encryption standards
- Key-management documentation
- Configuration screenshots

---

## Mapping Note 12: Backup and Recovery

### Common Objective

Ensure systems and data can be restored after disruption.

### Common Evidence

- Backup reports
- Restoration tests
- Recovery logs
- Failure tickets
- Recovery procedures

### Key Distinction

A successful backup job does not automatically prove recoverability.

Restoration testing provides stronger evidence.

---

## Mapping Note 13: Policy Management

### Common Objective

Ensure security and compliance policies are documented, approved, communicated, and reviewed.

### Reusable Evidence

- Current policies
- Approval records
- Revision history
- Review dates
- Employee acknowledgments

---

## Mapping Note 14: Asset Management

### Common Objective

Maintain visibility into systems, applications, devices, and information assets.

### Reusable Evidence

- Asset inventory
- Ownership records
- Classification
- Lifecycle status
- Review records

---

## Mapping Note 15: Data Protection

### Common Objective

Protect sensitive and regulated information throughout its lifecycle.

### Framework Differences

Data-protection requirements vary significantly between frameworks.

For example:

- PCI DSS focuses on payment-card information
- HIPAA focuses on protected health information
- GDPR focuses on personal data
- Security frameworks may focus more broadly on confidentiality and integrity

---

## Mapping Note 16: Privacy Governance

### Common Objective

Establish accountability and processes for handling personal information.

### Key Consideration

Privacy controls do not always map cleanly to security-only frameworks.

Privacy-specific obligations may include:

- Data subject rights
- Lawful basis
- Privacy notices
- Data minimization
- Retention
- DPIAs

These may require additional controls beyond general cybersecurity requirements.

---

## Mapping Note 17: Data Retention

### Common Objective

Retain information for an appropriate period and securely dispose of it when no longer required.

### Reusable Evidence

- Retention schedule
- Deletion records
- Disposal procedures
- Legal-hold documentation

---

## Mapping Note 18: Access Review

### Common Objective

Periodically verify that existing access remains appropriate.

### Evidence

- Access certification report
- Reviewer decision
- Business justification
- Removal evidence
- Review completion record

---

## Mapping Note 19: Remediation Tracking

### Common Objective

Track identified weaknesses until corrective actions are implemented and validated.

### Reusable Evidence

- Audit finding tracker
- POA&M
- Corrective-action plan
- Validation evidence
- Closure approval

---

## Evidence Reuse Principle

Evidence may support multiple frameworks when it genuinely demonstrates the related control objective.

For example, one privileged-access review may support:

- SOC 2 logical access testing
- ISO 27001 access-control evidence
- NIST control assessment
- PCI DSS access review
- HIPAA security controls
- GDPR security measures

However, the reviewer must still verify that the evidence meets each framework's specific scope and requirements.

---

## Crosswalk Risk

Poor crosswalking can create false confidence.

Common problems include:

- Mapping controls based only on similar wording
- Assuming equivalent scope
- Ignoring framework-specific requirements
- Treating security and privacy controls as identical
- Reusing evidence without validating applicability

---

## Final Mapping Principle

The goal of a control crosswalk is not to claim that one control automatically satisfies every framework.

The goal is to identify shared control objectives, reduce duplicated work, improve evidence reuse, and identify where additional framework-specific controls are still required.

This is a simulated portfolio project created for learning and demonstration purposes.
