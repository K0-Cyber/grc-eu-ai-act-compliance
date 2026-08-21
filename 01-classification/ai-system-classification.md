# AI System Classification Assessment

## Purpose

This document classifies EugAI under the EU AI Act risk-tier structure.

It supports Article 6 by determining whether EugAI is prohibited, High Risk, Limited Risk, or Minimal Risk, and identifying the applicable obligations.

## AI System

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| AI System | EugAI Customer Service Chatbot |
| System Type | Conversational AI / chatbot |
| Use Case | First-line customer service support |
| Users | Client employees and service users |
| Current Deployment | Product queries, troubleshooting, ticket routing, and support escalation |
| EU AI Act Classification | Limited Risk |
| Main Applicable Obligation | Article 50 transparency |

## Classification Method

Classification under the EU AI Act follows this sequence:

1. Check whether the AI practice is prohibited under Article 5.
2. Check whether the AI system is High Risk under Annex III or regulated product rules.
3. Check whether the system creates Limited Risk transparency obligations under Article 50.
4. If none apply, treat the system as Minimal Risk.

## Step 1 — Prohibited Practices Check

| Article 5 Prohibited Practice | Does EugAI Perform This? | Result |
|---|---|---|
| Subliminal manipulation | No | Not prohibited |
| Exploitation of vulnerabilities | No | Not prohibited |
| Social scoring | No | Not prohibited |
| Real-time remote biometric identification in public spaces | No | Not prohibited |
| Predictive policing based only on profiling | No | Not prohibited |
| Emotion inference in workplace or education | No | Not prohibited |
| Untargeted scraping of facial images | No | Not prohibited |

Result: EugAI is not prohibited under Article 5.

## Step 2 — High Risk Check

| Annex III High Risk Area | Does EugAI Apply? | Result |
|---|---|---|
| Biometric identification or categorisation | No | Not High Risk |
| Critical infrastructure | No | Not High Risk |
| Education or vocational training | No | Not High Risk |
| Employment, worker management, or access to self-employment | No | Not High Risk |
| Access to essential private or public services | No | Not High Risk |
| Law enforcement | No | Not High Risk |
| Migration, asylum, or border control | No | Not High Risk |
| Administration of justice or democratic processes | No | Not High Risk |

Result: EugAI is not High Risk in its current deployment.

## Step 3 — Limited Risk Check

| Article 50 Question | Answer | Result |
|---|---|---|
| Does the system interact with natural persons? | Yes | Article 50 applies |
| Is the system a chatbot or conversational AI? | Yes | Article 50 applies |
| Does the system generate deepfake image, audio, or video content? | No | Not applicable |
| Does the system detect emotions? | No | Not applicable |
| Does the system perform biometric categorisation? | No | Not applicable |

Result: EugAI is a Limited Risk AI system because it is a chatbot interacting with natural persons.

## Final Classification

| Classification Area | Decision |
|---|---|
| Prohibited AI system | No |
| High Risk AI system | No |
| Limited Risk AI system | Yes |
| Minimal Risk AI system | No |
| Final Classification | Limited Risk |
| Main Obligation | Article 50 transparency |

## Classification Rationale

EugAI is classified as Limited Risk because it is a customer service chatbot that interacts with human users.

It does not perform prohibited practices and is not currently used in any Annex III High Risk area such as employment, credit, education, law enforcement, migration, biometric identification, or access to essential services.

The main compliance requirement is that users must be clearly informed that they are interacting with an AI system.

## Reclassification Triggers

EugAI would need to be reassessed if used for:

- Employment screening
- Worker monitoring or task allocation
- Education access or assessment
- Credit scoring or insurance eligibility
- Access to essential services
- Healthcare decision support
- Biometric identification or categorisation
- Law enforcement support
- Migration or asylum decisions
- Decisions affecting legal rights or fundamental rights

## Status

Status: Implemented  
EU AI Act Mapping: Article 6 and Article 50  
Project: EU AI Act Compliance Lab
