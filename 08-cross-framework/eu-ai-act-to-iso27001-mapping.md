# EU AI Act to ISO 27001 Mapping

## Purpose

This document maps EU AI Act obligations to relevant ISO 27001 information security management areas.

The purpose is to show how information security governance can support AI compliance, especially for security, logging, supplier management, incident response, and risk assessment.

## Framework Relationship

The EU AI Act regulates AI systems and defines obligations based on risk tier and use case.

ISO 27001 provides an information security management system for protecting confidentiality, integrity, and availability of information assets.

ISO 27001 does not replace EU AI Act compliance, but it provides useful supporting controls for security, supplier risk, asset management, logging, and incident management.

## Mapping Table

| EU AI Act Area | ISO 27001 Area | Connection |
|---|---|---|
| Article 9 - Risk Management | Clause 6.1.2 Risk Assessment | ISO 27001 risk assessment supports organisational security risk identification for AI systems |
| Article 10 - Data Governance | Annex A 5.9 Asset Inventory | AI training data, prompts, logs, and knowledge bases should be treated as information assets |
| Article 12 - Record Keeping | Annex A 8.15 Logging | AI logs support traceability, monitoring, and investigation |
| Article 13 - Transparency | Annex A 5.1 Policies | Information security policy governance supports AI transparency commitments |
| Article 14 - Human Oversight | Annex A 5.24 Incident Management | Escalation and oversight processes can integrate with incident management |
| Article 15 - Accuracy, Robustness, and Cybersecurity | Annex A 8.8 Vulnerability Management | Cybersecurity and robustness testing align with vulnerability management and technical control testing |
| Article 50 - Transparency for Chatbots | Annex A 5.10 Acceptable Use | Acceptable use and user-facing controls support responsible AI use |
| Article 73 - Serious Incident Reporting | Annex A 5.24, 5.25, 5.26, 5.27 | AI incident reporting can integrate with security incident planning, assessment, response, and lessons learned |
| GPAI Supplier Dependency | Annex A 5.19 Supplier Relationships | Third-party LLM API providers require supplier risk management and contractual controls |
| Data Protection Risk | Annex A 5.34 Privacy and PII Protection | Personal data in AI prompts and logs requires privacy and protection controls |

## EugAI Project Evidence

| EU AI Act Requirement | ISO 27001 Support | Evidence in This Project |
|---|---|---|
| AI classification | Risk assessment governance | AI System Classification Assessment |
| Article 50 transparency | Policy and acceptable use controls | Article 50 Checklist, Transparency Notice |
| Data governance | Asset inventory and data handling controls | GPAI Due Diligence, Deployment Context Risk Assessment |
| Logging | Logging and monitoring controls | High Risk Gap Analysis, Incident Reporting Procedure |
| Human oversight | Incident and escalation procedures | Transparency Notice, Incident Reporting Procedure |
| Cybersecurity | Vulnerability management and supplier controls | GPAI Due Diligence |
| Incident reporting | Incident management lifecycle | AI Act Incident Reporting Procedure |
| Supplier governance | Supplier relationship management | GPAI Provider Due Diligence |

## Key Observations

- ISO 27001 supports EU AI Act compliance evidence but does not replace AI-specific legal compliance.
- AI systems, logs, prompts, knowledge bases, and supplier APIs should be treated as information assets.
- AI supplier governance maps strongly to ISO 27001 supplier relationship controls.
- EU AI Act incident reporting can integrate with ISO 27001 incident management processes.
- Cybersecurity obligations under Article 15 align with vulnerability management, logging, and monitoring controls.

## Summary

ISO 27001 provides the security governance foundation that supports EU AI Act compliance.

For EugAI, ISO 27001 is most relevant to risk assessment, data governance, supplier management, logging, cybersecurity, and incident response.

## Status

Status: Implemented  
Project: EU AI Act Compliance Lab
