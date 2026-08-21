# High Risk Gap Analysis

## Purpose

This document assesses what would be required if EugAI were reclassified as a High Risk AI system under the EU AI Act.

EugAI is currently classified as Limited Risk because it is a customer service chatbot. However, this gap analysis supports forward-looking readiness if EugAI is later deployed in a High Risk use case.

## Current Classification

| Field | Details |
|---|---|
| AI System | EugAI Customer Service Chatbot |
| Current Classification | Limited Risk |
| Current Main Obligation | Article 50 transparency |
| High Risk Status | Not High Risk in current deployment |
| Gap Assessment Purpose | High Risk readiness planning |

## When EugAI Could Become High Risk

EugAI could become High Risk if deployed for:

- Screening job applicants
- Making or supporting employment decisions
- Allocating work or monitoring employees
- Making or assisting education access decisions
- Supporting credit, insurance, or essential services decisions
- Supporting biometric categorisation affecting fundamental rights
- Supporting law enforcement, migration, asylum, or judicial decisions

The classification is use-case specific. The same AI model can be Limited Risk in one deployment and High Risk in another.

## High Risk Obligations Gap Analysis

| Article | Requirement | Current Control | Status | Max Penalty |
|---|---|---|---|---|
| Article 9 | Risk management system throughout lifecycle | NIST AI RMF and ISO 42001 projects provide partial risk management basis, but EU AI Act-specific High Risk risk management is not fully documented. | Gap | €30M / 6% turnover |
| Article 10 | Data and data governance | No complete High Risk training data governance documentation. Anonymisation and data quality processes require formal evidence. | Gap | €30M / 6% turnover |
| Article 11 | Technical documentation and Annex IV | Technical documentation template exists, but full High Risk technical documentation has not yet been produced. | Not Started | €15M / 3% turnover |
| Article 12 | Record keeping and logging | Conversation logs exist, but automated logging of model version, confidence scores, and decision factors is incomplete. | Partial | €15M / 3% turnover |
| Article 13 | Transparency and information provision | Limited Risk disclosure exists, but High Risk deployer-facing transparency documentation is not complete. | Partial | €15M / 3% turnover |
| Article 14 | Human oversight | Human escalation exists, but Article 14 High Risk oversight measures are not formally documented. | Partial | €30M / 6% turnover |
| Article 15 | Accuracy, robustness, and cybersecurity | Hallucination tracking exists, but formal accuracy benchmark and robustness testing against adversarial inputs require expansion. | Partial | €15M / 3% turnover |
| Article 43 | Conformity assessment | No conformity assessment has been conducted for High Risk deployment. | Not Started | €30M / 6% turnover |
| Article 71 | EU AI database registration | EugAI is not registered because it is not currently High Risk. Registration would be required before placing a High Risk system on the market. | Not Started | €30M / 6% turnover |

## Gap Summary

| Status | Count |
|---|---:|
| Gap | 2 |
| Partial | 4 |
| Not Started | 3 |
| Implemented | 0 |

## Priority Remediation Actions

| Priority | Action | Related Article | Owner |
|---|---|---|---|
| High | Build EU AI Act-specific risk management system evidence | Article 9 | ISM |
| High | Document training, validation, and test data governance | Article 10 | AI Engineering Lead / DPO |
| High | Complete Annex IV technical documentation | Article 11 | AI Engineering Lead |
| High | Define Article 14 human oversight measures | Article 14 | Head of Product |
| High | Prepare conformity assessment plan | Article 43 | ISM |
| Medium | Improve logging of model version, confidence scores, and decision factors | Article 12 | AI Engineering Lead |
| Medium | Expand transparency information for deployers | Article 13 | Head of Product |
| Medium | Expand accuracy, robustness, and cybersecurity testing | Article 15 | AI Engineering Lead |
| Medium | Prepare EU database registration template | Article 71 | ISM |

## High Risk Readiness Conclusion

EugAI is not currently High Risk, but a move into employment, education, credit, insurance, essential services, biometric, law enforcement, migration, or justice use cases would trigger significant additional obligations.

The highest priority gaps are Article 9 risk management, Article 10 data governance, Article 11 technical documentation, Article 14 human oversight, Article 43 conformity assessment, and Article 71 registration.

## Status

Status: Implemented  
EU AI Act Mapping: Articles 8-15, Article 43, Article 71  
Project: EU AI Act Compliance Lab
