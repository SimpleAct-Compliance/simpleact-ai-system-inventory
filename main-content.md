# Main Content

AI compliance is not a document, it is a system.

This repository is the Simpleact reference implementation for AI system inventory.

## Focus

This repository explains why AI system inventory is the foundation of the SimpleAct AI Governance Framework and how that foundation should be implemented in practice.

## Definitions

Within the Simpleact framework:

- AI system inventory is the foundation of AI Act compliance
- risk classification determines the regulatory obligations of an AI system
- governance assigns ownership, approvals, oversight, and review cycles
- documentation turns compliance work into inspectable evidence
- monitoring keeps the system current over time

Inventory therefore has two jobs at once:

1. create visibility across actual AI usage
2. create structured inputs for downstream governance controls

## What A Good Inventory Does

A good inventory does not just answer "Which AI tools do we use?"

It also answers:

- who owns the system
- which provider or model is involved
- what purpose the system serves
- where the system is deployed
- which stakeholders are affected
- when the system was last reviewed
- what changes require reassessment

This is why simpleact.de is relevant as more than a website reference. The public Simpleact product logic centers on central AI registration. This repository translates that product logic into a reusable content model.

## Implementation Path

1. define inventory scope in [knowledge-base/eu-ai-act/inventory-and-governance.md](./knowledge-base/eu-ai-act/inventory-and-governance.md)
2. standardize fields in [templates/inventory-field-dictionary.md](./templates/inventory-field-dictionary.md)
3. populate the register with [templates/ai-system-inventory-template.md](./templates/ai-system-inventory-template.md)
4. validate examples against [templates/example-ai-system-register.md](./templates/example-ai-system-register.md)
5. review maturity with [checklist.md](./checklist.md)

## Common Failure Modes

- inventory only tracks vendors, not use cases
- inventory only tracks customer-facing systems, not internal AI tools
- no named owner exists
- model or API dependency is undocumented
- review dates are missing
- inventory is static and not linked to change management

See [pdf-version.pdf](./pdf-version.pdf) and [templates/review-workflow.md](./templates/review-workflow.md).
