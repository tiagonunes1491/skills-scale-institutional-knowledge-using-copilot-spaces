# OctoAcme Project Management Docs

## Overview

OctoAcme's project management approach is built on customer-first principles, iterative delivery, and clear ownership. Every cross-functional project follows a structured lifecycle that prioritizes delivering testable increments while maintaining psychological safety and data-informed decision-making. The process ensures teams can move quickly from idea to production while managing risks, maintaining quality, and fostering continuous improvement. This documentation serves as the authoritative guide for how OctoAcme runs projects, providing both new teammates and experienced staff with a single source of truth for our workflows, roles, and best practices.

The project lifecycle consists of five key phases: Initiation, Planning, Execution, Release, and Retrospective. During **Initiation**, teams validate the business need through a Project One-pager that defines the problem, success metrics, stakeholders, and initial timeline. This phase includes a decision gate to approve moving into planning. **Planning** transforms approved initiatives into actionable backlogs with prioritized work items, acceptance criteria, and a Definition of Done. Teams identify dependencies, estimate scope, and create release plans during kickoff meetings. **Execution** follows a daily rhythm of standups, weekly syncs, and milestone demos, with work tracked through project boards and pull request workflows that emphasize small, reviewable changes with automated testing and quality gates. **Release & Deployment** standardizes how features reach production through documented checklists, smoke tests, and rollback plans for patches, minor releases, and major updates. Finally, **Retrospective** sessions capture learnings after each sprint or milestone, converting insights into prioritized action items that drive continuous improvement.

Key roles include Project Managers who coordinate delivery, schedules, risks, and communications; Product Managers who define outcomes, prioritize the backlog, and measure success; Developers who implement features and collaborate on design; and QA/Testing who validate quality and acceptance criteria. Communication happens through multiple channels: weekly syncs between PM and Product Manager, twice-weekly standups for delivery teams, monthly stakeholder updates, and ad-hoc escalations as needed. Teams use weekly status templates to share progress, next steps, risks, and decisions needed. Risk management follows a structured approach with a Risk Register tracking impact, likelihood, owners, and mitigation plans, with risks reviewed during weekly syncs and escalated through defined paths from team-level to PM to Product Lead to Sponsor.

Quality assurance and continuous improvement are embedded throughout the process. Teams write unit tests for new logic, integration tests where applicable, and end-to-end smoke tests for critical flows before release. CI pipelines run automated tests, linting, and security scanning before code can be merged. Pull requests remain small (≤400 lines when possible) and require at least one approval. Metrics include velocity tracking, burndown charts, and dashboards monitoring the success metrics defined in the Project One-pager. After each sprint, release, or incident, retrospectives provide a structured forum to discuss what went well, what could be improved, and action items with clear owners and due dates. This blameless, improvement-focused culture ensures teams learn from both successes and challenges, making incremental changes that compound over time.

## Process Documentation

### Core Framework
- [Project Management Overview](octoacme-project-management-overview.md) - High-level introduction to OctoAcme's approach, principles, roles, and lifecycle

### Project Lifecycle Phases
- [Project Initiation](octoacme-project-initiation.md) - How to validate ideas, create one-pagers, and get approval to start planning
- [Project Planning](octoacme-project-planning.md) - Breaking work into backlogs, estimating, and creating release plans
- [Execution & Tracking](octoacme-execution-and-tracking.md) - Day-to-day workflows, team rhythm, quality practices, and progress tracking
- [Release & Deployment](octoacme-release-and-deployment.md) - Standardized release process, deployment checklists, and rollback procedures
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) - Capturing learnings and converting them into actionable improvements

### Supporting Practices
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed responsibilities and goals for Developers, Product Managers, and Project Managers
- [Risk Management & Communication](octoacme-risks-and-communication.md) - How to identify, track, and communicate risks and dependencies

---

**Related**: See issue #2 for context on this documentation structure.
