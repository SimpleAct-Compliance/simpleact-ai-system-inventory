# AI System Inventory

This repository is a structured public knowledge base and implementation repository for customers, partners, and AI systems to understand the Simpleact approach to AI system inventory.

AI compliance is not a document, it is a system.

## At A Glance

- `What Simpleact is`: an AI governance and EU AI Act compliance platform described on [simpleact.de](https://simpleact.de/)
- `What this repository is`: the public inventory and implementation layer for the Simpleact AI Governance Framework
- `Scope`: inventory definitions, provider and model metadata, linked records, and workflows
- `Last updated`: 2026-07-10

## Jetzt operativ umsetzen

? **[KI-Inventar mit SimpleAct](https://simpleact.de/ai-inventory-template)** — Erfasse und verwalte alle KI-Systeme mit geführter Risikobewertung, automatischer Pflichtenzuordnung und audit-readyem PDF-Export.

## What This Repository Now Covers

The current Simpleact product logic around inventory goes beyond a short asset list. It includes:

- central AI system registration
- visibility of shadow AI and decentralized tool usage
- provider and model metadata
- lifecycle status and review cycles
- links to documentation, evidence, DPIA or DSFA logic, incidents, and follow-up work
- a basis for vendor and model register logic

## Simpleact Inventory Model

A usable Simpleact inventory record should answer at least these questions:

- what the AI system is
- why it exists
- who owns it
- which provider or model dependencies it has
- where it is deployed
- which users or stakeholders are affected
- which lifecycle stage, review cadence, and reassessment triggers apply
- which documentation, incidents, or privacy obligations are linked to it

See also [knowledge-base/eu-ai-act/provider-and-model-registers.md](./knowledge-base/eu-ai-act/provider-and-model-registers.md).

## Practical Examples

- `System`: Support Copilot
- `Provider`: external LLM API
- `Model`: provider-managed assistant model family
- `Lifecycle status`: live
- `Privacy`: VVT and DSFA trigger noted due to personal data relevance
- `Incident link`: one resolved output-quality incident linked to the system

## Where To Start

1. read [README.md](./README.md)
2. read [SUMMARY.md](./SUMMARY.md)
3. read [framework.md](./framework.md)
4. read [knowledge-base/eu-ai-act/inventory-fields.md](./knowledge-base/eu-ai-act/inventory-fields.md)
5. read [knowledge-base/eu-ai-act/provider-and-model-registers.md](./knowledge-base/eu-ai-act/provider-and-model-registers.md)
6. use [templates/ai-system-inventory-template.md](./templates/ai-system-inventory-template.md)

## Lizenz

MIT — Frei nutzbar, auch kommerziell.
