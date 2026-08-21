# AI Act Incident Reporting Procedure

## Purpose

This document defines the procedure for identifying, assessing, escalating, reporting, and reviewing AI incidents involving EugAI under the EU AI Act.

It supports Article 73 serious incident reporting readiness.

## AI System

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| AI System | EugAI Customer Service Chatbot |
| Current Classification | Limited Risk |
| Procedure Owner | Information Security Manager |
| EU AI Act Mapping | Article 73 |
| Related Processes | AI incident response, GDPR breach notification, risk register update, management review |

## Serious Incident Definition

Under the EU AI Act, a serious incident may include:

- Death or serious harm to health
- Serious and irreversible disruption to critical infrastructure
- Violation of obligations under EU law protecting fundamental rights
- Serious property damage
- Other serious harm

For EugAI, the most likely serious incident scenarios relate to fundamental rights, privacy, transparency, discrimination, or widespread harmful outputs.

## AI Act Incident Classification

| Incident Type | EU AI Act Reporting Trigger |
|---|---|
| Hallucination causing financial loss to user | If widespread and systematic, this may create potential fundamental rights or consumer protection concern |
| Systematic bias against a protected group | Yes, potential violation of non-discrimination rights |
| Prompt injection leading to data breach | If personal data is exposed, GDPR notification may apply and EU AI Act reporting may be considered |
| AI denying being AI | Yes, this may indicate an Article 50 transparency obligation breach |
| Service unavailability | Only likely reportable if linked to critical infrastructure or serious harm |
| Single user complaint | Usually not reportable unless part of a wider serious pattern |

## Reporting Procedure

| Step | Action | Timeline |
|---|---|---|
| 1. Detect | Potential serious incident detected through staff report, monitoring, user complaint, red team finding, supplier alert, or support escalation | Immediate |
| 2. Assess | ISM assesses whether the event may meet the EU AI Act serious incident threshold | Within 4 hours |
| 3. Contain | Disable affected AI functionality if ongoing harm is possible. Preserve logs and evidence. Route users to human support where needed. | Immediate after confirmation |
| 4. Notify under GDPR if applicable | If personal data is involved, assess whether UK GDPR Article 33 breach notification is required | Within 72 hours where required |
| 5. Notify under EU AI Act if applicable | If a serious incident is confirmed, notify the relevant authority within the required reporting timeframe | Within 15 working days |
| 6. Report content | Prepare incident date/time, system identification, nature of incident, affected persons, impact, and immediate measures taken | With notification |
| 7. Follow-up report | Provide root cause analysis, corrective actions, and preventive measures | Within 30 days |
| 8. Post-incident review | Review lessons learned, update risk register, update controls, brief leadership, and update documentation | Within 5 business days after closure |

## Detection Sources

Potential AI incidents may be detected through:

- User complaints
- Human support escalations
- AI monitoring
- Bias testing
- Red team testing
- Log review
- Supplier notifications
- Privacy incident reporting
- Staff reports
- Customer feedback

## Immediate Containment Actions

Containment may include:

- Disable EugAI temporarily
- Disable affected functionality
- Route all users to human support
- Preserve logs
- Preserve prompts and outputs
- Remove harmful knowledge base content
- Block specific prompt patterns
- Escalate to DPO if personal data is involved
- Escalate to leadership if serious harm is possible

## Roles and Responsibilities

| Role | Responsibility |
|---|---|
| Information Security Manager | Owns incident coordination, Article 73 assessment, evidence preservation, and reporting recommendation |
| Data Protection Officer | Assesses privacy impact and GDPR notification obligations |
| Head of Product | Assesses customer, service, and business impact |
| AI Engineering Lead | Investigates technical cause and implements fixes |
| Customer Experience Manager | Coordinates user support and client communications |
| CEO | Approves high-impact external notifications and leadership response |
| Legal / Compliance | Supports regulatory interpretation and notification wording |

## Evidence to Preserve

For every potentially reportable AI incident, preserve:

- Incident timeline
- User reports
- Conversation logs
- Prompt and response records
- Model version
- System prompt version
- Knowledge base version
- Monitoring alerts
- Screenshots where relevant
- Impact assessment notes
- Corrective action records
- Communications with users, clients, suppliers, or regulators

## Report Content

A serious incident report should include:

- AI system name and version
- Organisation details
- Date and time of incident
- Detection method
- Nature of incident
- Affected users or groups
- Potential or actual harm
- Immediate containment actions
- Root cause if known
- Corrective actions planned or completed
- Contact person for follow-up
- Related GDPR notification status where applicable

## Post-Incident Review

After the incident is contained and reported where required, EugTech must:

- Complete root cause analysis
- Identify failed or missing controls
- Update the AI Risk Register
- Update the High Risk Gap Analysis if relevant
- Update the Article 50 checklist if transparency was involved
- Update the FRIA if fundamental rights were affected
- Update monitoring and testing where required
- Report lessons learned to management review

## Status

Status: Implemented  
EU AI Act Mapping: Article 73  
Project: EU AI Act Compliance Lab
