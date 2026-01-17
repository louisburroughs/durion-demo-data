# Durion Demo Data

Demo and Sample Data

## Overview

This component is part of the Durion ERP system built on the Moqui Framework.

## Purpose

Provide seed and demo data sets that make Durion components usable in development and demonstrations (reference entities, sample configuration, and representative transactional data).

## Scope

In scope:
- Seed data required for a runnable environment (lookups, reference codes, baseline entities)
- Demo scenarios and sample records to exercise UI screens and workflows
- Test-friendly fixtures that keep demos repeatable

Out of scope:
- Production data migration or production initialization
- Business logic or domain behavior (this component should remain data-focused)

## Structure

- `data/` - Seed and demo data
- `entity/` - Entity definitions
- `screen/` - UI screens and forms
- `service/` - Service definitions
- `src/` - Groovy/Java source code
- `template/` - Email and document templates
- `test/` - Test specifications

## Dependencies

See `component.xml` for component dependencies.

## Installation

This component is managed via `myaddons.xml` in the Moqui project root.

## License

Same as Durion project.

---

**Last Updated:** December 09, 2025
