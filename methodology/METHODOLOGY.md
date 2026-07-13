# OPAP Methodology
Version 1.0
Status: Active
Last Updated: July 2026

---

# 1. Purpose

The Oregon Performance Audit Project (OPAP) is a structured research initiative that converts Oregon Secretary of State performance audits into a standardized relational database for policy analysis, oversight research, and academic study.

Rather than treating audit reports as isolated publications, OPAP extracts findings, recommendations, implementation information, and analytical metadata into a consistent data model.

---

# 2. Research Objectives

The project seeks to:

• Create a comprehensive inventory of Oregon performance audits.

• Standardize audit findings and recommendations.

• Identify recurring organizational and policy problems.

• Analyze implementation trends over time.

• Support evidence-based legislative and administrative reform.

---

# 3. Data Sources

The primary data source is:

Oregon Secretary of State
Audits Division
Official Performance Audit Reports

Secondary sources include:

• audit follow-up reports
• agency implementation reports
• legislative testimony
• administrative responses
• official supporting documentation

Only primary-source information is used for coding.

---

# 4. Unit of Analysis

The primary unit of analysis is the individual audit report.

Within each audit, OPAP extracts:

Audit
↓

Finding
↓

Recommendation
↓

Analytical Coding

This hierarchical structure preserves the relationships between observations and recommendations while allowing quantitative analysis.

---

# 5. Corpus Construction

Reports are screened before inclusion.

Included reports must:

• evaluate government performance

• evaluate management, operations, economy, efficiency, or effectiveness

• contain findings

• contain recommendations

Excluded reports include:

• Financial Statement Audits

• Single Audits

• Financial Reviews

• Agreed-Upon Procedures

• Other financial assurance engagements

Classification is based on report content rather than metadata alone.

---

# 6. Data Extraction Workflow

Every report follows the same workflow.

Official Report

↓

Audit Intake

↓

Finding Extraction

↓

Recommendation Extraction

↓

Root Cause Coding

↓

Action Type Coding

↓

Quality Assurance

↓

Production Database

No audit bypasses this process.

---

# 7. Coding Philosophy

OPAP distinguishes between:

Observation

Interpretation

The database records what auditors concluded.

Analytical coding adds standardized categories while preserving the original audit language.

Whenever uncertainty exists, the original report takes precedence.

---

# 8. Root Cause Analysis

Root causes are assigned only when supported by audit evidence.

Multiple root causes may be assigned to a single recommendation.

Root causes are stored in a relational table to preserve many-to-many relationships.

---

# 9. Quality Assurance

Every audit undergoes review before completion.

Quality checks include:

✓ audit metadata

✓ finding completeness

✓ recommendation completeness

✓ source verification

✓ identifier validation

✓ coding consistency

---

# 10. Version Control

Methodological revisions are documented in DECISIONS.md.
Database schema revisions are documented in DECISIONS.md
---
# 11. Limitations

OPAP records information contained within published audit reports.

The database does not independently verify audit findings.

Confidential recommendations and supporting evidence are coded only when publicly referenced.

Coding decisions reflect standardized interpretation of audit language and may evolve as the coding manual is refined.

The project is intended to support comparative analysis rather than replace the original audit reports.
