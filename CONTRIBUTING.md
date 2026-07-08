# Contributing Guide

**Version:** 0.1.0

**Status:** Active Development

**Owner:** Lifeg Platform

**Last Updated:** YYYY-MM-DD

---

# Purpose

This document defines the contribution process for all repositories within the Lifeg Platform organization.

Its goal is to ensure consistency, quality, maintainability, and architectural integrity across the entire platform.

---

# Core Principles

Every contribution must follow the engineering principles of the Lifeg Platform.

- Documentation First
- Git as the Single Source of Truth
- Modular Architecture
- Secure by Default
- IPv6 First
- Separation of Transport and Overlay

---

# Contribution Workflow

Every change follows the same lifecycle.

1. Identify the problem or improvement.
2. Update or create the required documentation.
3. Discuss the proposed solution if necessary.
4. Implement the change.
5. Test the implementation.
6. Submit a Pull Request.
7. Complete the review process.
8. Merge into the default branch.

---

# Documentation Requirements

Documentation is mandatory.

Before implementing significant changes, contributors should update the relevant documentation.

Examples include:

- README
- Architecture documents
- Standards (STD)
- Architecture Decision Records (ADR)
- Lifeg Requests for Comments (LRFC)

---

# Commit Messages

Use clear and descriptive commit messages.

Recommended format:

```
type(scope): short description
```

Examples:

```
docs(readme): improve quick start section

feat(network): add WireGuard configuration

fix(openbsd): correct PF firewall rule

refactor(template): simplify repository layout
```

---

# Branch Strategy

Use short-lived feature branches.

Recommended naming:

```
feature/<name>

fix/<name>

docs/<name>

refactor/<name>

release/<version>
```

Examples:

```
feature/wireguard

docs/readme-update

fix/dns-records

release/v1.0.0
```

---

# Pull Requests

Every Pull Request should:

- describe the purpose of the change;
- reference related issues when applicable;
- update documentation if required;
- remain focused on a single topic.

Large unrelated changes should be split into multiple Pull Requests.

---

# Code Quality

All contributions should:

- be readable;
- be maintainable;
- avoid unnecessary complexity;
- follow repository conventions;
- include documentation updates when appropriate.

---

# Repository Structure

Contributors should not modify the repository structure without prior architectural approval.

Major structural changes require an Architecture Decision Record (ADR).

---

# Security

Security-related changes should follow the repository's SECURITY.md policy.

Potential vulnerabilities should never be disclosed publicly before they are addressed.

---

# Code of Conduct

All contributors are expected to communicate respectfully and professionally.

Constructive feedback is encouraged.

Personal attacks, harassment, or discriminatory behavior are not acceptable.

---

# Questions

If you are unsure about a proposed change, start a discussion before implementation.

Early communication helps maintain project quality and architectural consistency.

---

Thank you for contributing to the Lifeg Platform.
