# GPAI Provider Due Diligence

## Purpose

This document records EugTech Solutions Ltd's due diligence over its General Purpose AI model provider.

It supports EU AI Act Articles 51-55 by documenting how EugTech reviews the provider of the GPAI model used by EugAI.

## Context

EugAI uses a GPT-4 class General Purpose AI model accessed through a third-party API.

EugTech does not train or provide the GPAI model. EugTech uses the model to build and deploy EugAI as a customer service chatbot.

## GPAI Role Assessment

| Role | Description | EugTech Position |
|---|---|---|
| GPAI Model Provider | Organisation that creates or trains the GPAI model | Third-party API provider |
| GPAI Downstream Provider / Deployer | Organisation that uses an existing GPAI model to build or deploy an AI application | EugTech Solutions Ltd |
| AI System | Application built using the GPAI model | EugAI Customer Service Chatbot |

## GPAI Provider Obligations

The GPAI model provider is responsible for obligations such as:

- Providing technical documentation
- Publishing model information or summaries
- Complying with copyright-related requirements
- Assessing systemic risks where applicable
- Implementing appropriate testing and evaluation
- Supporting downstream deployers with relevant information

## EugTech Downstream Obligations

EugTech must:

- Obtain and review provider documentation where available
- Conduct its own deployment-specific risk assessment
- Implement EugAI-specific controls
- Monitor provider changes and compliance updates
- Include AI compliance clauses in supplier contracts
- Maintain evidence of provider due diligence

## GPAI Provider Due Diligence Checklist

| Due Diligence Item | Status / Action | Evidence |
|---|---|---|
| Obtain GPAI provider's Article 53 technical documentation | Requested from API provider. Awaiting provision. Required before High Risk deployment. | Supplier correspondence, documentation request log |
| Review provider copyright compliance declaration | Obtained through API provider terms of service. Training data copyright compliance confirmed at supplier level. | API provider terms, copyright declaration |
| Assess whether model qualifies as systemic risk model | GPT-4 class models may qualify. Confirmation requested from API provider. | Model specification documentation from provider |
| Contractual clauses for GPAI compliance | Data processing agreement signed. AI-specific clauses added for incident reporting, model updates, compliance evidence, and audit rights. | Signed API agreement, DPA |
| Implement deployment-specific safeguards | Prompt injection controls, hallucination mitigation, transparency notices, and scope restrictions implemented. | System configuration, red team results |
| Monitor GPAI provider compliance updates | Compliance updates reviewed quarterly. Provider updates tracked by ISM. | Newsletter subscription, review schedule |

## Supplier Risk Areas

| Risk Area | Description | Control |
|---|---|---|
| Model change risk | Provider may change the model without sufficient notice | Contractual change notice and monitoring |
| Documentation gap | Provider may not provide sufficient technical documentation | Supplier evidence request and escalation |
| Compliance uncertainty | Provider may not clearly demonstrate EU AI Act readiness | Supplier due diligence checklist |
| Service availability | API outage could affect EugAI availability | SLA review and fallback to human support |
| Security breach | Provider compromise could affect confidentiality or integrity | Supplier security assessment and incident clauses |
| Data protection | API use may involve personal data in prompts or logs | DPA, data minimisation, PII controls |

## Review Requirements

GPAI provider due diligence must be reviewed:

- Annually
- When the provider changes model version
- When contractual terms change
- When EugAI changes deployment context
- Before any High Risk deployment
- After supplier incident notification
- When EU AI Act guidance changes

## Conclusion

EugTech is a downstream deployer of a GPAI model rather than the original GPAI model provider.

Using a GPAI model through an API does not remove EugTech's compliance responsibilities. EugTech must still assess its deployment context, implement application-level safeguards, and maintain supplier due diligence evidence.

## Status

Status: Implemented  
EU AI Act Mapping: Articles 51-55  
Project: EU AI Act Compliance Lab
