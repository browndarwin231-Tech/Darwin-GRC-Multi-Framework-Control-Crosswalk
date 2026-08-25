# Cross-Framework GRC Findings

## Purpose

This document summarizes key findings from the simulated multi-framework control crosswalk for Orion Digital Services.

The review compares common control themes across SOC 2, ISO 27001, NIST CSF 2.0, NIST SP 800-53, PCI DSS, HIPAA, and GDPR.

The goal is to identify where controls can be reused across frameworks, where evidence can be shared, and where framework-specific gaps still require separate treatment.

---

## Finding 1: Access Control Has Strong Cross-Framework Overlap

### Observation

User access management appears across all reviewed frameworks.

### Shared Objective

Access should be:

- Authorized
- Appropriate
- Reviewed
- Removed when no longer needed

### Common Evidence

- Access requests
- Manager approvals
- User inventories
- Termination records
- Access reviews

### Risk

Weak access governance can affect multiple compliance programs at once.

### Recommendation

Use a centralized access-control process with standardized evidence retention.

---

## Finding 2: Privileged Access Requires Stronger Governance

### Observation

Privileged access maps strongly across all major frameworks.

### Gap

Some privileged accounts lack current business justification or recurring review evidence.

### Risk Level

**High**

### Business Impact

Excessive privileged access can increase the risk of unauthorized changes, data exposure, or account compromise.

### Recommendation

Perform quarterly privileged-access reviews and require:

- Business justification
- Manager approval
- Role validation
- MFA
- Removal of unnecessary permissions
- Retained review evidence

---

## Finding 3: MFA Is Common but Not Identical Across Frameworks

### Observation

MFA is relevant across multiple frameworks but applicability varies.

### Risk

Treating MFA requirements as identical across every framework may lead to inaccurate control mapping.

### Recommendation

Define MFA scope based on:

- Privileged access
- Remote access
- Sensitive systems
- Regulatory requirements
- Organizational risk

---

## Finding 4: Audit Logging Evidence Can Be Reused

### Observation

Logging and monitoring requirements appear across most frameworks.

### Reusable Evidence

- SIEM reports
- Log-source inventory
- Review records
- Investigation tickets
- Escalation documentation

### Gap

Recurring review evidence is inconsistent.

### Risk Level

**Medium**

### Recommendation

Create one standardized log-review process and retain evidence in a centralized repository.

---

## Finding 5: Vulnerability Management Is a High-Value Common Control

### Observation

Vulnerability management has strong overlap across the reviewed frameworks.

### Gap

Some high-risk vulnerabilities exceed remediation timelines.

### Risk Level

**High**

### Business Impact

Known vulnerabilities may remain exploitable and create issues across multiple compliance programs.

### Recommendation

Implement severity-based remediation SLAs and formal risk acceptance for exceptions.

---

## Finding 6: Incident Response Is Broadly Reusable

### Observation

Incident response requirements appear across all frameworks reviewed.

### Common Evidence

- Incident response plan
- Incident tickets
- Investigation records
- Escalation evidence
- Tabletop exercises
- Lessons learned

### Gap

Incident testing is not performed consistently.

### Risk Level

**High**

### Recommendation

Conduct recurring tabletop exercises and track lessons learned through corrective action.

---

## Finding 7: Third-Party Risk Has Strong Multi-Industry Relevance

### Observation

Third-party risk appears across security, privacy, healthcare, payment, and general compliance frameworks.

### Gap

High-risk vendors are not always reassessed on schedule.

### Risk Level

**High**

### Business Impact

Changes in vendor security posture may remain unidentified.

### Recommendation

Use a risk-tiered third-party review process with recurring reassessment.

---

## Finding 8: Privacy Controls Do Not Map Cleanly to Security Frameworks

### Observation

Privacy requirements have partial overlap with general cybersecurity controls.

### Examples of Privacy-Specific Topics

- Lawful basis
- Data subject rights
- Privacy notices
- Data minimization
- DPIAs
- Retention rules

### Risk

A security-only control library may miss privacy obligations.

### Recommendation

Maintain dedicated privacy controls while linking shared security controls where appropriate.

---

## Finding 9: Data Retention Requires Framework-Specific Review

### Observation

Retention appears across multiple frameworks but requirements vary by:

- Data type
- Industry
- Law
- Contract
- Business need

### Gap

Retention rules are inconsistently documented.

### Risk Level

**Medium**

### Recommendation

Create a centralized retention schedule with owners, review dates, and disposal rules.

---

## Finding 10: Evidence Reuse Can Reduce Compliance Work

### Observation

The same evidence may support multiple frameworks.

### Examples

One access review may support:

- SOC 2
- ISO 27001
- NIST
- PCI DSS
- HIPAA
- GDPR

### Risk

Evidence reuse becomes risky if reviewers assume one artifact automatically satisfies every framework.

### Recommendation

Reuse evidence only after confirming that it meets the scope and intent of each framework.

---

## Finding 11: Remediation Tracking Is a Shared Governance Need

### Observation

All frameworks benefit from consistent issue tracking and closure validation.

### Gap

Some findings may close without sufficient validation evidence.

### Risk Level

**High**

### Recommendation

Require:

- Owner
- Due date
- Corrective action
- Validation evidence
- Independent review
- Closure approval

---

## Finding 12: Common Controls Can Reduce Duplication

### Observation

Many controls support multiple frameworks.

### Examples

- Access control
- MFA
- Logging
- Vulnerability management
- Incident response
- Risk assessment
- Vendor risk
- Policy management

### Benefit

A common control library can reduce duplicate testing and documentation.

### Recommendation

Maintain one control owner and one primary evidence source where possible, then map that control to multiple frameworks.

---

## Finding 13: Crosswalks Must Avoid False Equivalence

### Observation

Similar wording does not mean two requirements are identical.

### Risk

Poor mappings may create false confidence and inaccurate compliance claims.

### Recommendation

Crosswalks should document:

- Shared objective
- Framework differences
- Evidence applicability
- Scope
- Specific gaps

---

## Finding 14: Centralized Evidence Management Improves Audit Readiness

### Observation

Evidence is currently spread across multiple locations.

### Risk Level

**Medium**

### Business Impact

Audit preparation may take longer and supporting evidence may be missed.

### Recommendation

Create a centralized evidence repository with:

- Naming standards
- Owners
- Review dates
- Retention periods
- Version control

---

## Key Findings Summary

| Finding Area | Risk Level |
|---|---|
| User Access | High |
| Privileged Access | High |
| MFA | High |
| Logging | Medium |
| Vulnerability Management | High |
| Incident Response Testing | High |
| Third-Party Risk | High |
| Privacy Governance | High |
| Data Retention | Medium |
| Access Review | High |
| Remediation Tracking | High |
| Evidence Management | Medium |

---

## Final Conclusion

The cross-framework review shows that many security controls can be centralized and reused across multiple compliance programs.

However, effective crosswalking requires careful analysis of framework intent, scope, evidence expectations, and industry-specific requirements.

A strong common-control approach can reduce duplicated work while still preserving framework-specific obligations.

This is a simulated portfolio project and does not represent a real compliance engagement.
