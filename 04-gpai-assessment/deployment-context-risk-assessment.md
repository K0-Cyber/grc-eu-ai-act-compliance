# Deployment Context Risk Assessment

## Purpose

This document assesses the deployment-specific risks created by EugTech's use of a GPAI model within EugAI.

It supports EU AI Act readiness by showing that EugTech does not rely only on the GPAI provider's controls and instead assesses the specific risks created by its own use case.

## Deployment Context

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| AI System | EugAI Customer Service Chatbot |
| GPAI Use | GPT-4 class model accessed via API |
| Deployment Role | Downstream deployer / application provider |
| Use Case | First-line customer service |
| Users | Client employees and service users |
| Current EU AI Act Classification | Limited Risk |
| Main Current Obligation | Article 50 transparency |

## Deployment-Specific Risk Principle

A GPAI model may be general purpose, but the legal and risk impact depends on how it is deployed.

EugTech must assess EugAI in its own context because using a compliant GPAI model does not automatically make the EugAI deployment compliant.

## Deployment Risk Assessment

| Risk ID | Deployment Risk | Description | Control |
|---|---|---|---|
| DRA-01 | Hallucination in customer support | GPAI model may generate confident but false product information | RAG grounding, accuracy testing, human escalation |
| DRA-02 | Prompt injection | Users may attempt to override system instructions | Prompt hardening, input monitoring, red team testing |
| DRA-03 | PII in prompts | Users may submit personal data during support conversations | PII detection, masking, data minimisation |
| DRA-04 | Overreliance | Users may trust AI outputs without verification | Transparency notice, limitations notice, human support |
| DRA-05 | Model change by provider | Provider may update model behaviour without direct EugTech control | Supplier monitoring, change review, regression testing |
| DRA-06 | Transparency failure | Users may not realise they are interacting with AI | Article 50 disclosure at start of chat |
| DRA-07 | Bias or unequal service quality | Model may respond differently to users based on writing style or demographic signals | Bias testing and monitoring |
| DRA-08 | Out-of-scope advice | EugAI may answer medical, legal, financial, or high-stakes queries | Scope restrictions and escalation triggers |
| DRA-09 | Provider outage | Third-party API service may be unavailable | Human support fallback and SLA review |
| DRA-10 | Supplier compliance gap | GPAI provider evidence may be incomplete or delayed | Supplier due diligence and contractual escalation |

## Current Safeguards

| Safeguard | Purpose |
|---|---|
| Article 50 transparency notice | Informs users they are interacting with AI |
| Human escalation | Allows users to move to human support |
| Prompt guardrails | Restrict out-of-scope or unsafe responses |
| RAG grounding | Reduces unsupported answers |
| Accuracy monitoring | Tracks factual correctness |
| Bias testing | Monitors fairness across demographic variants |
| Red team testing | Tests prompt injection and jailbreak risks |
| Supplier due diligence | Reviews provider documentation and compliance evidence |
| Incident procedure | Supports investigation and corrective action |

## Deployment Boundary

EugTech controls:

- EugAI user interface
- Transparency notice
- Prompt configuration
- Knowledge base content
- User escalation process
- Monitoring and logging
- Customer support workflow
- Incident response process
- Supplier due diligence

The GPAI provider controls:

- Base model training
- Base model architecture
- Foundation model updates
- Provider-side technical documentation
- Provider-side systemic risk assessment where applicable
- Provider platform security and availability

## High Risk Deployment Warning

EugAI's deployment context must be reassessed before use in:

- Employment screening
- Credit or insurance decisions
- Education access or assessment
- Healthcare advice
- Access to essential services
- Biometric categorisation
- Law enforcement
- Migration or asylum
- Decisions affecting legal rights

## Conclusion

EugTech's use of a GPAI model creates deployment-specific risks that must be managed by EugTech, even where the GPAI provider has its own compliance obligations.

The current deployment remains Limited Risk, but controls are required for transparency, hallucination, prompt injection, privacy, overreliance, supplier dependency, and human escalation.

## Status

Status: Implemented  
EU AI Act Mapping: Articles 51-55 and Article 50  
Project: EU AI Act Compliance Lab
