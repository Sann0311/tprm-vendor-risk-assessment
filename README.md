# TPRM Vendor Risk Assessment

I built this project to get deeper hands-on practice with the day-to-day work involved in third-party risk management.

My previous cybersecurity work has included vendor assessments, control testing, evidence validation, and security reviews. I wanted to take those pieces further and build a complete vendor risk workflow from intake through ongoing monitoring.

The project currently models three SaaS vendors with different levels of business and security risk.

## What I am covering

The assessment workflow includes:

* Vendor intake and inherent risk assessment
* Vendor tiering based on data sensitivity, system access, business criticality, regulatory exposure, and fourth-party dependencies
* CAIQ and SIG-aligned security due diligence
* Review of SOC 2, ISO 27001, penetration testing, BCP/DR, privacy, and security evidence
* Identification and documentation of vendor security risks
* Inherent and residual risk scoring
* Compensating control evaluation
* Remediation and risk acceptance tracking
* Fourth-party and subprocessor risk
* Continuous monitoring and reassessment triggers
* Executive-level TPRM metrics and reporting

## Current Work

The first version of the project is available in:

`TPRM_Vendor_Risk_Assessment.xlsx`

The workbook currently includes:

* Vendor Inventory
* Vendor Intake & Inherent Risk Assessment
* Vendor Tiering Model
* Security Questionnaire
* Evidence Review
* SOC 2 Review
* Risk Register
* Remediation Tracker
* Continuous Monitoring
* TPRM Dashboard

### Vendor scenarios

Three fictional vendors are used to demonstrate risk-based due diligence rather than applying the same assessment to every third party:

| Vendor        | Service                                             | Risk Level |
| ------------- | --------------------------------------------------- | ---------- |
| MetricFlow    | Cloud analytics platform with production API access | Critical   |
| PeopleSphere  | HR and payroll SaaS processing employee PII         | High       |
| CampaignPilot | Marketing automation platform                       | Medium     |

The scenarios and vendor information are fictional and created specifically for this project.

## Example Assessment Flow

A typical assessment in the project follows this sequence:

`Vendor Intake → Inherent Risk → Tiering → Security Due Diligence → Evidence Review → Findings → Residual Risk → Remediation / Risk Acceptance → Approval → Continuous Monitoring`

For higher-risk vendors, the assessment goes beyond questionnaire responses. Supporting evidence is reviewed to determine whether the stated controls are actually supported and whether additional follow-up is required.

For example, a vendor answering that MFA is implemented would not automatically result in an effective control rating. The assessment also considers where MFA is enforced, whether privileged accounts are covered, what evidence supports the response, and whether exceptions exist.

## Risk Assessment Approach

Vendor risk is evaluated using factors such as:

* Type and sensitivity of data processed
* Production and privileged access
* API and system integrations
* Business criticality
* Regulatory and privacy exposure
* External hosting
* Subprocessors and fourth parties

Identified risks are then evaluated using likelihood and impact, existing or compensating controls, residual risk, treatment decisions, ownership, and remediation timelines.

## Security Due Diligence

The questionnaire used in this project covers areas including:

* Identity and Access Management
* Data Protection
* Encryption and Key Management
* Logging and Monitoring
* Vulnerability Management
* Secure SDLC
* Incident Response
* Business Continuity and Disaster Recovery
* Privacy
* Third- and Fourth-Party Risk
* Security Governance
* Change Management
* Network and Endpoint Security

The practice questionnaire is aligned to common CAIQ and SIG risk areas. It does not reproduce licensed SIG questionnaire content.

## What I am building next

The next phase is focused on creating a realistic evidence package for the Critical vendor and performing a deeper assessment against it.

Planned additions include:

* Mock SOC 2 assessment package
* BCP/DR test evidence
* Penetration test findings
* Vendor security policies
* Subprocessor assessment
* Contract security review
* Formal vendor risk assessment report
* Risk acceptance workflow
* Additional continuous-monitoring scenarios

## Purpose

This project is intended to demonstrate how I approach vendor risk as an analyst: understanding the business relationship first, applying risk-based due diligence, validating evidence rather than relying only on questionnaire responses, documenting gaps clearly, and following risks through remediation or formal acceptance.

The project will continue to evolve as I add more realistic vendor scenarios and assessment artifacts.
