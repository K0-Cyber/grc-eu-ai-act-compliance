# Fundamental Rights Impact Assessment

## Purpose

This document records a voluntary Fundamental Rights Impact Assessment for EugAI.

Although EugAI is currently classified as Limited Risk, this assessment demonstrates proactive consideration of the potential impact of AI on people, rights, fairness, privacy, and access to remedy.

## Assessment Details

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| AI System | EugAI Customer Service Chatbot |
| Current Classification | Limited Risk |
| FRIA Status | Voluntary |
| EU AI Act Mapping | Article 27 |
| Assessment Type | Fundamental Rights Impact Assessment |
| Assessment Date | January 2026 |

## When a FRIA Is Required

A Fundamental Rights Impact Assessment is required before deploying certain High Risk AI systems, especially where used by:

- Public bodies
- Private entities providing public services
- Private deployers using High Risk AI in employment
- Private deployers using High Risk AI in financial services

EugAI is currently not High Risk, so this FRIA is not mandatory in the current deployment.

## AI System Description

EugAI is a customer service chatbot providing product information and first-line support to clients of EugTech Solutions Ltd.

It supports:

- Product queries
- Troubleshooting common issues
- Ticket routing
- Human escalation
- Knowledge base retrieval

EugAI does not make final decisions affecting legal rights, employment, credit, healthcare, education, or access to essential services.

## Affected Groups

| Affected Group | Description |
|---|---|
| EugTech clients | Organisations using EugAI as part of service delivery |
| Client employees | Users who interact with the chat support function |
| EugTech support staff | Staff reviewing escalated conversations |
| Data subjects | Individuals whose personal data may appear in support queries |
| Users with varied technical literacy | Users may understand AI outputs differently |
| Users with varied writing styles | Users may interact with EugAI using different language patterns |

## Fundamental Rights Assessment

| Right | Potential Risk | Mitigation | Residual Risk |
|---|---|---|---|
| Non-discrimination | EugAI may provide lower quality service to users based on writing style, implied demographics, or language formality | Quarterly bias assessment. Demographic variant testing. Monitoring of response quality. | Low |
| Privacy and data protection | User queries may contain inadvertent personal data | PII detection, short retention period, privacy notice, data minimisation, DPO involvement | Low |
| Human dignity | Users may be treated disrespectfully if guardrails fail | Content moderation, human escalation, red team testing, monitoring of poor outputs | Low |
| Access to effective remedy | Users may not know how to challenge or escalate AI outputs | Human support contact provided, complaints route available, AI cannot take account actions | Low |
| Freedom of information | EugAI may restrict information beyond its support scope | Scope limitations documented. Human escalation available for unresolved queries. | Low |
| Consumer protection | Incorrect AI output may mislead users about products or services | Accuracy testing, RAG grounding, knowledge base review, escalation for important decisions | Low to Medium |
| Equality | Response quality may vary across demographic or language groups | Bias testing and monitoring. Findings reviewed by governance stakeholders. | Low |

## Non-Discrimination Assessment

EugAI may create non-discrimination risk if users receive different response quality based on:

- Writing style
- Language formality
- Implied nationality
- Implied gender
- Technical literacy
- Sector context

Mitigation includes quarterly bias testing and comparison of demographic variants against a neutral baseline.

Current assessment result:

```text
PASS — all tested demographic groups remained within 8% of baseline.
