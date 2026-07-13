# OPAP Coding Manual
Version 1.0
Status: Active
Last Updated: July 2026

---

# 1. Purpose

The Oregon Performance Audit Project (OPAP) is a structured research database that transforms Oregon Secretary of State performance audits into standardized, analyzable data.

The objective is to produce a transparent, reproducible dataset suitable for policy analysis, legislative oversight, academic research, and public administration studies.

This manual establishes the procedures every analyst shall follow when extracting information from audit reports.

---

# 2. Guiding Principles

All coding shall follow these principles.

1. Primary-source first.
2. Preserve official wording whenever practical.
3. Separate observation from interpretation.
4. Document uncertainty.
5. Apply coding rules consistently.
6. Maintain one source of truth for every data element.

---

# 3. Workflow

Every audit shall be processed in the following order.

1. Corpus Screening
2. Audit Intake
3. Finding Extraction
4. Recommendation Extraction
5. Root Cause Coding
6. Action Type Coding
7. Source Documentation
8. Quality Assurance
9. Final Review

Do not skip steps.

---

# 4. Corpus Screening

Include reports that:

• evaluate government performance
• evaluate management or operations
• evaluate economy, efficiency, or effectiveness
• contain findings
• contain recommendations

Exclude:

• Financial Statement Audits
• Single Audits
• Financial Reviews
• Agreed-Upon Procedures
• Other financial assurance engagements

When classification is uncertain:

Status = Needs Review

Review the report before making a final determination.

---

# 5. Audit Intake

Complete one record in the audits table.

Required fields include:

• OPAP ID
• Official Report Number
• Title
• Publication Date
• Fiscal Year
• Agency
• Audit Type

Optional fields may be completed later.

---

# 6. Findings

Each finding shall receive a unique identifier.

Example:

AUD-2010-001-F01

Each finding shall include:

• concise summary
• supporting evidence
• page reference
• severity (if applicable)

Do not combine multiple findings into one record.

---

# 7. Recommendations

Each recommendation receives a unique identifier.

Example:

AUD-2010-001-R01

Each recommendation must link to its parent finding.

One finding may contain multiple recommendations.

---

# 8. Root Cause Coding

Assign every root cause explicitly supported by the report.

Multiple root-cause codes are permitted.

Do not infer causes unsupported by audit evidence.

---

# 9. Action Type Coding

Each recommendation shall receive one primary action type.

Examples include:

• Governance
• Policy
• Organizational
• Financial
• Operational
• Technology
• Human Resources
• Legislative

---

# 10. Recommendation Visibility

Recommendations shall be classified as:

Public

Confidential Reference

Mixed

This accommodates audits that contain confidential supporting reports.

---

# 11. Confidence Rating

Every analytical coding decision receives a confidence rating.

High
The report explicitly supports the coding.

Medium
The report strongly supports the coding.

Low
Interpretation required.

---

# 12. Sources

Every coding decision shall reference the original audit.

Whenever possible include:

• report number
• page number
• quotation or summary

---

# 13. Quality Assurance

Before an audit is marked Complete, verify:

✓ Audit record complete

✓ Findings entered

✓ Recommendations entered

✓ Root causes assigned

✓ Sources documented

✓ IDs verified

✓ Internal consistency confirmed

---

# 14. Version Control

Methodological changes shall not be made directly within this manual.

All revisions must first be documented in DECISIONS.md.

After approval, the manual shall be updated and assigned a new version number.
