# Lemobb Contracts

This repository contains the canonical contract definitions used across the Lemobb platform.

Contracts define how applications, plans, and events are modeled and communicated across services, agents, and third-party integrations. They are intentionally technology-agnostic and versioned to support long-term scalability.

## Purpose

- Establish a single source of truth for platform interoperability
- Enable decoupled, event-driven architectures
- Support automation, analytics, and AI-driven orchestration
- Provide a stable foundation for SDKs, integrations, and ecosystem growth

## Structure

### `app-types/`
Defines the supported application models within the Lemobb ecosystem (e.g. marketplace, social, SaaS).

### `plans/`
Defines pricing, feature access, and monetization logic applicable to app types.

### `events/`
Defines the event taxonomy and schemas used across the platform for orchestration, analytics, and automation.

## Versioning

All contracts follow semantic versioning:
- `v1` → stable, backward-compatible
- `v2+` → breaking changes or major architectural shifts

New versions never overwrite previous ones.

## Design Principles

- Explicit over implicit
- Forward-compatible schemas
- No infrastructure or implementation details
- Contracts describe **what**, never **how**

## Public & Open

This repository is public by design.
It represents Lemobb’s commitment to transparency, interoperability, and ecosystem-driven growth.
