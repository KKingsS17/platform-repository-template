# Engineering Standards

## Purpose

This platform exists to standardize automation, documentation, development workflows, repository governance, and operational practices across all future projects to ensure consistency, maintainability, scalability, and engineering quality.

---

## Engineering Principles

- Everything should be version controlled
- Everything should be documented
- Automation over repetitive manual work
- Reusable over duplicated
- Security by default
- Simplicity before complexity
- Standardization over improvisation
- Build for maintainability first

These principles guide all engineering and operational decisions.

---

## Repository Standards

Every repository must include:

- A clear repository description including purpose, scope, and optionally major technologies used
- README
- LICENSE
- .gitignore
- CHANGELOG
- docs/ directory
- standardized directory structure
- GitHub Issue and Pull Request templates
- baseline CI validation workflow

Repositories should remain clean, modular, and easy to navigate.

---

## Naming Standards

Naming should clearly communicate purpose, scope, and functionality.

### Repositories

Use descriptive names that clearly define the repository purpose.

Examples:

- platform-engineering-foundation
- identity-lifecycle-automation
- m365-governance-platform

---

### Branches

Use descriptive names based on the purpose of the branch.

Examples:

- feature/add-user-provisioning
- bugfix/fix-module-import
- docs/update-readme

---

### Scripts

Use descriptive names based on functionality and avoid generic names such as script1.ps1 or test.py.

Examples:

- invoke-user-audit.ps1
- new-github-repository.py

---

### Variables

Use clear and descriptive names while avoiding unnecessary abbreviations.

Examples:

- $TenantId
- $GitHubRepositoryName
- $LogFilePath

---

## Git Workflow

- No direct commits to main
- Planned work should begin with an Issue whenever possible
- Work should happen in dedicated branches
- Pull requests are required before merge
- Pull requests should reference related Issues
- CI validation checks must pass before merge
- Branch protection should be enabled for main
- Squash merges are preferred
- Commit messages should remain clear and descriptive
- Semantic versioning should be used for releases

---

## Repository Governance

Repositories should implement:

- Standardized labels
- Issue templates
- Pull request templates
- Branch protection rules
- CI validation workflows
- Consistent repository structure

Repository governance should remain lightweight, maintainable, and operationally useful.
