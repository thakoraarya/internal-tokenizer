## 🌳 Project Structure (Work in Progress)

This document outlines the project's( **Internal-Tokenizer's** ) file and directory structure, optimized for readability and navigation within a GitHub `README.md` or similar Markdown rendering environments. Emojis and brief descriptions are added for better visual clarity.

---

- 📁 **[BRD/](./BRD)** - Business Requirements Document

  - 📄 [overview.md](./BRD/overview.md) - High-level summary of the project's purpose and goals.
  - 📄 [faq.md](./BRD/faq.md) - Frequently asked questions about the project.
  - 📄 [changelog.md](./BRD/changelog.md) - Tracks major changes and updates to the BRD itself.
  - 📁 **[Features/](./BRD/features/)** - Detailed specifications for individual functionalities:
    - 📄 [points-system.md](./BRD/features/points-system.md)
    - 📄 [nft-badges.md](./BRD/features/nft-badges.md)
    - 📄 [web3-infra.md](./BRD/features/web3-infra.md)
    - 📄 [employee-onboarding.md](./BRD/features/employee-onboarding.md)
  - 📁 **[Roles/](./BRD/roles/)** - Defines the responsibilities and interactions of different user types within the system:
    - 📄 [hr-admin.md](./BRD/roles/hr-admin.md)
    - 📄 [team-leads.md](./BRD/roles/team-leads.md)
    - 📄 [employees.md](./BRD/roles/employees.md)
    - 📄 [reward-validators.md](./BRD/roles/reward-validators.md)
  - 📁 **[Integration/](./BRD/integration/)** - Documents how our system connects with external services:
    - 📄 [directory-sync.md](./BRD/integration/directory-sync.md)
    - 📄 [sheet-import.md](./BRD/integration/sheet-import.md)
  - 📁 **[Governance/](./BRD/governance/)** - Describes the rules and mechanisms for system operation:
    - 📄 [reward-validation.md](./BRD/governance/reward-validation.md)
    - 📄 [smart-contracts.md](./BRD/governance/smart-contracts.md)
  - 📁 **[Onboarding-drills/](./BRD/onboarding-drills/)** - Guides for demonstrating and testing key functionalities:
    - 📄 [demo-drill.md](./BRD/onboarding-drills/demo-drill.md)

- 💻 **[Code/](./code/)** - Application Source Code

  - 📁 **frontend/** - All client-side application code.
  - 📁 **backend/** - Server-side logic and API implementation.
  - 📁 **contracts/** - Smart contracts for blockchain interaction.

- 📚 **[Docs/](./docs/)** - Technical Documentation

  - 📄 [architecture.md](./docs/architecture.md) - Overview of the system's design and components.
  - 📄 [setup.md](./docs/setup.md) - Instructions for setting up the development environment.
  - 📄 [api-specs.md](./docs/api-specs.md) - Detailed specifications for all APIs.

- ⚙️ **scripts/** - Various utility scripts for development, deployment, or automation.
- 🐙 **.github/** - GitHub-specific configurations, such as workflows, issue templates, or pull request templates.
- 📄 [README.md](./README.md) - The main project README, providing a quick overview and entry point.
- 📄 [LICENSE](./LICENSE) - The project's licensing information.
- 📦 [package.json](./package.json) - (If applicable, for Node.js projects) Defines project metadata, dependencies, and scripts.
