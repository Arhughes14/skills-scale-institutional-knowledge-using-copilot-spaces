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

## Scrum Master / Agile Coach

### Role Summary
The Scrum Master / Agile Coach facilitates agile ceremonies, removes impediments, and coaches the team on agile best practices. They foster psychological safety and a culture of continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, sprint reviews, and retrospectives
- Identify and remove blockers that impede team progress
- Coach team members and stakeholders on agile principles and practices
- Track and communicate team velocity and delivery health metrics
- Shield the team from unplanned interruptions during sprints

### Goals
- Enable the team to self-organize and deliver predictably
- Continuously improve team processes and collaboration
- Reduce cycle time and eliminate waste in delivery workflows

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective action items and follow-ups
- One-on-one coaching sessions with team members
- Agile metrics reports to Project Manager and leadership

### Interactions with Existing Roles
- **Developers**: Shields from scope creep, facilitates blockers removal, supports estimation and planning
- **Product Managers**: Partners on backlog refinement cadence and sprint goal clarity
- **Project Managers**: Aligns on delivery status, risk escalation, and cross-team dependencies

---

## UX/UI Designer

### Role Summary
The UX/UI Designer creates user-centered interface designs and ensures solutions meet usability and accessibility standards. They bridge the gap between user needs and technical implementation.

### Responsibilities
- Conduct user research, usability testing, and heuristic evaluations
- Create wireframes, prototypes, and high-fidelity mockups
- Define and maintain the design system and style guidelines
- Partner with Product Manager to translate requirements into user journeys
- Review implemented interfaces to verify design fidelity and accessibility

### Goals
- Deliver intuitive, accessible, and visually consistent user experiences
- Reduce rework by resolving UX questions before development begins
- Validate design decisions with real users and data

### Typical Communication
- Design review sessions with Developers and Product Manager
- Figma or design tool links shared in pull requests and issues
- Usability test findings summarized in project documentation

### Interactions with Existing Roles
- **Developers**: Shares design specs and prototypes; reviews implementations during QA and demos
- **Product Managers**: Collaborates on user journeys, acceptance criteria, and success metrics
- **Project Managers**: Flags design dependencies and timeline risks during planning

---

## Data Analyst

### Role Summary
The Data Analyst provides data-driven insights to support decision-making. They define success metrics, build dashboards, and surface trends that inform product direction and delivery quality.

### Responsibilities
- Define, instrument, and monitor success metrics aligned to project goals
- Build and maintain dashboards and reports for team and stakeholder use
- Conduct exploratory analysis to identify trends, anomalies, and opportunities
- Support Developers in implementing data pipelines and telemetry
- Present findings and recommendations in a clear, actionable format

### Goals
- Ensure all features and initiatives are measurable and measured
- Enable data-informed prioritization and retrospectives
- Reduce time-to-insight for stakeholders and product decisions

### Typical Communication
- Dashboard links and metric summaries in weekly syncs
- Analysis write-ups attached to relevant issues or project docs
- Ad-hoc data requests fulfilled with documented methodology

### Interactions with Existing Roles
- **Developers**: Collaborates on instrumentation, data pipeline design, and schema decisions
- **Product Managers**: Provides impact measurement and supports hypothesis validation
- **Project Managers**: Contributes delivery metrics (velocity, defect rates) to status reports

---

## Release Manager

### Role Summary
The Release Manager oversees deployment planning and coordination, ensuring releases are safe, well-communicated, and include rollback plans. They are the primary coordinator between development, operations, and stakeholders during release cycles.

### Responsibilities
- Maintain the release calendar and coordinate deployment windows
- Verify pre-release readiness (CI passing, release notes drafted, smoke tests ready)
- Coordinate go/no-go decisions with engineering and product leads
- Ensure rollback and mitigation plans are documented and rehearsed
- Communicate release status and post-deploy results to stakeholders

### Goals
- Minimize release risk and mean time to recover (MTTR) from incidents
- Ensure consistent, repeatable release processes across teams
- Keep all stakeholders informed throughout the release lifecycle

### Typical Communication
- Release readiness meetings and go/no-go checkpoints
- Release notes and deployment announcements
- Incident notifications and post-deploy verification summaries

### Interactions with Existing Roles
- **Developers**: Reviews release readiness, coordinates merges and deployment artifacts
- **Product Managers**: Aligns on release scope, feature flags, and customer communications
- **Project Managers**: Reports release milestones and escalates blocking issues

---

## Customer Support Lead

### Role Summary
The Customer Support Lead represents the voice of the customer within the delivery team. They triage post-launch issues, communicate user feedback, and ensure the team ships support-ready releases.

### Responsibilities
- Triage and prioritize post-launch support tickets and escalations
- Communicate user-reported issues and feedback to the product and engineering team
- Contribute to release readiness by reviewing support documentation and FAQs
- Partner with Product Manager on bug severity and backlog prioritization
- Coordinate with Release Manager to communicate planned changes to support staff

### Goals
- Minimize time-to-resolution for customer-reported issues
- Improve support readiness so fewer releases result in support escalations
- Ensure user feedback informs the product roadmap

### Typical Communication
- Weekly support status updates shared with Project Manager and Product Manager
- Escalation alerts for high-severity customer issues
- Pre-release briefings with support staff ahead of major deployments

### Interactions with Existing Roles
- **Developers**: Reports bugs with reproduction steps and severity context; validates fixes
- **Product Managers**: Surfaces recurring user pain points and feedback trends for prioritization
- **Project Managers**: Flags support-impacting risks during planning and execution phases

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [octoacme-role-interaction-matrix.md](./octoacme-role-interaction-matrix.md) for a RACI-style overview of how these roles collaborate.
- See [octoacme-role-handoff-checklist.md](./octoacme-role-handoff-checklist.md) for release and support readiness handoff steps.

