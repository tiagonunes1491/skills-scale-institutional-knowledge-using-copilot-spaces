# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — facilitated by Scrum Master, focus on progress, blockers, dependencies
- Weekly delivery sync — Project Manager shows progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone — team demonstrates completed work to stakeholders
- Retrospectives — Scrum Master facilitates team reflection on process improvements

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- QA Engineer creates and maintains test plans
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers, QA Engineer)
- End-to-end smoke tests for critical flows before release (QA Engineer)
- Security scanning in CI
- Manual QA for feature acceptance when needed (QA Engineer)
- UX Designer validates design implementation and usability
- QA Engineer provides release readiness sign-off

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates)
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues
- Design blockers: UX Designer escalates to Product Manager or Design Lead
- Quality/Testing blockers: QA Engineer escalates to Project Manager and Engineering Lead

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
