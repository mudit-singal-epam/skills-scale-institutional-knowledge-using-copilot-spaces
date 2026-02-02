# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based) - coordinated by PM
- Use a single source of truth (project README or release doc) for status
- Business Analyst helps translate technical progress into business impact for stakeholders
- UX/UI Designer shares design progress and user research findings with relevant stakeholders

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Role-Specific Communication Guidelines

### Scrum Master Communications
- Sprint planning outcomes (goals, capacity, commitments)
- Blocker removal updates (what was blocking, resolution, preventive measures)
- Velocity and team health metrics
- Retrospective action items and follow-ups

### UX/UI Designer Communications
- Design review invitations with context and goals
- User research findings and recommendations
- Design specification handoffs to developers
- Usability test results and proposed iterations

### Business Analyst Communications
- Requirements clarification and user story elaboration
- Process flow documentation and business rule changes
- Stakeholder interview summaries
- Requirements traceability matrix updates

### DevOps Engineer Communications
- Infrastructure change notifications
- Deployment pipeline updates and improvements
- Incident response and post-mortem reports
- Performance and reliability metrics
- Planned maintenance windows

### QA Lead Communications
- Test plan reviews and coverage reports
- Quality metrics and defect trends
- Release readiness assessments
- Testing blockers and resource needs

## Escalation Paths
- Team-level -> Scrum Master (for process/blocker issues) or PM (for project issues) -> Product Lead -> Sponsor
- Technical issues: Developers -> Tech Lead -> DevOps Engineer (for infrastructure) or relevant specialist
- Requirements clarity: Developers -> Business Analyst -> Product Manager
- Design decisions: Developers -> UX/UI Designer -> Product Manager
- Quality concerns: QA Lead -> PM -> Product Lead
- For security incidents, follow the security incident runbook and notify Security on-call
