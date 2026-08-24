# LAXEE — Company Operating System

> **Purpose:** This document defines how the LAXEE repository should be organized and used. It is the master map for the company knowledge system.

## 1. The LAXEE Information Model

Everything in the repository belongs to one of five types:

### A. Direction

What LAXEE is trying to become.

Examples: vision, mission, goals, roadmap, strategic priorities.

### B. Knowledge

What LAXEE has learned or defined.

Examples: research, customer insights, brand principles, product specifications.

### C. Decisions

What LAXEE has chosen after considering evidence.

Examples: positioning decisions, product-tier decisions, packaging decisions, supplier decisions.

Record major decisions in `00 Company/Key-Decisions.md`.

### D. Execution

What LAXEE is actively building or operating.

Examples: website, packaging production, supplier onboarding, launch tasks, SOPs.

### E. Archive

Old, replaced, rejected, or inactive material that should be retained for history but should not be treated as current truth.

---

# 2. Master Repository Structure

```text
LAXEE.COM/
│
├── README.md
│
├── 00 Company/
│   ├── README.md
│   ├── Operating-System.md
│   ├── Vision-Mission.md
│   ├── Goals.md
│   ├── Roadmap.md
│   └── Key-Decisions.md
│
├── 01 Brand/
│   ├── README.md
│   ├── Foundation/
│   │   └── Brand-Foundation.md
│   ├── Strategy/
│   │   ├── Market-Category.md
│   │   ├── Competitor-Analysis.md
│   │   ├── USP.md
│   │   ├── Value-Proposition.md
│   │   ├── Premium-Positioning.md
│   │   ├── Customer-Experience.md
│   │   └── Product-Architecture.md
│   ├── Identity/
│   │   ├── Logo/
│   │   ├── Colors/
│   │   ├── Typography/
│   │   ├── Photography/
│   │   └── Visual-Language.md
│   ├── Voice/
│   │   └── Brand-Voice.md
│   └── Guidelines/
│       └── Brand-Guidelines.md
│
├── 02 Research/
│   ├── README.md
│   ├── Market/
│   ├── Customer/
│   ├── Competitors/
│   ├── Category/
│   └── Insights/
│
├── 03 Products/
│   ├── README.md
│   ├── Architecture/
│   │   └── Product-Architecture.md
│   ├── Nikah/
│   │   ├── README.md
│   │   ├── Signature/
│   │   │   └── Product-Spec.md
│   │   ├── Premium/
│   │   │   └── Product-Spec.md
│   │   └── Prestige/
│   │       └── Product-Spec.md
│   └── Future/
│
├── 04 Packaging/
│   ├── README.md
│   ├── Concepts/
│   ├── Specifications/
│   ├── Materials/
│   ├── Production/
│   └── Experience/
│
├── 05 Suppliers/
│   ├── README.md
│   ├── Packaging/
│   ├── Products/
│   ├── Manufacturing/
│   ├── Logistics/
│   └── Supplier-Database.md
│
├── 06 Website/
│   ├── README.md
│   ├── Strategy/
│   ├── Content/
│   ├── UX/
│   ├── Design/
│   ├── Development/
│   └── SEO/
│
├── 07 Operations/
│   ├── README.md
│   ├── SOPs/
│   ├── Quality/
│   ├── Fulfillment/
│   ├── Customer-Service/
│   └── Launch/
│
└── 99 Archive/
    ├── Deprecated/
    ├── Rejected/
    └── Superseded/
```

---

# 3. What Each Department Owns

## 00 Company — Direction & Governance

Owns the company-level truth.

Put here:

- Vision
- Mission
- Goals
- Roadmap
- Major decisions
- Company-level principles

Do not put detailed brand design, product specifications, or research here.

## 01 Brand — Brand System

Owns how LAXEE is positioned, expressed, and experienced as a brand.

### Foundation

Why LAXEE exists and what it stands for.

### Strategy

Where LAXEE competes and why customers should choose it.

### Identity

How LAXEE looks.

### Voice

How LAXEE communicates.

### Guidelines

The practical rules that ensure consistency.

## 02 Research — Evidence

Research answers:

> **What do we know?**

Store evidence here before turning it into a strategic decision.

Research should include source, date, observation, implication, and confidence where practical.

## 03 Products — What LAXEE Sells

Every product family should eventually have:

- Product purpose
- Target recipient
- Occasion
- Positioning
- Contents
- Materials
- Dimensions
- Quality standard
- Pricing
- Packaging relationship
- Personalization
- Production requirements
- Customer experience
- Status

Recommended product status values:

`Concept → Research → Development → Prototype → Validated → Production → Active → Retired`

## 04 Packaging — Physical Experience

Packaging is not merely a container.

It covers:

- Concept
- Structure
- Materials
- Visual application
- Protection
- Opening sequence
- Production
- Quality control
- Experience

## 05 Suppliers — Supply Network

Each supplier record should eventually contain:

- Supplier name
- Category
- Location
- Contact
- Capabilities
- MOQ
- Pricing
- Lead time
- Quality assessment
- Samples
- Reliability
- Payment terms
- Status
- Last verified date

Recommended supplier status:

`Discovered → Contacted → Sampled → Evaluated → Approved → Active → Paused → Rejected`

## 06 Website — Digital Commerce

The website should be treated as a product, not a random collection of pages.

It contains:

- Strategy
- Information architecture
- UX
- Design
- Content
- Development
- SEO
- Performance
- Analytics

## 07 Operations — Delivery System

This is where LAXEE becomes repeatable.

Document:

- SOPs
- Quality control
- Fulfillment
- Customer service
- Launch procedures
- Returns/refunds when defined
- Internal checklists

## 99 Archive — Historical Material

Never let obsolete documents compete with current truth.

Move them here with a short note explaining what replaced them when appropriate.

---

# 4. Rules for Documents

## Rule 1 — One Source of Truth

Do not maintain the same fact in multiple documents unless one document is explicitly summarizing the authoritative source.

## Rule 2 — Research Before Decisions

Research contains evidence. Strategy contains interpretation. Decisions contain the chosen direction.

## Rule 3 — Current vs Historical

If a document is no longer current, archive it. Do not leave two conflicting versions active.

## Rule 4 — No Empty Placeholder Documents

Create a file when there is meaningful content to maintain it. Empty files create false structure.

## Rule 5 — Avoid Excessive Numbering

Use numbers for major repository sections. Use normal names inside them unless order is genuinely important.

## Rule 6 — Every Major Document Has Status

Use:

- `Draft`
- `In Review`
- `Approved`
- `Active`
- `Superseded`
- `Archived`

## Rule 7 — Every Strategic Document Has Ownership

At minimum record:

- Owner
- Status
- Version
- Last Updated

## Rule 8 — Decisions Need Reasons

Do not only record what was decided. Record why.

## Rule 9 — Product Documents Must Be Actionable

A product document should eventually be sufficient for another person to understand what is being made and how it should be produced or sold.

## Rule 10 — Keep the Repository Readable

A new team member should understand the LAXEE system from the root README without needing the founder to explain the folder structure.

---

# 5. Current Migration Map

The existing repository already contains strong material. Do not rewrite everything from zero.

### Move / rename conceptually

`01 Brand/01 Foundation/` → keep as `01 Brand/Foundation/`

`01 Brand/02 Strategy/` → keep as `01 Brand/Strategy/`

`01 Brand/03 Identity/` → keep as `01 Brand/Identity/`

`01 Brand/04 Voice/` → keep as `01 Brand/Voice/`

`01 Brand/Brand-Guidelines.md` → `01 Brand/Guidelines/Brand-Guidelines.md`

`02 Packaging/` → `04 Packaging/`

`03 Products/` → `03 Products/`

`Research/` → `02 Research/`

`Suppliers/` → `05 Suppliers/`

`Website/` → `06 Website/`

Create `07 Operations/` for operational documentation that does not belong to products, packaging, suppliers, or website.

Create `99 Archive/` for replaced material.

---

# 6. Existing Brand Strategy Cleanup

The current Brand Strategy documents overlap. Keep the ideas, but give each document one job:

| Document | Single Job |
|---|---|
| Market Category | Define the category LAXEE competes in |
| Competitor Analysis | Show alternatives and competitive gaps |
| USP | Define the distinctive reason to choose LAXEE |
| Value Proposition | Define customer value by audience/need |
| Premium Positioning | Define how premium positioning is built |
| Customer Experience | Define the experience principles and journey |
| Product Architecture | Define how products and collections are structured |

Do not repeat the complete Brand Foundation in every strategy document.

---

# 7. Product System

The product hierarchy should be:

```text
LAXEE
  ↓
Product Category
  ↓
Product Family
  ↓
Collection / Tier
  ↓
Specific Product
  ↓
SKU / Variant
```

For the current Nikah system:

```text
Nikah
├── Signature
├── Premium
└── Prestige
```

Each tier should have a clear reason to exist. Avoid making tiers different only by adding more items.

---

# 8. GitHub Workflow

GitHub should separate documentation from tasks.

### Markdown documents

Answer:

> What is true, defined, or decided?

### Issues

Answer:

> What needs to be done?

### Pull Requests

Answer:

> What changed and why?

### Commits

Answer:

> What was actually changed in the repository?

Recommended issue labels:

- `company`
- `brand`
- `research`
- `product`
- `packaging`
- `supplier`
- `website`
- `operations`
- `decision`
- `urgent`

---

# 9. The Golden Rule

Before creating a new document, ask:

1. What question does this document answer?
2. Which department owns that answer?
3. Does an existing document already answer it?
4. Is this knowledge, a decision, or an execution task?
5. Will someone else understand and maintain it later?

If an existing document already owns the answer, update that document instead of creating another one.

---

**Status:** `ACTIVE`

**Owner:** LAXEE

**Version:** `1.0`

**Last Updated:** August 2026
