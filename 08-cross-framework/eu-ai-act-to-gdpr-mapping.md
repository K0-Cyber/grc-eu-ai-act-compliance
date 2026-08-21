# EU AI Act to GDPR Mapping

## Purpose

This document maps EU AI Act obligations to GDPR-related privacy and data protection considerations.

The purpose is to show how AI compliance and data protection compliance interact where AI systems process personal data.

## Framework Relationship

The EU AI Act governs the placing on the market, deployment, and use of AI systems.

GDPR governs the processing of personal data.

Where an AI system processes personal data, both frameworks may apply. EU AI Act compliance does not replace GDPR compliance, and GDPR compliance does not automatically satisfy EU AI Act obligations.

## Mapping Table

| EU AI Act Area | GDPR Area | Connection |
|---|---|---|
| Article 6 - AI Classification | Lawfulness and purpose limitation | AI use case and purpose must be clear before processing personal data |
| Article 10 - Data Governance | Data minimisation, accuracy, storage limitation | AI training, validation, testing, prompts, and logs may involve personal data controls |
| Article 12 - Record Keeping | Accountability | AI logs and records may support accountability but must respect data minimisation |
| Article 13 - Transparency | Transparency and information rights | Users should understand AI use and personal data processing where applicable |
| Article 14 - Human Oversight | Automated decision-making safeguards | Human oversight can support safeguards where AI affects individuals |
| Article 15 - Accuracy and Robustness | Accuracy principle | AI outputs and personal data processing should be accurate and controlled |
| Article 27 - Fundamental Rights Impact Assessment | Data Protection Impact Assessment | FRIA and DPIA may overlap where AI affects rights and processes personal data |
| Article 50 - Chatbot Transparency | Privacy notice transparency | AI disclosure should align with privacy notice information |
| Article 73 - Serious Incident Reporting | Personal data breach notification | Prompt injection or AI leakage involving personal data may trigger GDPR breach assessment |

## EugAI Privacy Context

EugAI may process personal data if users include it in chat queries.

Potential personal data examples include:

- Names
- Email addresses
- Phone numbers
- Account references
- Employee details
- Support issue details
- Sensitive information accidentally submitted by users

## GDPR Controls for EugAI

| GDPR Principle or Obligation | EugAI Control |
|---|---|
| Lawfulness, fairness, and transparency | Privacy notice and AI transparency notice |
| Purpose limitation | EugAI restricted to customer support |
| Data minimisation | Users discouraged from entering unnecessary personal data |
| Accuracy | Knowledge base review and factual accuracy monitoring |
| Storage limitation | Short retention period for AI interaction logs |
| Integrity and confidentiality | Access controls, supplier due diligence, secure logging |
| Accountability | Documented assessments, incident procedure, audit evidence |
| Data subject rights | Human support and escalation route |
| Breach notification | DPO involvement and GDPR notification assessment |

## DPIA and FRIA Relationship

A Data Protection Impact Assessment focuses on personal data processing risk.

A Fundamental Rights Impact Assessment focuses more broadly on impacts to rights, equality, dignity, remedy, and affected groups.

For EugAI:

| Assessment | Required? | Reason |
|---|---|---|
| DPIA | May be required depending on personal data processing scale and risk | EugAI may process personal data in chat logs |
| FRIA | Not mandatory in current Limited Risk deployment | EugAI is not currently High Risk |
| Voluntary FRIA | Completed | Demonstrates proactive rights assessment |

## Incident Overlap

Some AI incidents may trigger both EU AI Act and GDPR processes.

| Incident | EU AI Act Concern | GDPR Concern |
|---|---|---|
| Prompt injection exposes personal data | Serious incident or security failure | Personal data breach |
| AI repeats personal data in response | Privacy and transparency concern | Data breach or unlawful disclosure |
| Systematic bias affecting protected group | Fundamental rights concern | Fairness and discrimination-related data protection concerns |
| AI denies being AI | Article 50 transparency breach | May also create transparency issue if linked to data processing notice |
| Logs retained too long | Record keeping and governance issue | Storage limitation breach |

## Key Observations

- AI transparency and privacy transparency should be aligned but are not the same thing.
- Article 50 tells users they are interacting with AI.
- GDPR tells users how their personal data is processed.
- AI logs can support compliance evidence but must be managed under data minimisation and retention controls.
- Personal data incidents involving AI may require DPO review and GDPR breach notification assessment.

## Summary

The EU AI Act and GDPR are complementary.

For EugAI, the strongest overlap is transparency, personal data in prompts, logging, data minimisation, DPIA/FRIA alignment, and incident reporting.

## Status

Status: Implemented  
Project: EU AI Act Compliance Lab
