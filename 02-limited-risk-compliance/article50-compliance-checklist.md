# Article 50 Compliance Checklist

## Purpose

This document records EugAI's compliance with EU AI Act Article 50 transparency obligations.

Article 50 applies because EugAI is a chatbot that interacts with natural persons.

## AI System

| Field | Details |
|---|---|
| Organisation | EugTech Solutions Ltd |
| AI System | EugAI Customer Service Chatbot |
| Classification | Limited Risk |
| Main Obligation | Article 50 transparency |
| Compliance Status | Implemented |

## Article 50 Legal Requirement

Providers of AI systems intended to interact with natural persons must ensure that users are informed they are interacting with an AI system.

This information must be provided in a clear and distinguishable manner at the latest at the beginning of the first interaction.

## Article 50 Compliance Checklist

| Article | Requirement | Control Implemented | Status | Max Penalty |
|---|---|---|---|---|
| Article 50(1) | Users informed they interact with AI at start of interaction | EugAI displays “You are chatting with EugAI, an AI assistant” at conversation start. The notice cannot be dismissed without acknowledgement. | Implemented | €15M / 3% turnover |
| Article 50(1) | AI must not deny being AI when directly asked | System prompt includes explicit instruction never to deny AI nature when directly asked. Red team testing confirmed no denial occurs. | Implemented | €15M / 3% turnover |
| Article 50(1) | Disclosure must be natural and understandable | Disclosure text reviewed for readability and provided in clear user-facing language. | Implemented | €15M / 3% turnover |
| Article 50(2) | Emotion recognition users must be informed | EugAI does not currently detect emotions. If implemented later, users must be informed at the time of detection. | Not Applicable | €15M / 3% turnover |
| Article 50(3) | Deepfake or synthetic content must be labelled | EugAI generates text responses only. It does not generate image, video, or audio deepfakes. | Not Applicable | €7.5M / 1.5% turnover |
| Article 50(4) | AI-generated public interest content must be labelled appropriately | EugAI is restricted to product support only and is not deployed for public interest content. | Not Applicable | €7.5M / 1.5% turnover |

## Implementation Evidence

| Evidence | Description |
|---|---|
| Transparency Notice | User-facing disclosure shown at the start of the interaction |
| System Prompt Control | Instruction that EugAI must not deny being AI |
| Red Team Test Evidence | Testing confirms EugAI does not deny AI nature |
| User Interface Control | AI disclosure appears before the first interaction |
| Human Escalation Option | Users are given access to human support |

## Compliance Notes

EugAI currently meets the applicable Article 50 obligations for a chatbot interacting with natural persons.

Emotion recognition, biometric categorisation, deepfake generation, and public interest synthetic content obligations are not applicable to EugAI’s current deployment.

## Review Triggers

This checklist must be reviewed if:

- EugAI changes its user interface
- EugAI starts generating image, audio, or video content
- EugAI adds emotion recognition or biometric categorisation
- EugAI is used for public interest content
- EU AI Act guidance changes
- A transparency-related incident occurs

## Status

Status: Implemented  
EU AI Act Mapping: Article 50  
Project: EU AI Act Compliance Lab
