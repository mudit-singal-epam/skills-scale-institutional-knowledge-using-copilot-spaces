# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies (facilitated by Scrum Master or PM)
- Weekly delivery sync — show progress, updates, and flagged risks (PM, Product Manager, Tech Lead)
- Design reviews — validate UX/UI alignment and implementation (UX/UI Designer, Developers)
- Backlog refinement — clarify upcoming work (Product Manager, Business Analyst, Scrum Master, team)
- Demo/Review at the end of each sprint or milestone (full team)

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic (Developers)
- Integration tests where applicable (Developers, QA Lead)
- End-to-end smoke tests for critical flows before release (QA Lead)
- Usability and accessibility testing (UX/UI Designer, QA Lead)
- Security scanning in CI (DevOps Engineer)
- Manual QA for feature acceptance when needed (QA Lead)
- Performance testing for critical paths (DevOps Engineer, QA Lead)

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master helps identify and remove blockers)
- Level 2: PM escalates to Product Lead and dependent teams (Business Analyst may help clarify requirements blockers)
- Level 3: Sponsor-level escalation for business-impacting issues
- Technical blockers: DevOps Engineer for infrastructure/deployment issues, UX/UI Designer for design decisions

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
