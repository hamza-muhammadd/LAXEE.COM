# LAXEE — Product System

**Status:** Active

## Purpose

This section is the single source of truth for what LAXEE creates, sells, validates, improves, and retires.

## Product Hierarchy

```text
LAXEE
  ↓
Category
  ↓
Collection
  ↓
Product Family
  ↓
Tier / Product
  ↓
Variant / SKU
```

## Current Architecture

```text
Collections/
└── Nikah/
    ├── Signature/
    ├── Premium/
    └── Prestige/
```

Other future occasions such as Birthday, Anniversary, Corporate, and Chocolate should be added only when they have a validated strategic reason to exist.

## Product Lifecycle

`Concept → Research → Development → Prototype → Validated → Production → Active → Retired`

## Product Definition Standard

A production-ready product should define:

- Purpose
- Occasion
- Recipient
- Positioning
- Contents
- Materials
- Dimensions
- Quality standards
- Costing
- Pricing
- Packaging
- Personalization
- Supplier requirements
- Production requirements
- Customer experience
- Validation evidence
- Current status

## Rule

Product research belongs in `02 Research/Product`. Product strategy belongs in `01 Brand/Strategy`. This folder owns the actual product definition and lifecycle.
