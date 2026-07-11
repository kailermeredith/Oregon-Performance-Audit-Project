# Project Standards

**Oregon Performance Audit Project (OPAP)**

**Version:** 1.0

**Status:** Active

---

# Purpose

The Project Standards document establishes the operational standards used throughout the Oregon Performance Audit Project (OPAP). These standards promote consistency, transparency, and reproducibility across all project documentation, databases, reports, and research products.

All project materials should conform to these standards unless otherwise documented through an approved methodology revision.

---

# Guiding Principles

Project standards are intended to promote:

- Consistency
- Transparency
- Reproducibility
- Accuracy
- Maintainability
- Professional presentation

---

# Repository Organization

The repository follows a standardized directory structure.

```
docs/
methodology/
reports/
policy-briefs/
data/
figures/
references/
```

New folders should only be created when a recurring project need is identified.

---

# File Naming Conventions

File names should be descriptive, concise, and machine-readable.

## Markdown Documents

```
PROJECT_CHARTER.md
PROJECT_STANDARDS.md
METHODOLOGY.md
VISION.md
ROADMAP.md
```

Use uppercase for major governance documents.

---

## Reports

```
OPAP_Annual_Report_2027.pdf

OPAP_Implementation_Report_Transportation.pdf
```

---

## Datasets

```
Audit_Inventory.xlsx

Recommendation_Database.xlsx

Agency_Directory.xlsx
```

---

## Figures

```
Figure_01_Implementation_Rates.png

Figure_02_Agency_Comparison.png
```

---

# Database Standards

Each table shall contain:

- Primary key
- Clearly defined variables
- Standardized field names
- Controlled categorical values where applicable

Primary keys are immutable once assigned.

---

## Naming Conventions

Field names use:

```
snake_case
```

Examples:

```
audit_id

finding_id

recommendation_id

publication_date

implementation_status
```

Avoid spaces, punctuation, and abbreviations unless widely understood.

---

# Identifier Standards

Unique identifiers remain permanent.

Examples:

```
AUD-2014-001

FND-2014-001-01

REC-2014-001-01
```

Identifiers should never be reused.

---

# Controlled Vocabulary

Categorical variables shall use standardized values.

Examples include:

## Implementation Status

- Implemented
- Substantially Implemented
- Partially Implemented
- Not Implemented
- Unable to Determine

## Confidence

- High
- Moderate
- Low

## Review Status

- Pending
- Reviewed
- Final

---

# Source Documentation

Every implementation assessment should reference supporting evidence whenever possible.

Acceptable source types include:

- Audit reports
- Follow-up reports
- Agency documentation
- Legislative records
- Administrative rules
- Official websites

Personal communications should not be used as primary evidence.

---

# Citation Standards

Audit titles should match the official published title.

Agency names should follow official state naming conventions.

Dates should use ISO 8601 format:

```
YYYY-MM-DD
```

---

# Version Control

Semantic Versioning is used.

```
Major.Minor.Patch
```

Examples:

```
0.1.0

0.2.0

1.0.0
```

Major methodological revisions require a new release.

---

# Quality Assurance

Before publication, verify:

- Spelling and grammar
- Working hyperlinks
- Accurate citations
- Consistent terminology
- Database integrity
- Cross-reference validation

---

# Data Integrity

Project data should prioritize:

- Accuracy over completeness
- Documentation over assumption
- Evidence over inference

When evidence is insufficient, records should be coded as **Unable to Determine** rather than inferred.

---

# Documentation Standards

Every major document should include:

- Title
- Version
- Status
- Purpose
- Date of significant revision (when applicable)

---

# Release Standards

Each public release should include:

- Updated release notes
- Changelog entry
- Version tag
- Documentation updates
- Dataset revisions (if applicable)

---

# Future Revisions

This document is intended to evolve alongside OPAP.

Changes to project standards shall be documented through GitHub version releases and reflected in the project changelog.
