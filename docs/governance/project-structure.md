# Enterprise Tableau Project Structure

## Purpose

A well-designed project structure helps organizations organize content, simplify permission management, and improve governance across Tableau Cloud.

---

## Recommended Hierarchy


Company
│
├── Executive Reporting
├── Finance
├── Sales
├── Supply Chain
├── Human Resources
├── IT
├── Sandbox
└── Archive


## Design Principles

- Organize projects by business function.
- Use sub-projects to separate development and production content.
- Assign permissions at the project level whenever possible.
- Avoid deeply nested project structures.


## Environment Structure

Each department should contain:

- Development
- Testing
- Production
- Archive

Example:

Finance
│
├── Development
├── Testing
├── Production
└── Archive

## Best Practices

- Keep project names consistent.
- Use groups for permissions.
- Archive inactive content.
- Publish only approved dashboards to Production.
