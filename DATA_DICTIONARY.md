# Data Dictionary

This document defines the variables used throughout the Oregon Performance Audit Project.

---

## Audit Information

| Variable | Type | Description |
|----------|------|-------------|
| Audit_ID | Text | Official audit identifier assigned by the Oregon Secretary of State |
| Audit_Title | Text | Full audit title |
| Publication_Date | Date | Audit publication date |
| Agency | Text | Primary audited agency |
| Audit_Type | Text | Performance Audit |

---

## Recommendation Information

| Variable | Type | Description |
|----------|------|-------------|
| Recommendation_ID | Text | Unique recommendation identifier |
| Recommendation_Number | Integer | Recommendation number within audit |
| Recommendation_Text | Text | Original recommendation language |
| Recommendation_Category | Text | Functional category |
| Responsible_Entity | Text | Agency responsible for implementation |

---

## Implementation

| Variable | Type | Description |
|----------|------|-------------|
| Implementation_Status | Categorical | Implemented, Partially Implemented, Not Implemented, Unable to Determine |
| Evidence_Source | Text | Documentation supporting coding decision |
| Evidence_Date | Date | Date of supporting evidence |
| Confidence_Level | Ordinal | High, Moderate, Low |

---

## Coding Metadata

| Variable | Type | Description |
|----------|------|-------------|
| Primary_Coder | Text | Individual completing coding |
| Coding_Date | Date | Date coded |
| Review_Status | Text | Pending, Reviewed, Final |
| Notes | Text | Additional observations |
