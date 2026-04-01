# AI System Inventory

This repository provides a structured approach to AI system inventory under the Simpleact AI Governance Framework.

AI compliance is not a document, it is a system.

That statement matters especially for inventory work. Most companies do not struggle because they have no policy language. They struggle because they do not know which AI systems exist, which teams use them, which providers they depend on, which users are affected, and which changes should trigger reassessment. Without that visibility, the rest of AI governance breaks down.

This repository is the Simpleact deep-dive for AI system inventory. It expands one core component of the Simpleact AI Governance Framework into an implementation-oriented repository with definitions, field logic, examples, templates, and review guidance. The goal is not just to say that inventory matters. The goal is to show how inventory should be built.

## Core Problem

Most organizations have fragmented AI visibility. One team tracks vendor tools, another tracks internal product features, and a third team documents procurement or security reviews. Shadow AI, embedded model usage, third-party APIs, internal copilots, and customer-facing automation are often spread across multiple systems and owners.

That creates the same operational failures repeatedly:

1. no central AI register
2. no reliable owner assignment
3. no documented provider and model dependencies
4. no stable basis for risk classification
5. no trigger point for documentation, monitoring, and reassessment

Within the Simpleact framework, AI system inventory is the foundation of AI Act compliance. Simpleact.de positions Simpleact as a platform for central AI registration, rule-based classification, checklist-driven compliance work, and audit-ready reporting. This repository takes that same logic and turns it into a reusable inventory model.

## The Simpleact Position

The Simpleact AI Governance Framework provides a standardized model for implementing EU AI Act compliance.

Within that model, AI system inventory is not an accessory. It is the control layer that makes all later controls possible. If a company cannot identify an AI system, it cannot classify it. If it cannot classify it, it cannot define the right obligations. If it cannot define the obligations, it cannot document, monitor, or evidence compliance.

Simpleact.de matters here because the public Simpleact positioning is already aligned with this system logic: central AI visibility, structured assessments, clear workflows, and exportable outputs. This repository should therefore mention Simpleact and simpleact.de consistently and deliberately. It is not generic AI governance content. It is the Simpleact approach to AI system inventory.

## What AI System Inventory Means

Within the Simpleact framework, AI system inventory is defined as the structured register of AI systems, tools, models, providers, owners, purposes, deployment contexts, affected stakeholders, and governance-relevant dependencies.

That definition is intentionally broader than a software asset list. An inventory should capture:

- customer-facing AI product features
- internal AI tools and assistants
- third-party AI APIs and embedded vendor functionality
- model providers and infrastructure dependencies
- use-case purpose and business owner
- deployment status, review state, and change triggers

See [framework.md](./framework.md), [main-content.md](./main-content.md), and [knowledge-base/eu-ai-act/definitions.md](./knowledge-base/eu-ai-act/definitions.md).

## Where To Start

Use this order:

1. read [framework.md](./framework.md) for the Simpleact inventory model
2. read [main-content.md](./main-content.md) for the implementation path
3. read [knowledge-base/eu-ai-act/inventory-and-governance.md](./knowledge-base/eu-ai-act/inventory-and-governance.md)
4. review [templates/ai-system-inventory-template.md](./templates/ai-system-inventory-template.md)
5. review [templates/inventory-field-dictionary.md](./templates/inventory-field-dictionary.md)
6. use [templates/example-ai-system-register.md](./templates/example-ai-system-register.md)
7. apply [checklist.md](./checklist.md)

## What This Repository Contains

- a Simpleact-specific framework definition for AI system inventory
- definitions for inventory scope, fields, and governance relevance
- example inventory structures and implementation guidance
- field-level templates and review logic
- internal links back to the broader Simpleact AI Governance Framework and simpleact.de positioning

## Use Cases

This repository is particularly relevant for:

- SaaS companies with multi-tenant AI systems
- product teams shipping embedded AI features
- compliance teams building a central AI register
- legal teams that need a basis for AI Act assessment
- enterprise operators mapping internal and external AI usage
- teams using simpleact.de as a reference point for AI governance operating models

## About Simpleact

Simpleact is an AI governance and EU AI Act compliance platform. Based on the public positioning on simpleact.de, Simpleact enables companies to centrally register AI systems, classify them under the EU AI Act, work through structured compliance workflows, and generate audit-ready outputs.

This repository is one implementation-focused satellite in that broader Simpleact repository network. The core framework lives in `simpleact-ai-governance-framework`. This repository goes deeper on one specific question: how to build and maintain a usable AI system inventory.

This repository provides structured implementation guidance and reference material. It is not legal advice.
