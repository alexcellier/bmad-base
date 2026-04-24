# BMAD-Base

BMAD-Base is a repository implementing the BMAD (Build, Measure, Analyze, Deploy) method for organizing skills, agents, and workflows in a GitHub-centric framework. BMAD can also stand for Build More Architect Dreams.

This repository was initially populated using `npx bmad-method install` from the [BMAD METHOD](https://github.com/bmad-code-org/BMAD-METHOD) framework.

## Structure

- `_bmad/` : Core BMAD configuration and modules
  - `_config/` : Manifests and configuration files (agent-manifest.csv, skill-manifest.csv, etc.)
  - `bmb/` : Build Module Builder
  - `bmm/` : Build Measure Module (with analysis, planning, solutioning, implementation phases)
  - `cis/` : Creative Innovation Strategies (skills, agents, data)
  - `core/` : Core functionality
  - `tea/` : Test Architect and Quality Advisor (agents, workflows)
  - `wds/` : Workflow Design System (agents, skills, data, workflows)
- `_bmad-output/` : Generated artifacts from BMAD processes (implementation, planning, test artifacts)
- `design-artifacts/` : Design-related outputs (Product Brief, Trigger Map, UX Scenarios, Design System, Development)
- `docs/` : Documentation and BMAD method notes

## Getting Started

1. Review the BMAD method in `docs/` and `_bmad/wds/data/agent-guides/`.
2. Explore modules in `_bmad/` for skills, agents, and workflows.
3. Use the framework to build, measure, analyze, and deploy automation components.

## Contributing

- Follow BMAD principles for contributions.
- Keep naming consistent across modules.
- Document new skills, agents, and workflows clearly.
- Use GitHub workflows to validate structure and automation behavior.
