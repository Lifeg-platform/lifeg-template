tes

## Metadata

| Field | Value |
| :---------------- | :----------------------- |
| **Document ID** | README |
| **Document Type** | Repository Guide |
| **Status** | Stable |
| **Version** | 1.0.0 |
| **Author** | Lifeg Project |
| **Created** | YYYY-MM-DD |
| **Last Updated** | YYYY-MM-DD |
| **Applies To** | All Lifeg repositories |
| **Repository** | lifeg-template |

---

# Table of Contents

- [1. Scope](#1-scope)
- [2. Purpose](#2-purpose)
- [3. Philosophy](#3-philosophy)
- [4. Documentation Hierarchy](#4-documentation-hierarchy)
- [5. Available Templates](#5-available-templates)
- [6. Document Lifecycle](#6-document-lifecycle)
- [7. Recommended Workflow](#7-recommended-workflow)
- [8. Choosing the Correct Template](#8-choosing-the-correct-template)
- [9. Repository Standards](#9-repository-standards)
- [10. References](#10-references)

---

# 1. Scope

This document defines the purpose, usage and engineering workflow of all document templates provided by the Lifeg Template Repository.

It applies to every repository adopting the Lifeg documentation methodology.

---

# 2. Purpose

This directory contains the official document templates used throughout the Lifeg ecosystem.

The objective of these templates is to ensure that every repository follows a consistent documentation structure, architectural process and engineering workflow.

All project documentation SHOULD be created from these templates.

---

# 3. Philosophy

The Lifeg project follows the principle:

> **Documentation First**

Architecture is designed before implementation.

Standards are defined before architectural decisions.

Architectural decisions are approved before technical specifications.

Technical specifications are completed before implementation begins.

Documentation is considered part of the system architecture rather than project metadata.

---

# 4. Documentation Hierarchy

The Lifeg documentation system follows a hierarchical model.

Higher-level documents define the rules that govern lower-level documents.

```text
Constitution
 ↓
Standards (STD)
 ↓
Requests for Comments (LRFC)
 ↓
Architecture Decision Records (ADR)
 ↓
Specifications (SPEC)
 ↓
Guides (GUIDE)
 ↓
Implementation
```

If two documents conflict, the document higher in the hierarchy SHALL be considered authoritative.

---

# 5. Available Templates

| Template | Creates | Purpose |
| :------------------ | :------------------- | :-------------------------------------------------- |
| **ADR.template** | ADR-0001-*.md | Records an approved architectural decision. |
| **STD.template** | STD-0001-*.md | Defines project-wide standards and conventions. |
| **LRFC.template** | LRFC-0001-*.md | Describes proposals before architectural approval. |
| **SPEC.template** | SPEC-0001-*.md | Defines technical specifications. |
| **GUIDE.template** | GUIDE-0001-*.md | Provides operational and implementation guidance. |

---

# 6. Document Lifecycle

Typical engineering workflow within the Lifeg ecosystem:

```text
Idea
 ↓
STD (if required)
 ↓
LRFC
 ↓
Architecture Review
 ↓
ADR
 ↓
SPEC
 ↓
GUIDE
 ↓
Implementation
 ↓
Testing
 ↓
Release
```

Not every change requires every document.

Small implementation changes MAY begin with an existing ADR or SPEC.

Major architectural changes SHOULD follow the complete workflow.

---

# 7. Recommended Workflow

## Step 1 — Define Standards

Create or update an STD document if new project-wide rules are required.

---

## Step 2 — Propose the Change

Create an LRFC document describing the proposed change.

The LRFC serves as the primary discussion document.

---

## Step 3 — Record the Decision

Once consensus has been reached, create an ADR documenting the approved architectural decision.

---

## Step 4 — Write the Specification

Describe the technical implementation in a SPEC document.

---

## Step 5 — Prepare Operational Documentation

Create one or more GUIDE documents describing installation, configuration, operation and maintenance.

---

## Step 6 — Implement

Implementation SHALL follow the approved ADR and corresponding SPEC documents.

Implementation MUST NOT redefine architectural decisions already recorded in ADR documents.

---

# 8. Choosing the Correct Template

| If you need to... | Use... |
| :---------------------------------------- | :------------------- |
| Define a mandatory project standard | **STD** |
| Propose an architectural change | **LRFC** |
| Record an approved architectural decision | **ADR** |
| Describe technical implementation details | **SPEC** |
| Explain operation or maintenance | **GUIDE** |

---

# 9. Repository Standards

All documents SHOULD:

- follow the approved template;
- include complete metadata;
- include a table of contents;
- maintain stable section numbering;
- use consistent Markdown formatting;
- use RFC 2119 terminology where applicable;
- include references where appropriate;
- preserve backward compatibility whenever practical.

Templates SHOULD NOT be modified within individual repositories unless justified by an approved architectural decision.

---

# 10. References

- Constitution
- Repository README
- CONTRIBUTING
- Documentation Standards
- Repository Standards
- Markdown Standards
- Naming Standards
- Versioning Standards
