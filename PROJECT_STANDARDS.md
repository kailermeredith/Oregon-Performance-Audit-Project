# OPAP Project Standards
Version 1.0
Status: Active
Last Updated: July 2026

---

# 1. Purpose

This document establishes the development, documentation, and data management standards for the Oregon Performance Audit Project (OPAP).

Its purpose is to ensure that OPAP remains transparent, reproducible, internally consistent, and maintainable over time.

---

# 2. Core Principles

OPAP is governed by the following principles.

## Accuracy

Record what the audit states.

Do not embellish, speculate, or infer unsupported conclusions.

---

## Consistency

Apply identical coding standards to every audit.

No agency, subject area, or audit receives special treatment.

---

## Transparency

Every analytical decision should be traceable to:

- the original audit
- the Coding Manual
- the Decisions Log

---

## Reproducibility

A second analyst following the Coding Manual should reach substantially similar coding decisions.

---

## Simplicity

Prefer solutions that are easy to understand and maintain.

Avoid unnecessary complexity in database design or coding procedures.

---

# 3. Repository Organization

The repository follows the structure below.

docs/
- CODING_MANUAL.md
- METHODOLOGY.md
- PROJECT_STANDARDS.md
- DECISIONS.md
- ROADMAP.md

data/
- raw/
- processed/
- reference/

database/
- schema
- exports

assets/
- diagrams
- figures
- templates

---

# 4. Naming Conventions

## Audits

AUD-YYYY-###

Example:

AUD-2010-001

---

## Findings

AUD-YYYY-001-F01

---

## Recommendations

AUD-YYYY-001-R01

---

## Sources

SRC-0001

---

## Root Causes

RC01

RC02

...

---

# 5. Database Standards

Each data element shall have one authoritative location.

Duplicate information should be avoided whenever possible.

Relationships should be represented using identifiers rather than repeated text.

Database normalization is preferred when it improves consistency and maintainability.

---

# 6. Documentation Standards

Every major methodological change shall update:

- DECISIONS.md
- the affected documentation
- the version number (when appropriate)

Historical decisions should never be deleted.

---

# 7. Version Control

Use semantic versioning.

Major versions reflect methodological or schema changes.

Minor versions reflect new functionality.

Patch versions reflect corrections and documentation updates.

Example:

v1.0.0

v1.1.0

v1.1.1

---

# 8. Git Commit Standards

Commit messages should be concise and descriptive.

Examples:

Add AUD-2010-001 findings

Update Coding Manual to v1.0

Populate agencies table

Complete corpus screening for 2010

Avoid generic commit messages such as:

"Update"

"Changes"

"Misc fixes"

---

# 9. Quality Assurance

Before closing an audit:

✓ Metadata complete

✓ Findings extracted

✓ Recommendations extracted

✓ Root causes assigned

✓ Sources verified

✓ Internal consistency confirmed

---

# 10. Research Integrity

OPAP is intended to support objective analysis.

Analysts shall:

- preserve original audit meaning
- document uncertainty
- avoid advocacy within coding
- distinguish evidence from interpretation
- prioritize reproducibility over speed

---

# 11. Long-Term Maintenance

Future development should prioritize:

- data quality
- documentation
- reproducibility
- scalability

Feature additions should not compromise methodological consistency.

The database is intended to evolve gradually through documented decisions rather than frequent redesign.
