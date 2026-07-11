# ADR-XXXX: <Short Title>

| Field              | Value      |
| :----------------- | :--------- |
| **Status**         | Draft      |
| **ADR ID**         | ADR-XXXX   |
| **Author**         |            |
| **Created**        | YYYY-MM-DD |
| **Last Updated**   | YYYY-MM-DD |
| **Supersedes**     | None       |
| **Superseded By**  | None       |
| **Related STD**    |            |
| **Related SPEC**   |            |
| **Related GUIDE**  |            |
| **Related LRFC**   |            |
| **Related Issues** |            |
| **Repository**     |            |
| **Target Version** |            |

> [!NOTE]
> ## Author Guidance
>
> This template contains guidance for authors.
>
> Before publishing the final document:
>
> - remove instructional text;
> - replace placeholders;
> - verify all references;
> - update metadata;
> - validate the Table of Contents;
> - ensure compliance with the Constitution;
> - ensure compliance with applicable ADR, STD, SPEC and GUIDE documents;
> - verify cross-references and internal links.

---

# Table of Contents

- [1. Purpose](#1-purpose)
- [2. Summary](#2-summary)
- [3. Context](#3-context)
- [4. Problem Statement](#4-problem-statement)
- [5. Requirements](#5-requirements)
- [6. Considered Options](#6-considered-options)
- [7. Decision](#7-decision)
- [8. Rationale](#8-rationale)
- [9. Consequences](#9-consequences)
- [10. Implementation Plan](#10-implementation-plan)
- [11. Validation](#11-validation)
- [12. Rollback Plan](#12-rollback-plan)
- [13. References](#13-references)
- [Appendix A. Notes](#appendix-a-notes)

---

# 1. Purpose

Describe the purpose of this Architecture Decision Record.

Explain why this decision is documented and what architectural aspect it governs.

This section should allow the reader to quickly understand the scope of the ADR.

---

# 2. Summary

Provide a concise summary of the architectural decision.

The summary should enable readers to understand the essence of the decision without reading the entire document.

---

# 3. Context

Describe the current situation that led to this decision.

Include, where applicable:

- current architecture;
- background information;
- technical constraints;
- operational constraints;
- security considerations;
- business constraints;
- assumptions;
- dependencies;
- related architectural decisions.

Reference existing documentation whenever possible.

---

# 4. Problem Statement

Describe the architectural problem that requires a decision.

Focus exclusively on the problem.

Do not describe the selected solution in this section.

---

# 5. Requirements

Describe all requirements influencing the decision.

Consider:

- Functional requirements
- Non-functional requirements
- Security
- Reliability
- Availability
- Scalability
- Performance
- Maintainability
- Portability
- Compatibility
- Documentation
- Operational simplicity
- Long-term maintainability

Clearly identify mandatory constraints.
---

# 6. Considered Options

Describe all reasonable architectural alternatives that were evaluated.

Each option should include sufficient detail to understand the trade-offs.

The preferred format is:

## Option A

### Description

Describe the proposed architecture.

### Advantages

- ...
- ...
- ...

### Disadvantages

- ...
- ...
- ...

---

## Option B

### Description

Describe the proposed architecture.

### Advantages

- ...
- ...
- ...

### Disadvantages

- ...
- ...
- ...

---

## Option C

### Description

Describe the proposed architecture.

### Advantages

- ...
- ...
- ...

### Disadvantages

- ...
- ...
- ...

---

Conclude this section with a short comparison explaining why one option is preferred over the others.

---

# 7. Decision

Describe the selected architectural decision.

Clearly specify:

- what has been approved;
- implementation boundaries;
- affected components;
- expected implementation scope;
- effective date, if applicable.

This section represents the official architectural decision.

---

# 8. Rationale

Explain why this option was selected.

Document:

- engineering reasoning;
- architectural trade-offs;
- rejected alternatives;
- long-term impact;
- expected benefits;
- known limitations.

This section should allow future contributors to understand the reasoning behind the decision.

---

# 9. Consequences

Describe the expected consequences of implementing this decision.

## Positive

Document anticipated benefits.

- ...
- ...
- ...

## Negative

Document known disadvantages.

- ...
- ...
- ...

## Risks

Identify technical, operational, organizational or security risks.

For each significant risk, describe potential mitigation where applicable.

---

# 10. Implementation Plan

Describe the recommended implementation sequence.

Example:

1. Update documentation.
2. Create or update relevant standards.
3. Prepare implementation tasks.
4. Implement changes.
5. Execute testing.
6. Perform architecture review.
7. Merge changes.
8. Publish release documentation.

Implementation may be divided into multiple phases if necessary.
---

# 11. Validation

Describe how the implementation of this architectural decision will be validated.

Possible validation methods include:

- Architecture Review
- Documentation Review
- Code Review
- Unit Testing
- Integration Testing
- System Testing
- Performance Testing
- Security Review
- Operational Validation
- User Acceptance Testing

Define measurable acceptance criteria whenever possible.

Example:

- Documentation updated.
- Implementation completed.
- All required tests passed.
- No critical defects identified.
- Architecture Review approved.

---

# 12. Rollback Plan

Describe how this architectural decision can be safely reverted if necessary.

Include:

- rollback conditions;
- rollback procedure;
- affected components;
- expected impact;
- recovery time estimate;
- required documentation updates.

Every significant architectural decision should include a rollback strategy unless rollback is technically impossible.

If rollback is not possible, explain why and describe the mitigation strategy.

---

# 13. References

List all documents related to this ADR.

Typical references include:

## Governance

- Constitution
- Vision
- Whitepaper
- Roadmap

## Architecture

- Related ADRs
- STD documents
- SPEC documents
- GUIDE documents
- LRFC documents

## External Standards

- RFCs
- IETF Drafts
- IEEE Standards
- ISO Standards
- OpenBSD Documentation
- RouterOS Documentation

## Repository

- GitHub Issues
- Pull Requests
- Commits
- Project Discussions

Use relative links whenever possible for repository documents.

---

# Appendix A. Notes

Include supporting material that improves understanding of the decision.

Examples:

- diagrams;
- C4 models;
- PlantUML diagrams;
- Mermaid diagrams;
- benchmarks;
- migration notes;
- compatibility notes;
- implementation examples;
- calculations;
- design alternatives;
- glossary additions.

Appendices are informative and do not form part of the normative architectural decision unless explicitly referenced.

---

# Document History

| Version | Date       | Description   | Author |
| :------ | :--------- | :------------ | :----- |
| 0.1.0   | YYYY-MM-DD | Initial draft |        |

---

# Approval

| Role                | Name | Date | Status  |
| :------------------ | :--- | :--- | :------ |
| Author              |      |      | Draft   |
| Architecture Review |      |      | Pending |
| Technical Review    |      |      | Pending |
| Approved By         |      |      | Pending |

---

# End of Document

