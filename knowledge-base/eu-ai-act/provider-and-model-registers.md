# Provider And Model Registers

This document explains how AI inventory records should connect to provider and model register logic.

## Why It Matters

A modern AI inventory is not complete when it only lists a system name and owner. It should also capture which provider, which model family, which hosting arrangement, which contractual dependencies, and which review signals apply.

## Core Register Fields

- provider name
- model or model family
- version or release identifier when known
- hosting arrangement
- contractual context such as DPA, AVV, SCC, or procurement note
- review trigger when provider or model changes
- linked evidence or due-diligence record

## Governance Value

This linkage matters because provider and model changes often trigger reclassification, documentation updates, privacy review, or incident follow-up. The inventory should therefore be the place where those dependencies become visible.
