# SharedLens Issue Tracker

**SharedLens** is a product data governance platform built by [Noetic Data, LLC](https://noeticdata.com). It helps enterprises standardize, classify, and migrate product data across PLM systems — without replacing the systems themselves.

> *Standardize the data, not the PLM.*

---

## What is SharedLens?

SharedLens provides a governed workspace where data stewards, engineers, and migration teams collaborate to:

- **Load** product data from CSV, Excel, or ARAS AML/XML files
- **Map** source attributes to target schemas with AI-assisted suggestions
- **Validate** data quality before migration using automated checks
- **Classify** parts into structured hierarchies for better governance and search
- **Promote** clean, validated data from staging to master
- **Export** ARAS-compatible AML files for bulk import into Innovator

### Key Capabilities

| Capability | Description |
|---|---|
| **Three-Zone Architecture** | Raw (as-imported) → Staging (review & map) → Master (validated & governed) |
| **AI-Assisted Mapping** | Automatic attribute matching with confidence scores — you confirm or override |
| **Classification Structures** | Organize parts by category so each item type shows only relevant attributes |
| **Relationship Management** | BOM, Vendor, and Manufacturer Part relationships with validation dashboards |
| **Multi-Lens Views** | See the same data from Engineering, Procurement, or Manufacturing perspectives |
| **Data Quality Scoring** | Completeness and validation scoring with priority-based thresholds |
| **Work Packages** | Organize migration work into manageable, trackable chunks |
| **Full Audit Trail** | Every change is logged — who, what, when, and why |

---

## How to Use This Issue Tracker

This repository is the central place to report bugs, request features, and track project work for SharedLens.

### Reporting a Bug

1. Click **[New Issue](../../issues/new)**
2. Use a clear, descriptive title (e.g., "Staging grid doesn't save edits on Tab key")
3. Include:
   - **What you expected** to happen
   - **What actually happened**
   - **Steps to reproduce** (be specific)
   - **Screenshots** if helpful
   - **Browser and OS** (e.g., Chrome 120 on Windows 11)

### Requesting a Feature

1. Click **[New Issue](../../issues/new)**
2. Describe the problem you're trying to solve, not just the solution
3. Include context: which workflow, which data, which user role

### Labels

| Label | Meaning |
|---|---|
| `bug` | Something isn't working correctly |
| `enhancement` | New feature or improvement to existing functionality |
| `question` | Clarification needed — not a bug or feature request |
| `mapping` | Related to attribute mapping workflow |
| `validation` | Related to data quality or validation gates |
| `export` | Related to AML/ARAS export |
| `ui` | User interface or usability issue |
| `data-quality` | Data quality scoring or rules |
| `priority: high` | Blocking or critical issue |
| `priority: low` | Nice-to-have or minor |

---

## Current Release Highlights

### v1.2.0 — Relationship Management
- BOM, Vendor, and Manufacturer Part relationship validation
- AI-assisted attribute mapping for relationships (90%+ confidence auto-match)
- Relationship promotion and AML export
- Validation dashboard with clear guidance on fixes

### v1.1.0 — Initial Release
- CSV, Excel, and ARAS AML file loading
- Staging area with duplicate detection and AI analysis
- Attribute mapping with master schema alignment
- Classification structures and multi-lens views
- Promotion workflow with completeness thresholds
- Role-based access and full audit trail

---

## Contact

- **Support**: File an issue in this repository
- **Company**: [Noetic Data, LLC](https://noeticdata.com)

---

*© 2026 Noetic Data, LLC. All rights reserved.*
