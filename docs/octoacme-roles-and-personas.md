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

## QA / Testing Lead

### Role Summary
QA / Testing Leads define the quality strategy for the project and ensure that business and technical requirements are validated before release. They work with Product Managers, Developers, and Project Managers to keep quality visible and measurable.

### Responsibilities
- Define test strategy and quality gates for each milestone or release
- Review acceptance criteria for clarity and testability
- Lead manual and automated testing efforts
- Track defects, regressions, and release blockers
- Validate that work meets the Definition of Done before sign-off
- Coordinate with DevOps and Developers on test environments and release readiness

### Goals
- Improve product quality and customer trust
- Reduce escaped defects and production incidents
- Provide confidence for release decisions

### Typical Communication
- Quality checkpoints in sprint reviews and weekly delivery syncs
- Test reports and defect triage with engineering and PMs
- Release readiness sign-off with stakeholders and sponsors

### Interaction with Existing Roles
- Works with Developers to align testing coverage and defect triage
- Collaborates with Product Managers to confirm acceptance criteria and user outcomes
- Reports project risk and release readiness to the Project Manager
- Coordinates with DevOps to ensure stable, representative environments for testing

---

## Technical Lead / Architect

### Role Summary
Technical Leads shape the technical direction of the solution and guide implementation decisions. They ensure the design remains aligned with quality, scalability, and maintainability goals while supporting the delivery team.

### Responsibilities
- Define the technical approach and architecture for key features
- Review and guide system design, trade-offs, and implementation decisions
- Mentor developers and support engineering standards
- Identify technical risks, dependencies, and long-term maintenance concerns
- Help prioritize technical debt and modernization work
- Partner with Product and Project leadership on feasibility and delivery sequencing

### Goals
- Deliver robust, maintainable solutions
- Reduce design drift and rework
- Support predictable execution and technical quality

### Typical Communication
- Design reviews and technical planning sessions
- Architecture decisions and engineering trade-off discussions
- Review feedback in pull requests and technical working sessions

### Interaction with Existing Roles
- Works closely with Developers to guide implementation and review technical quality
- Aligns with Product Managers on scope, feasibility, and sequencing trade-offs
- Advises Project Managers on delivery risk, dependencies, and planning assumptions
- Provides input to stakeholder updates when technical trade-offs affect roadmap or release timing

---

## Scrum Master / Team Facilitator

### Role Summary
Scrum Masters or Team Facilitators help the team work effectively by removing blockers, supporting healthy rituals, and improving the flow of delivery. They are accountable for process health rather than task ownership.

### Responsibilities
- Facilitate sprint planning, standups, retrospectives, and reviews
- Remove impediments that slow delivery or create confusion
- Coach the team on working agreements and Agile practices
- Track process friction, team health, and improvement opportunities
- Support cross-team alignment on dependencies and delivery flow

### Goals
- Improve team efficiency and delivery predictability
- Create a healthy, collaborative working environment
- Reduce friction caused by unclear process or unresolved blockers

### Typical Communication
- Team ceremonies and coaching conversations
- Dependency tracking and blocker escalation updates
- Retrospective outcomes and continuous improvement actions

### Interaction with Existing Roles
- Supports Project Managers by improving meeting flow and artifact consistency
- Helps Product Managers and Developers clarify priorities and reduce ambiguity in the backlog
- Coordinates with Stakeholders/Sponsors on escalation timing when external dependencies block work
- Works with QA and DevOps to ensure cross-functional handoffs are clear and timely

---

## UX / Design

### Role Summary
UX / Design partners with product and engineering to ensure solutions are usable, accessible, and aligned with customer needs. They turn user needs into clear interaction patterns and experience decisions.

### Responsibilities
- Define user flows, interaction patterns, and design standards
- Validate concepts with user research and usability feedback
- Translate customer needs into design requirements and acceptance criteria
- Collaborate with Developers and QA on implementation fidelity and edge cases
- Ensure accessibility and usability are considered in the product experience

### Goals
- Deliver intuitive, customer-friendly experiences
- Reduce rework caused by unclear product expectations
- Improve adoption and satisfaction with the final solution

### Typical Communication
- Design reviews and product discovery sessions
- Feedback loops with Product Managers and engineers
- Usability validation summaries and design handoff documentation

### Interaction with Existing Roles
- Partners with Product Managers to define customer problems and desired outcomes
- Works with Developers to ensure design intent is implemented correctly
- Supports QA in validating interactions, usability, and accessibility requirements
- Helps Project Managers and Stakeholders understand trade-offs related to user experience and customer value

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide strategic direction, funding context, and executive alignment for the project. They help ensure the work remains connected to business priorities and is supported across teams and functions.

### Responsibilities
- Define business goals, success criteria, and strategic priorities
- Approve scope changes, major commitments, and milestone decisions
- Remove organizational blockers and support cross-functional dependencies
- Review risk, status, and outcome progress at agreed intervals
- Champion the initiative internally and advocate for team support

### Goals
- Ensure business value is delivered and measurable
- Maintain alignment across leadership and delivery teams
- Support timely decisions and strategic focus

### Typical Communication
- Milestone reviews, steering updates, and leadership briefings
- Decision-making on scope, prioritization, and escalation issues
- Status updates tied to business outcomes and risks

### Interaction with Existing Roles
- Provides direction to Product Managers and Project Managers on priorities and business context
- Reviews delivery progress with Project Managers and key milestones with Product leadership
- Works with QA and Technical Leads on risk, readiness, and release confidence
- Helps resolve escalated blockers that require executive sponsorship or organizational support

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps / Infrastructure Engineers support the systems, automation, and deployment workflows needed for reliable delivery. They help the team move from code to production with fewer manual steps and lower operational risk.

### Responsibilities
- Manage environments, deployment pipelines, and release automation
- Support monitoring, observability, and operational health
- Improve reliability, scaling, and recovery readiness
- Partner with Developers and QA on build, test, and deployment validation
- Help define production readiness and rollback practices

### Goals
- Increase delivery speed without compromising stability
- Reduce deployment risk and operational surprises
- Support reliable, repeatable delivery across environments

### Typical Communication
- Release planning and deployment readiness reviews
- Incident coordination and operational health updates
- Environment and CI/CD feedback with engineering teams

### Interaction with Existing Roles
- Works with Developers to support build, deploy, and environment automation
- Coordinates with QA to create stable environments and validate release readiness
- Supports Project Managers with milestone and deployment risk tracking
- Helps Stakeholders and Sponsors understand operational readiness and deployment impacts

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Together, these roles create a clearer cross-functional model for planning, execution, quality, communication, and accountability.
