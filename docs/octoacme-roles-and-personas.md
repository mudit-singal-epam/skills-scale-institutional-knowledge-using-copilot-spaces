# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile rituals, remove blockers, and coach the team in agile practices. They ensure the team follows the agreed-upon agile framework and foster a culture of continuous improvement.

### Responsibilities
- Facilitate sprint ceremonies (planning, daily standups, reviews, retrospectives)
- Remove impediments and blockers that prevent team progress
- Coach the team on agile principles and self-organization
- Protect the team from external distractions and scope creep
- Track and communicate team velocity and sprint metrics
- Foster collaboration and psychological safety within the team

### Goals
- Maximize team productivity and flow
- Continuously improve team processes and practices
- Ensure sustainable pace and prevent burnout
- Build team autonomy and self-organization capabilities

### Typical Communication
- Daily facilitation of standups
- Sprint planning and retrospective facilitation
- Regular 1:1s with team members to identify blockers
- Collaboration with Product Manager on backlog refinement

### Interactions with Other Roles
- **vs Project Manager**: While Project Managers focus on cross-project coordination, timelines, and stakeholder management, Scrum Masters focus on team-level process, agile practices, and removing daily impediments. In some organizations, one person may fill both roles, but they serve distinct functions. Scrum Masters work closely with PMs to align sprint goals with project milestones.
- **with Product Manager**: Partners to ensure backlog is refined, prioritized, and ready for sprint planning. Helps Product Manager understand team capacity and velocity.
- **with Developers**: Serves the development team by removing blockers, facilitating ceremonies, and coaching on agile practices. Acts as a servant leader rather than a traditional manager.

---

## UX/UI Designer

### Role Summary
UX/UI Designers define user experience and visual design standards. They ensure products are usable, accessible, and aligned with user needs through research, prototyping, and design iteration.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define and maintain design systems and style guides
- Ensure accessibility (WCAG) and inclusive design standards
- Collaborate with developers to ensure design implementation fidelity
- Validate designs through user feedback and analytics

### Goals
- Maximize user satisfaction and task completion rates
- Ensure consistent, accessible user experiences
- Reduce time-to-value for end users
- Balance user needs with technical constraints and business goals

### Typical Communication
- Design reviews and critique sessions
- Usability test findings and recommendations
- Design specs and handoff documentation for developers
- Alignment sessions with Product Manager on user needs

### Interactions with Other Roles
- **with Product Manager**: Collaborates closely to understand user problems, validate solutions through research, and ensure designs align with product vision and success metrics.
- **with Developers**: Provides design specifications, assets, and guidance during implementation. Reviews implemented features to ensure design fidelity and addresses technical constraints collaboratively.
- **with QA Lead/Test Engineer**: Partners to define acceptance criteria from a UX perspective and validate that implemented features meet usability and accessibility standards.
- **with Business Analyst**: Works together to understand user workflows and requirements, ensuring designs address real user needs and business processes.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They gather, refine, and manage requirements, ensuring that solutions address actual business needs and deliver measurable value.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Translate business needs into detailed user stories and acceptance criteria
- Analyze current processes and identify improvement opportunities
- Facilitate requirements workshops and stakeholder interviews
- Maintain requirements traceability and change management
- Validate that delivered solutions meet business requirements

### Goals
- Ensure clear, complete, and testable requirements
- Minimize rework due to misunderstood or missing requirements
- Maximize alignment between business objectives and technical solutions
- Facilitate informed decision-making through data and analysis

### Typical Communication
- Requirements documentation and user story elaboration
- Stakeholder interviews and requirements workshops
- Process flow diagrams and business rule specifications
- Regular alignment with Product Manager and development team

### Interactions with Other Roles
- **with Product Manager**: Supports product vision by translating high-level product requirements into detailed functional specifications. Helps Product Manager understand business constraints and opportunities.
- **with Developers**: Elaborates user stories, clarifies acceptance criteria, and answers questions during implementation. Acts as a liaison to business stakeholders for technical questions.
- **with QA Lead/Test Engineer**: Provides detailed requirements and business rules to inform test planning. Collaborates on defining test scenarios that validate business logic.
- **with UX/UI Designer**: Partners to ensure designs address business workflows and requirements. Provides context on business processes and user roles.
- **with Stakeholders**: Primary point of contact for gathering requirements, managing expectations, and demonstrating solutions.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design and maintain CI/CD pipelines, infrastructure, and automation tools. They enable reliable, efficient software delivery by bridging development and operations concerns.

### Responsibilities
- Design and maintain CI/CD pipelines for automated builds, tests, and deployments
- Manage cloud infrastructure and container orchestration (e.g., Kubernetes, Docker)
- Implement infrastructure as code (IaC) and configuration management
- Monitor system health, performance, and security
- Automate operational tasks and improve deployment reliability
- Respond to production incidents and lead post-incident reviews

### Goals
- Reduce deployment friction and cycle time from code to production
- Maximize system reliability, availability, and performance
- Automate repetitive operational tasks
- Improve observability and incident response times

### Typical Communication
- Infrastructure design docs and runbooks
- Incident reports and post-mortems
- Pipeline and deployment status updates
- Collaboration with developers on deployment strategies

### Interactions with Other Roles
- **with Developers**: Partners to optimize build and deployment processes, provides guidance on containerization, observability, and production best practices. Enables developers to deploy safely and independently.
- **with QA Lead/Test Engineer**: Collaborates to integrate automated testing into CI/CD pipelines, provides test environments, and ensures quality gates are enforced before production deployment.
- **with Project Manager**: Reports on infrastructure readiness, deployment timelines, and technical risks related to operations and reliability.
- **with Security**: Works closely to implement security scanning, secrets management, and compliance controls in the deployment pipeline.

---

## QA Lead/Test Engineer

### Role Summary
QA Leads oversee quality strategy and testing execution for products. They ensure that features meet requirements, are reliable, and provide a positive user experience through comprehensive test planning and execution.

### Responsibilities
- Define and execute comprehensive test strategies (functional, integration, regression, performance)
- Create and maintain test plans, test cases, and test data
- Perform manual and automated testing as appropriate
- Identify, document, and track defects through resolution
- Collaborate with developers on testability and quality metrics
- Advocate for quality throughout the development lifecycle

### Goals
- Maximize product quality and minimize defects in production
- Ensure features meet acceptance criteria and user expectations
- Reduce time-to-market through efficient testing processes
- Build a culture of quality across the team

### Typical Communication
- Test plans and test case documentation
- Bug reports and quality metrics dashboards
- Test summary reports for releases
- Collaboration with all roles on acceptance criteria and definition of done

### Interactions with Other Roles
- **with Developers**: Partners to define testability requirements, reviews code for quality concerns, and collaborates on automated testing strategies. Provides rapid feedback on code changes.
- **with Product Manager**: Validates that features meet product requirements and acceptance criteria. Provides quality insights to inform release decisions.
- **with Business Analyst**: Uses detailed requirements to create comprehensive test scenarios. Validates that business rules and workflows are correctly implemented.
- **with DevOps Engineer**: Collaborates to integrate automated tests into CI/CD pipelines and ensures test environments are properly configured.
- **with UX/UI Designer**: Tests for usability and accessibility issues, ensuring implemented designs meet user experience standards.
- **with Project Manager**: Reports on testing progress, quality metrics, and risks that may impact release timelines.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

