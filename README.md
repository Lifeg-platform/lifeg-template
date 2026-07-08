# Lifeg Repository Template

The official repository template for the Lifeg Platform.

## Overview

`lifeg-template` provides the standard repository structure used across all projects within the Lifeg Platform organization.

Its purpose is to ensure consistency, maintainability, and predictable project organization by providing a common foundation for documentation, repository layout, and GitHub configuration.

This repository is intended to be used as a **GitHub Template Repository**.

## Goals

This template is designed to:

- provide a consistent repository structure;
- encourage documentation before implementation;
- simplify repository creation;
- standardize project governance;
- improve long-term maintainability.

## Repository Structure

```text
.
├── .github/
├── assets/
├── configs/
├── docs/
├── examples/
├── scripts/
├── templates/
├── tests/
├── CHANGELOG.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── ROADMAP.md
├── SECURITY.md
├── VERSION
└── .gitignore
```

## Design Principles

Every repository created from this template follows the core engineering principles of the Lifeg Platform:

- Documentation First
- Git as the Single Source of Truth
- Modular Architecture
- Secure by Default
- IPv6 First
- Separation of Transport and Overlay

## What This Template Includes

- Standard repository layout
- Documentation skeleton
- GitHub configuration
- Common project files
- Reusable document templates

## What This Template Does Not Include

This template intentionally contains no project-specific implementation.

It does not include:

- application source code;
- infrastructure configuration;
- operating system settings;
- network configuration;
- deployment logic.

Project-specific implementation belongs in the repository that owns that domain.

## Versioning

This repository follows Semantic Versioning.

Template changes are documented in `CHANGELOG.md`.

## Contributing

Before contributing, please read `CONTRIBUTING.md`.

## Security

Security issues should be reported according to the process described in `SECURITY.md`.

## License

See the `LICENSE` file for licensing information.

## Related Repositories

- `lifeg-platform` — Platform portal
- `lifeg-template` — Repository template

Additional repositories will be added as the Lifeg Platform ecosystem evolves.
