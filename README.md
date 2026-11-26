# Foundation

**A reusable AI Engineering System for building software with AI agents.**

Foundation is a structured, agent-driven engineering environment designed to help developers build, test, review, and maintain software projects through coordinated AI agents.

Instead of treating AI as a collection of isolated coding assistants, Foundation organizes agents around established software engineering practices, reusable skills, development workflows, and quality standards.

The goal is simple: **describe what you want to build, and let a coordinated AI engineering team help take it from idea to verified software.**

---

## Vision

Software development involves much more than writing code. It requires understanding requirements, making architectural decisions, designing databases, implementing features, integrating components, testing functionality, reviewing code, and maintaining documentation.

Foundation aims to bring these activities into a unified engineering system.

It provides a reusable environment in which specialized AI agents can collaborate under a common set of engineering principles, follow structured workflows, and produce consistent, verifiable results.

The long-term objective is to move from manually prompting individual AI assistants to coordinating an AI engineering team through a structured development lifecycle.

---

## Core Principles

Foundation is built around the following principles:

- **Structured Engineering:** Follow established software engineering practices instead of generating code without a plan.
- **Specialization:** Assign responsibilities to agents based on their engineering expertise.
- **Coordination:** Enable agents to collaborate through defined responsibilities, task dependencies, and shared project context.
- **Reusability:** Create rules, skills, workflows, and templates that can be reused across different projects.
- **Quality First:** Treat testing, verification, security, and code review as essential parts of development.
- **Controlled Autonomy:** Allow agents to work independently within defined boundaries, with human involvement for important decisions and approvals.
- **Continuous Improvement:** Learn from implementation failures, verification results, and review feedback.

---

## Architecture

Foundation is organized into reusable engineering components.

| Component             | Responsibility                                                                                               |
| --------------------- | ------------------------------------------------------------------------------------------------------------ |
| Engineering Rules     | Define coding standards, architecture principles, security requirements, and development conventions.        |
| Agent Skills          | Provide reusable instructions and procedures for specific engineering activities.                            |
| Specialist Agents     | Handle frontend, backend, database, QA, security, and code review responsibilities.                          |
| Development Workflows | Define structured processes for starting projects, developing features, fixing bugs, and verifying releases. |
| Project Templates     | Standardize project specifications, architecture documents, implementation plans, and reports.               |
| Quality Gates         | Establish requirements for testing, validation, security, and review before work is considered complete.     |
| Automation Scripts    | Support repository validation, Git inspection, and other repeatable engineering tasks.                       |
| Project Documentation | Maintain requirements, technical decisions, progress, verification results, and development history.         |

### Specialist Agents

Foundation is designed around specialized engineering responsibilities.

- **Engineering Orchestrator:** Understands requirements, creates plans, coordinates agents, and manages integration.
- **Frontend Engineer:** Handles frontend architecture, interfaces, components, and client-side functionality.
- **Backend Engineer:** Handles APIs, business logic, services, and backend implementation.
- **Database Engineer:** Designs database schemas, relationships, migrations, and data access.
- **QA Engineer:** Develops test strategies, executes tests, and verifies functionality.
- **Code Reviewer:** Reviews implementation quality, maintainability, and adherence to standards.
- **Security Engineer:** Evaluates application security, vulnerabilities, and security practices.

Agents operate within shared engineering rules and project context.

---

## Engineering Lifecycle

Foundation follows a consistent development lifecycle:

\<pre> Understand     ↓ Plan     ↓ Implement     ↓ Integrate     ↓ Verify     ↓ Review     ↓ Report \</pre>

### 1. Understand

- Analyze the project idea and requirements.
- Identify functional and non-functional requirements.
- Detect missing information and ambiguities.
- Ask for clarification when necessary.

### 2. Plan

- Recommend an appropriate technology stack.
- Design the system architecture.
- Define database schemas and API contracts.
- Break the project into manageable tasks.
- Identify dependencies and parallel implementation opportunities.

### 3. Implement

- Assign tasks to specialist agents.
- Develop frontend and backend components.
- Implement database models and integrations.
- Follow established engineering standards.

### 4. Integrate

- Combine independently developed components.
- Resolve interface and contract mismatches.
- Verify compatibility between system components.

### 5. Verify

- Run relevant builds and tests.
- Validate functionality and integration.
- Identify failures and implementation defects.
- Coordinate fixes and repeat verification where necessary.

### 6. Review

- Examine code quality and maintainability.
- Check security and engineering standards.
- Identify unresolved issues and technical debt.

### 7. Report

- Summarize completed work.
- Record test and verification results.
- Document technical decisions.
- Identify remaining tasks and recommended next steps.

---

## Development Roadmap

Foundation is being developed incrementally, with each stage expanding the system's capabilities.

### Stage 1 — Foundation

Establish the reusable engineering environment.

- Repository structure and organization.
- Engineering rules and standards.
- Reusable agent skills.
- Initial project templates.
- Documentation and validation scripts.

### Stage 2 — Agent Organization

Introduce specialized agents and structured collaboration.

- Define specialist agent responsibilities.
- Establish orchestration principles.
- Enable controlled task delegation.
- Experiment with independent and parallel agent execution.
- Establish shared project context.

### Stage 3 — Automation

Reduce manual coordination and repetitive engineering work.

- Integrate reusable automation procedures.
- Improve task assignment and dependency management.
- Introduce automated testing and validation.
- Establish quality gates.
- Improve result collection and reporting.

### Stage 4 — Autonomous Engineering

Move towards an end-to-end AI engineering lifecycle.

- Natural-language project initiation.
- Automated requirement analysis and architecture planning.
- Coordinated implementation across specialist agents.
- Automated integration and verification.
- Bounded failure recovery and iterative improvement.
- Persistent project tracking and development history.
- Unified project lifecycle commands.

---

## Current Implementation Status

Foundation is an evolving prototype. Its capabilities are being validated incrementally.

| Area                                      | Current status          |
| ----------------------------------------- | ----------------------- |
| Repository structure                      | Established             |
| Engineering rules                         | Implemented             |
| Reusable agent skills                     | Implemented             |
| Specialist agent definitions              | Implemented             |
| Development workflows                     | Documented              |
| Project templates                         | Implemented             |
| Repository validation scripts             | Implemented             |
| Agent discovery and delegation            | Experimentally verified |
| Parallel specialist execution             | Experimentally verified |
| Permanent orchestration engine            | Under development       |
| Automated project discovery and planning  | Under development       |
| Autonomous implementation and integration | Planned                 |
| Iterative testing and self-correction     | Planned                 |
| Unified command-line interface            | Planned                 |

*Implementation status reflects the current prototype, not the final intended system.*

---

## Design Philosophy

Foundation is not intended to replace software engineering principles with AI-generated code.

Instead, it aims to make AI agents operate within a disciplined engineering environment.

Every agent should have:

- A clearly defined responsibility.
- Access to relevant project context.
- Consistent engineering standards.
- Explicit task boundaries.
- Verifiable completion criteria.

Every project should maintain persistent documentation so that decisions, progress, and implementation details remain available throughout development.

Human developers remain responsible for important architectural decisions, approvals, and final acceptance.

---

## Technology and Environment

Foundation is designed to work with an AI-assisted development environment.

The current prototype uses:

- **Agent Environment:** Antigravity
- **Agent Definitions:** Markdown-based specialist configurations
- **Reusable Instructions:** Agent Skills
- **Engineering Standards:** Markdown-based rules
- **Automation:** Python scripts
- **Version Control:** Git

The architecture is intended to remain reusable and adaptable rather than being tied permanently to a particular programming language or application framework.

---

## Repository Structure

```text
foundation/
│
├── .agents/
│   ├── agents/          # Specialist agent definitions
│   ├── skills/          # Reusable engineering skills
│   └── rules/           # Engineering standards
│
├── docs/
│   ├── architecture/    # Architecture documentation
│   ├── guides/          # Usage and development guides
│   ├── standards/       # Engineering standards
│   └── Project_Notes.md # Persistent project context
│
├── scripts/             # Validation and utility scripts
│
├── templates/           # Reusable project templates
│
├── workflows/           # Engineering workflow documentation
│
├── AGENTS.md            # Root agent instructions
├── README.md
└── LICENSE
```

---

## Git and Development Practices

Foundation follows controlled version management practices.

- Use meaningful, conventional commit messages.
- Commit verified changes locally.
- Keep unrelated modifications separate.
- Never commit credentials, secrets, or sensitive configuration.
- Do not automatically push changes to remote repositories.
- Require explicit authorization before remote operations.

Each project should maintain a development record containing requirements, architecture decisions, completed tasks, pending work, verification results, and development history.

---

## Guiding Principle

**Understand → Plan → Implement → Integrate → Verify → Review → Report**

Foundation aims to turn this principle into a repeatable, coordinated, and increasingly autonomous engineering process.

---

## Long-Term Goal

The ultimate goal is to make software development as simple as describing an idea and initiating a structured engineering process.

A future Foundation workflow could look like:

```bash
foundation new
foundation build
foundation status
foundation test
foundation resume
foundation release
```

Behind these commands, specialized AI agents would collaborate to understand requirements, design the system, implement features, integrate components, verify results, and maintain project documentation.

**One engineering environment. Multiple specialized agents. One coordinated development lifecycle.**

---

*Foundation — Building a structured environment for autonomous AI engineering.*
