<div align="center">

<img src="https://avatars.githubusercontent.com/u/272495327?s=200&v=4" width="88" alt="Geargames Toolkit" />

<br/>

# GEARGAMES TOOLKIT

**The engineering backbone of Gear Games.**<br/>
*Built by engineers. For engineers. Since 2006.*

<br/>

[![Auto Assign](https://github.com/Geargames-toolkit/demo-repository/actions/workflows/auto-assign.yml/badge.svg)](https://github.com/Geargames-toolkit/demo-repository/actions/workflows/auto-assign.yml)
[![Proof HTML](https://github.com/Geargames-toolkit/demo-repository/actions/workflows/proof-html.yml/badge.svg)](https://github.com/Geargames-toolkit/demo-repository/actions/workflows/proof-html.yml)
![Status](https://img.shields.io/badge/Status-Active-00d9ff?style=flat-square)
![Team](https://img.shields.io/badge/Team-270%2B%20Engineers-7c3aed?style=flat-square)
![Location](https://img.shields.io/badge/Hanoi%2C%20Vietnam-0f1a2e?style=flat-square)
![Founded](https://img.shields.io/badge/Since-2006-a855f7?style=flat-square)

<br/>

**[Landing Page](https://geargames-toolkit.github.io/demo-repository) &nbsp;&middot;&nbsp; [About Gear Games](https://geargames.com) &nbsp;&middot;&nbsp; [All Repositories](https://github.com/orgs/Geargames-toolkit/repositories)**

</div>

---

## Table of Contents

- [About](#about)
- [Tech Stack and Ecosystem](#tech-stack-and-ecosystem)
- [Repositories](#repositories)
- [What We Build Here](#what-we-build-here)
- [Getting Started](#getting-started)
- [Project Structure and Conventions](#project-structure-and-conventions)
- [Contributing](#contributing)
- [Values](#values)
- [Community and Support](#community-and-support)
- [License](#license)

---

## About

We don't just build games. We build the tools that build the games.

At **Gear Games**, 270+ engineers in Hanoi have been shipping world-class titles since 2006 — *WWE Champions*, *Marvel Strike Force*, *Angry Birds Match* and more. Behind every shipped title is an engineering culture that invests in its own craft.

**Geargames Toolkit** is that investment. It is the internal hub where our best ideas live beyond a single team's Slack channel. Scripts born from late-night debugging sessions. Libraries refactored until they're actually reusable. Workflows that eliminate the toil no one should repeat twice. This is where those things become permanent, shared infrastructure.

> *Your work deserves a permanent home. Stop letting good tools disappear into private repos or Slack threads. This organization exists so that what you build can outlast your current project, benefit engineers across the studio, and grow into something larger than you originally imagined.*

---

## Tech Stack and Ecosystem

The core technologies and standards used across Geargames Toolkit repositories:

| Category | Technologies |
|---|---|
| **Languages** | TypeScript, JavaScript, HTML, CSS |
| **Frontend** | React, Vite |
| **Runtime** | Node.js |
| **Testing** | Vitest, Playwright |
| **Linting / Formatting** | ESLint, Prettier |
| **Schema Validation** | Zod |
| **AI Integrations** | MCP (Model Context Protocol) |
| **Animation** | Rive |
| **CI/CD** | GitHub Actions |
| **Hosting** | GitHub Pages |

All repositories target **Node.js 18+** and use **TypeScript** as the primary language unless otherwise noted.

---

## Repositories

| Repository | Description | Stack | Status |
|---|---|---|---|
| [`rive-playground`](https://github.com/Geargames-toolkit/rive-playground) | CLI + MCP server + visual playground for Rive `.riv` animations | TypeScript, React, MCP | ![Active](https://img.shields.io/badge/-Active-00d9ff?style=flat-square) |
| *Your tool here* | Open a discussion — bring your idea | — | — |

> We are actively growing this collection. If you have a tool that solves a real problem for your team, it belongs here.

---

## What We Build Here

```
cli-tools          Terminal utilities for inspection, automation, and codegen
shared-libs        Reusable modules, type definitions, and configuration presets
mcp-servers        AI-assistant integrations that accelerate developer workflows
ci-templates       GitHub Actions pipelines for game builds, testing, and releases
visual-tools       Browser-based playgrounds, dashboards, and inspection tools
standards          Engineering conventions, onboarding guides, and team norms
```

---

## Getting Started

### Prerequisites

- **Node.js** 18 or later
- **npm** 9+ or **pnpm** 8+
- **Git** 2.30+
- A GitHub account with access to the [Geargames-toolkit](https://github.com/Geargames-toolkit) organization

### Quick Start

```sh
# Clone a repository
git clone git@github.com:Geargames-toolkit/<repo-name>.git
cd <repo-name>

# Install dependencies
npm install

# Start development
npm run dev
```

### Finding Your First Contribution

1. Browse [open issues](https://github.com/orgs/Geargames-toolkit/repositories) across repositories
2. Look for issues labeled `good-first-issue` or `help-wanted`
3. Check [GitHub Discussions](https://github.com/orgs/Geargames-toolkit/discussions) for ideas in progress
4. Or simply bring your own tool — see [Contributing](#contributing) below

---

## Project Structure and Conventions

### Repository Naming

| Pattern | Use Case | Example |
|---|---|---|
| `<tool-name>` | Standalone tool or playground | `rive-playground` |
| `<domain>-<type>` | Shared configs or templates | `eslint-config`, `ci-templates` |
| `mcp-<name>` | MCP server integration | `mcp-rive` |

### What Belongs Here

- Tools and utilities used by **two or more teams**
- Shared configurations that enforce **org-wide standards**
- Automation scripts that eliminate **repeated manual work**
- Internal playgrounds and **visual debugging tools**

### What Does Not Belong Here

- Game-specific code tied to a single title
- Proprietary game assets or credentials
- Experimental code with no clear use case beyond one person

### Quality Standards

Every repository in this organization should meet the following bar:

- **README** — Clear description, setup instructions, and usage examples
- **TypeScript** — Strict mode enabled, no `any` types without justification
- **Tests** — At minimum, core functionality covered
- **CI** — GitHub Actions running on every PR
- **License** — MIT unless otherwise approved

---

## Contributing

This is not a request. It is an invitation.

If you are an engineer at Gear Games and you have built something useful, this organization is yours too. There is no committee to impress. There is no long approval chain. There is just the work and the community of engineers who will benefit from it.

### How to Contribute

```
1. Have an idea or a tool worth sharing
2. Open a GitHub Discussion to introduce it
3. Fork the repo or request a new one
4. Submit a pull request — clear description, real use case
5. Get one teammate to review it
6. Merge. Ship. Done.
```

### Pull Request Requirements

- **Title**: Concise summary of the change (e.g., `feat: add Rive export CLI command`)
- **Description**: What changed, why it changed, and how to test it
- **Tests**: Include tests for new functionality; do not break existing tests
- **Review**: At least one approval from a team member
- **CI**: All checks must pass before merging

### Branch Naming

```
feat/<short-description>     New features
fix/<short-description>      Bug fixes
chore/<short-description>    Maintenance and cleanup
docs/<short-description>     Documentation updates
```

Senior or junior — it does not matter. A well-placed utility from a first-year engineer can save a staff engineer hours every week. That contribution is worth exactly as much.

---

## Values

```
SHIP FREELY      A working prototype is worth more than a perfect proposal.
SHARE OPENLY     If it solved your problem, it will solve someone else's.
GROW TOGETHER    Every engineer has something to teach and something to learn.
MOVE FAST        Small tools. Fast iterations. Done is better than theoretical.
BUILD WITH PRIDE Code you ship under this org represents the craft of the whole team.
```

---

## Community and Support

| Action | Where |
|---|---|
| Propose a new toolkit | [GitHub Discussions](https://github.com/orgs/Geargames-toolkit/discussions) |
| Report a bug or request a feature | [Issues](https://github.com/Geargames-toolkit/demo-repository/issues) |
| Contribute code or docs | [Pull Requests](https://github.com/Geargames-toolkit/demo-repository/pulls) |
| Ask a question | [GitHub Discussions](https://github.com/orgs/Geargames-toolkit/discussions) |
| View the landing page | [geargames-toolkit.github.io](https://geargames-toolkit.github.io/demo-repository) |

No message is too small. No tool is too simple. The only wrong move is building something great and keeping it to yourself.

---

## License

This project is licensed under the **MIT License**. See individual repositories for their specific license terms.

```
MIT License

Copyright (c) 2026 Gear Games

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

<div align="center">

**Built by the engineering team at [Gear Games](https://geargames.com)**<br/>
Hanoi, Vietnam &nbsp;&middot;&nbsp; Since 2006 &nbsp;&middot;&nbsp; 270+ engineers and growing

</div>
