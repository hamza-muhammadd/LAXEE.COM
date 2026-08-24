# Research Migration Audit

**Status:** Active
**Purpose:** Record what was found in the legacy `Research/` area and what should happen to it.

## Audit Principle

Do not delete research simply because it is old or imperfect. Delete only when it is empty, duplicated, clearly superseded, or has no durable informational value.

## Deleted During First Cleanup

### Empty legacy placeholders

Removed empty README placeholders from:

- `Research/01 Market-Research/`
- `Research/02 Competitor-Research/`
- `Research/03 Customer-Research/`
- `Research/05 Supplier-Research/`
- `Research/06 Pricing-Research/`
- `Research/07 Packaging-Research/`

These contained no research content.

### Empty project placeholders

Removed:

- `Research/04 Product-Research/01 Nikah-Signiture-Box/06-Pricing-Research/comingsoon.md`
- `Research/04 Product-Research/01 Nikah-Signiture-Box/08-Packaging-Research/comingsoon.md`
- `Research/04 Product-Research/01 Nikah-Signiture-Box/09-Validation/comingsoon.md`

These contained no useful information.

### Duplicate product research

Removed:

- `Research/04 Product-Research/001 Egyptian-Chocolate-Demo.md`

A newer, more developed Egyptian Chocolate research record already exists at `Research/Product-Research/001-Egyptian-Chocolate.md`.

## Keep — Substantive Research

The following material contains useful research and should be preserved during migration:

### Nikah Signature Box — Market Analysis

`Research/04 Product-Research/01 Nikah-Signiture-Box/01-Market-Analysis/Market-Analysis.md`

**Disposition:** KEEP → migrate to `02 Research/Market/` or a Nikah research sub-area.

Contains market opportunity, Bangladesh gifting context, pricing bands, personalization trends, e-commerce, risks, opportunities, and a preliminary conclusion.

### Nikah Signature Box — Customer Research

`Research/04 Product-Research/01 Nikah-Signiture-Box/02-Customer-Research/Customer-Research.md`

**Disposition:** KEEP → migrate to `02 Research/Customers/`.

Contains buyer/recipient distinction, customer hypotheses, jobs-to-be-done, pain points, expectations, purchase triggers/barriers, willingness-to-pay questions, research methods, and persona hypotheses.

### Nikah Signature Box — Competitor Analysis

`Research/04 Product-Research/01 Nikah-Signiture-Box/03-Competitor-Analysis/Competitor-Analysis-all-together.md`

**Disposition:** KEEP → migrate to `02 Research/Competitors/`.

Contains six competitor profiles, pricing observations, strengths/weaknesses, experience analysis, and LAXEE opportunity hypotheses.

**Important:** It is research, not approved brand strategy. Strategic conclusions must be validated and then reflected in `01 Brand/Strategy/` or `00 Company/Key-Decisions.md`.

### Nikah Signature Box — Product Selection

`Research/04 Product-Research/01 Nikah-Signiture-Box/04-Product-Selection/Product-Selection.md`

**Disposition:** KEEP → migrate to `02 Research/Product/`.

Contains product-role architecture, candidate pools, screening criteria, and candidate scoring logic.

**Important:** Candidate lists are not final product approvals.

### Nikah Signature Box — Product Research

`Research/04 Product-Research/01 Nikah-Signiture-Box/ 05-Product-Research/Product-Research.md`

**Disposition:** KEEP → migrate to `02 Research/Product/`.

Contains product definition, composition research, specifications, customer value, quality requirements, differentiation, and validation logic.

**Cleanup needed during migration:** remove duplicated introductory sections and separate research hypotheses from approved product specifications.

### Nikah Signature Box — Supplier & Sourcing Research

`Research/04 Product-Research/01 Nikah-Signiture-Box/07-Supplier-Research/Supplier-Sourcing.md`

**Disposition:** KEEP → migrate to `05 Supply Chain/` for active supplier records and `02 Research/Suppliers/` for market/sourcing research.

The current document is a framework, not an approved supplier database.

### Egyptian Chocolate Product Research

`Research/Product-Research/001-Egyptian-Chocolate.md`

**Disposition:** KEEP → migrate to `02 Research/Product/`.

This is useful as an initial candidate record, but its financial and market figures are explicitly preliminary and must remain marked as unverified until independently confirmed.

## Delete / Archive Later

### Final Decision Empty Structure

`Research/04 Product-Research/01 Nikah-Signiture-Box/10-Final-Decision/`

The currently visible contents are empty. Once verified that no hidden substantive files exist, this structure should be removed. Final decisions belong in the product project and `00 Company/Key-Decisions.md` rather than in an empty research folder.

### Legacy Top-Level Research Folder

After the substantive research above has been migrated and verified, delete the entire legacy `Research/` area.

## New Source of Truth

All new research must be created under:

`02 Research/`

Active supplier records belong under:

`05 Supply Chain/`

Approved product definitions belong under:

`03 Products/`

Strategic conclusions belong under:

`01 Brand/Strategy/` or `00 Company/Key-Decisions.md`

## Current Decision

**Legacy Research:** KEEP TEMPORARILY FOR MIGRATION

**New Research:** USE `02 Research/` ONLY

**Cleanup Strategy:** Preserve evidence, remove duplication, separate evidence from decisions, then remove the legacy area.
