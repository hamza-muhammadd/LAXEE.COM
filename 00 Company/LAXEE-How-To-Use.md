# LAXEE — How to Use the Operating System

**Status:** ACTIVE
**Owner:** LAXEE
**Purpose:** This is the practical manual for using the LAXEE repository after the restructuring.

---

# 1. First: You Do Not Need to Understand the Old Repository

The old repository was your thinking workspace. It contains useful ideas, research, experiments, duplicates, and unfinished material.

The new structure is the organized company system.

When in doubt, start here and follow the map below.

---

# 2. The One-Minute Map

| Question | Go Here |
|---|---|
| What is LAXEE trying to become? | `00 Company` |
| What does the brand stand for? | `01 Brand` |
| What do we know from evidence? | `02 Research` |
| What are we making? | `03 Products` |
| How should it be packaged? | `04 Packaging` |
| Who/how do we source and manufacture? | `05 Supply Chain` |
| What should the customer experience? | `06 Customer Experience` |
| How does the website work? | `07 Website & Digital` |
| How do we repeatedly deliver the experience? | `08 Operations` |
| How do we attract and retain customers? | `09 Growth` |
| Does the business make commercial sense? | `10 Finance & Commercial` |
| Who owns what and how do we govern? | `11 People & Governance` |
| What are we actively building right now? | `12 Projects` |
| Is this old/replaced material? | `99 Archive` |

---

# 3. The Golden Workflow

Do not jump directly from an idea to execution when the idea affects the company materially.

Use:

```text
QUESTION
  ↓
RESEARCH
  ↓
INSIGHT
  ↓
HYPOTHESIS
  ↓
DECISION
  ↓
STRATEGY
  ↓
BUILD
  ↓
OPERATE
  ↓
MEASURE
  ↓
LEARN
```

Not every small task needs every step. Use the full chain for important decisions.

---

# 4. Where New Information Goes

## If you discover a fact

Put the evidence in `02 Research`.

Example:

> A competitor sells personalized Nikah boxes at a certain price.

That is research evidence.

## If you interpret the evidence

Put the resulting strategic interpretation in the appropriate Strategy or Insights document.

Example:

> Customers appear willing to pay more when personalization and presentation are perceived as meaningful.

That is an insight/hypothesis until validated.

## If LAXEE chooses something

Record the decision in `00 Company/Key-Decisions.md` when it is strategically important.

Example:

> LAXEE will launch Nikah Signature before expanding to additional occasions.

That is a decision.

## If you need to make it

Create a GitHub Issue or put the work inside the relevant `12 Projects` project.

Example:

> Create three prototype configurations for Nikah Signature.

That is execution.

---

# 5. The Difference Between Research, Strategy, and Product

This is the most important distinction in the whole system.

### Research

**What do we know?**

### Strategy

**What does the evidence mean, and what position should LAXEE take?**

### Decision

**What are we choosing?**

### Product

**What exactly are we building?**

### Operations

**How do we repeatedly deliver it?**

Never put all five into one giant document.

---

# 6. How to Use the Nikah System

Nikah is the first major product-development system.

Use this sequence:

```text
02 Research
   ↓
Market
Customers
Competitors
Product
Pricing
Suppliers
   ↓
Insights
   ↓
03 Products / Nikah
   ↓
Signature → Premium → Prestige
   ↓
04 Packaging
   ↓
06 Customer Experience
   ↓
05 Supply Chain
   ↓
08 Operations
   ↓
Launch
```

Do not create new random Nikah research folders.

If it is evidence, it belongs in Research.

If it defines the product, it belongs in Products.

If it defines the package, it belongs in Packaging.

If it defines the supplier relationship, it belongs in Supply Chain.

---

# 7. How to Create a New Product

Use this sequence:

1. Create a product question/hypothesis.
2. Research the market and customer need.
3. Check competitors and substitutes.
4. Check feasibility and suppliers.
5. Estimate cost and price.
6. Decide whether the opportunity is worth pursuing.
7. Create the Product Brief.
8. Develop the prototype.
9. Validate it.
10. Finalize specification.
11. Define packaging.
12. Define customer experience.
13. Prepare operations.
14. Launch.
15. Measure.
16. Improve or retire.

---

# 8. How to Create a New Research Document

Use this minimum structure:

```markdown
# Title

Status: Draft / Active / Superseded
Owner: LAXEE
Date:

## Research Question

## Why It Matters

## Method / Sources

## Evidence

## Findings

## Interpretation

## Confidence

## Implications

## Open Questions

## Next Action
```

Never present an assumption as a verified fact.

---

# 9. How to Make a Strategic Decision

For major decisions, use:

```text
Decision
Why
Evidence
Alternatives considered
Risks
Expected impact
Owner
Date
Review condition
```

Record major decisions in `00 Company/Key-Decisions.md`.

A decision can later be reversed. If it is reversed, record the new decision and why.

---

# 10. How to Use GitHub Issues

Use an Issue when something needs to be done.

Good:

> Validate Nikah Signature packaging prototype with 3 production suppliers.

Bad:

> Packaging

Issues should have:

- Objective
- Context
- Owner
- Deliverable
- Acceptance criteria
- Dependencies
- Deadline when necessary

Recommended labels:

`company`, `brand`, `research`, `product`, `packaging`, `supply-chain`, `customer-experience`, `website`, `operations`, `growth`, `finance`, `governance`, `project`, `decision`

---

# 11. How to Use Projects

Use `12 Projects` for temporary initiatives.

A project has:

- Start
- Outcome
- Owner
- Scope
- Deadline
- Completion condition

When completed, the permanent knowledge created by the project must move to the correct operating section.

The project itself can then be archived.

---

# 12. What NOT to Do

Do not:

- Create a new top-level folder because you are unsure where something belongs.
- Duplicate the same strategy in multiple files.
- Put research inside Product Specifications.
- Put decisions inside raw research.
- Treat a hypothesis as a fact.
- Keep obsolete documents active.
- Create empty placeholder files.
- Make one huge document that tries to contain an entire department.
- Change major strategy without recording the decision.

---

# 13. When You Are Confused

Use this decision tree:

```text
Is it evidence?
 └─ YES → 02 Research

Is it a brand/market strategic choice?
 └─ YES → 01 Brand / Strategy

Is it an important company decision?
 └─ YES → 00 Company / Decisions

Is it a product definition?
 └─ YES → 03 Products

Is it packaging?
 └─ YES → 04 Packaging

Is it sourcing/manufacturing?
 └─ YES → 05 Supply Chain

Is it customer experience?
 └─ YES → 06 Customer Experience

Is it website/digital?
 └─ YES → 07 Website & Digital

Is it a repeatable process?
 └─ YES → 08 Operations

Is it marketing/growth?
 └─ YES → 09 Growth

Is it financial/commercial?
 └─ YES → 10 Finance & Commercial

Is it people/ownership/governance?
 └─ YES → 11 People & Governance

Is it temporary work?
 └─ YES → 12 Projects

Is it obsolete?
 └─ YES → 99 Archive
```

---

# 14. The Weekly LAXEE Operating Rhythm

## Daily

Work on the active project/issues. Do not reorganize the whole company every day.

## Weekly

Review:

- Active projects
- Blocked work
- New research
- New decisions
- Product progress
- Supplier progress
- Customer feedback
- Important metrics

## Monthly

Review:

- Goals
- Roadmap
- Product portfolio
- Financial health
- Customer learning
- Growth performance
- Operational problems
- Strategic assumptions

## Quarterly

Ask:

1. What did we learn?
2. What changed?
3. What should we stop?
4. What should we continue?
5. What should we start?
6. Which assumptions are now proven?
7. Which assumptions are still uncertain?
8. What is the next strategic priority?

---

# 15. The LAXEE Master Loop

```text
          ┌──────────────┐
          │   DIRECTION  │
          └──────┬───────┘
                 ↓
          ┌──────────────┐
          │   RESEARCH   │
          └──────┬───────┘
                 ↓
          ┌──────────────┐
          │   INSIGHTS   │
          └──────┬───────┘
                 ↓
          ┌──────────────┐
          │  DECISIONS   │
          └──────┬───────┘
                 ↓
          ┌──────────────┐
          │    BUILD     │
          └──────┬───────┘
                 ↓
          ┌──────────────┐
          │   OPERATE    │
          └──────┬───────┘
                 ↓
          ┌──────────────┐
          │   MEASURE    │
          └──────┬───────┘
                 ↓
          ┌──────────────┐
          │    LEARN     │
          └──────┬───────┘
                 │
                 └──────────────→ IMPROVE
                                      │
                                      └──→ RESEARCH
```

This loop is the LAXEE operating system.

---

# 16. Current Priority

Do not try to build every future department at once.

Current strategic sequence:

```text
1. Company Foundation
2. Brand Foundation & Positioning
3. Research Consolidation
4. Nikah Product Development
5. Packaging Development
6. Supplier Validation
7. Customer Experience
8. Website & Commerce
9. Operations
10. Launch
11. Growth
12. Expansion
```

The current product focus should remain narrow until the first system is validated.

---

# 17. The Rule That Protects the Whole System

Before creating or editing a document, ask:

> **What question does this document own?**

If you cannot answer that question in one sentence, the document probably needs to be merged, split, renamed, or deleted.

---

# 18. Final Mental Model

You only need to remember this:

**Company tells us where we are going.**

**Brand tells us who we are.**

**Research tells us what we know.**

**Decisions tell us what we choose.**

**Products tell us what we make.**

**Packaging tells us how it is presented.**

**Customer Experience tells us how it feels.**

**Supply Chain tells us how it is sourced and produced.**

**Operations tells us how we deliver it repeatedly.**

**Website tells us how people experience LAXEE digitally.**

**Growth tells us how we reach people.**

**Finance tells us whether the business works economically.**

**Projects tell us what we are actively changing.**

**Archive tells us what happened before.**

That is the complete LAXEE operating system.
