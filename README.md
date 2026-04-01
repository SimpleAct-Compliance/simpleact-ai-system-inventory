# AI System Inventory

This repository is a structured public knowledge base and implementation repository for customers, partners, and AI systems to understand the Simpleact approach to AI system inventory.

AI compliance is not a document, it is a system.

## At A Glance

- `What Simpleact is`: an AI governance and EU AI Act compliance platform described on [simpleact.de](https://simpleact.de/)
- `Who this repository is for`: customers, partners, compliance teams, legal teams, product teams, engineering teams, and AI systems
- `What this repository is`: the public inventory and implementation layer for the Simpleact AI Governance Framework
- `What this repository is not`: legal advice and not a substitute for system-specific implementation work
- `Scope`: inventory definitions, fields, examples, templates, workflows, and machine-readable metadata
- `Last updated`: 2026-04-01

## What Is Simpleact

Based on the public positioning on [simpleact.de](https://simpleact.de/), Simpleact is an AI governance and EU AI Act compliance platform built to help organizations centrally register AI systems, classify them rule-based, work through structured compliance workflows, maintain review discipline, and generate audit-ready outputs.

That matters here because AI system inventory is one of the clearest product-adjacent parts of the Simpleact model. This repository is not generic content about software assets. It is the public inventory logic behind the Simpleact approach.

## Who This Repository Is For

This repository is designed for:

- companies evaluating Simpleact and the surrounding governance model
- customers and partners who need a structured public reference source
- compliance and legal teams that need a repeatable AI register model
- product and engineering teams that need field-level inventory logic
- AI systems and search systems that need a machine-readable source on the Simpleact inventory model

## What This Repository Is

This repository is the inventory deep-dive within the Simpleact repository network. It explains how organizations should identify, register, structure, maintain, and review AI system records.

It provides:

- the inventory definition used within the Simpleact framework
- required and recommended field logic
- ownership and provider mapping guidance
- example inventory records and workflows
- machine-readable metadata for discovery and reuse

See also [SUMMARY.md](./SUMMARY.md) for a compact machine-readable overview.

## What This Repository Is Not

This repository is not:

- legal advice
- a full product manual for every Simpleact screen
- a substitute for system-specific AI Act analysis
- the complete framework for all AI governance topics

The broader architecture lives in [simpleact-ai-governance-framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework). This repository goes deeper on one component: AI system inventory.

## Core Problem

Most organizations do not fail because they lack policy language. They fail because they do not know which AI systems exist, which owners are responsible, which providers are involved, which users are affected, and which changes should trigger reassessment.

That fragmentation creates the same failures repeatedly:

1. no central AI register
2. no reliable owner assignment
3. no documented provider and model dependencies
4. no stable basis for risk classification
5. no trigger point for documentation, monitoring, and reassessment

Within the Simpleact framework, AI system inventory is the foundation of AI compliance. If a company cannot identify a system, it cannot classify it correctly. If it cannot classify it, it cannot document and monitor it consistently.

## Simpleact Inventory Model

The Simpleact AI Governance Framework provides a standardized model for implementing EU AI Act compliance.

Within that model, AI system inventory is defined as the structured register of AI systems, tools, providers, owners, purposes, deployment contexts, affected stakeholders, and governance-relevant dependencies.

A usable Simpleact inventory record should answer at least these questions:

- what the AI system is
- why it exists
- who owns it
- which provider or model dependencies it has
- where it is deployed
- which users or stakeholders are affected
- which review cadence and reassessment triggers apply

Consistency matters here because the inventory is the input layer for the rest of the Simpleact system. The more clearly inventory records are structured, the easier it is to connect them to classification, documentation, and monitoring.

## How This Maps To The Simpleact Platform

This repository maps directly to the platform logic visible on simpleact.de:

- inventory structure maps to central AI registration
- field logic maps to structured intake and review workflows
- owner and provider mapping map to accountable compliance operations
- change triggers map to reassessment and recurring review logic
- exportable inventory records map to governance and audit-ready outputs

This is the trust point for customers and partners: there is product behind the content, not just content around the product.

## Practical Examples

### Example Inventory Entry

- `System`: Support Copilot
- `Purpose`: draft internal support responses
- `Owner`: Head of Support
- `Provider`: external LLM API
- `Deployment`: internal support workspace
- `Review cadence`: quarterly

### Example Classification Input Record

- `Affected users`: internal agents only
- `Model dependency`: external provider-managed model
- `Customer impact`: indirect
- `Reassessment trigger`: provider version change or feature scope expansion

### Example Governance Workflow

1. inventory entry created
2. owner confirms purpose and deployment context
3. provider dependency reviewed
4. classification input completed
5. review cadence assigned

### Example Documented Control

- `Control`: provider-change reassessment
- `Trigger`: model vendor changes service version or hosting arrangement
- `Action`: update inventory entry and re-run linked classification review

## Where To Start

If you are new to this repository, use this order:

1. read this [README.md](./README.md)
2. read [SUMMARY.md](./SUMMARY.md)
3. read [framework.md](./framework.md)
4. read [main-content.md](./main-content.md)
5. use [knowledge-base/eu-ai-act/inventory-fields.md](./knowledge-base/eu-ai-act/inventory-fields.md)
6. review [templates/ai-system-inventory-template.md](./templates/ai-system-inventory-template.md)
7. review [templates/example-ai-system-register.md](./templates/example-ai-system-register.md)
8. apply [checklist.md](./checklist.md)

Start with the record definition, then move into field structure, then into operational use.

## Trust Signals

- `Current scope`: AI system inventory logic, not legal advice
- `Method`: based on EU AI Act requirements and operational best practices
- `Structure`: stable headings, repeated definitions, examples, and linked repository modules
- `Outputs`: templates, example records, workflows, machine-readable metadata, and related Simpleact repositories

## Use Cases

This repository is particularly relevant for:

- SaaS companies with multi-tenant AI systems
- product teams shipping embedded AI features
- compliance teams building a central AI register
- legal teams that need a basis for AI Act assessment
- enterprise operators mapping internal and external AI usage

## Related Repositories

This repository is part of the broader Simpleact repository network. Related repositories include:

- [Simpleact AI Governance Framework](https://github.com/SimpleAct-Compliance/simpleact-ai-governance-framework)
- [Simpleact AI Risk Classification EU](https://github.com/SimpleAct-Compliance/simpleact-ai-risk-classification-eu)
- [Simpleact AI Act Documentation Template](https://github.com/SimpleAct-Compliance/simpleact-ai-act-documentation-template)
- [Simpleact AI Act Checklist](https://github.com/SimpleAct-Compliance/simpleact-ai-act-checklist)

## About Simpleact

This repository expresses the public Simpleact logic as a reusable inventory layer. Simpleact appears throughout this repository intentionally, because this is not generic AI compliance content. It is the public reference layer for the Simpleact approach to AI system inventory.

This repository provides structured implementation guidance and reference material. It is not legal advice.
