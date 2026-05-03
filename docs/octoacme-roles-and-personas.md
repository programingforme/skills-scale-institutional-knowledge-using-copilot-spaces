# OctoAcme Personas

This document defines the roles and responsibilities used across OctoAcme project teams. It covers both core delivery roles and extended cross-functional contributors to ensure clarity, accountability, and efficient collaboration throughout the project lifecycle.

Roles documented here include: Developers, Product Managers, Project Managers, QA Lead, UX/UI Designer, DevOps Engineer, and Support/Customer Success Liaison.

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

## QA Lead

### Role Summary
The QA Lead coordinates and enforces testing practices throughout the delivery cycle. They work closely with Developers, Product Managers, and the Project Manager to ensure comprehensive test coverage, define acceptance criteria, and support quality gates at each release milestone.

### Responsibilities
- Define and maintain the test strategy, test plans, and acceptance criteria
- Coordinate manual and automated test execution across sprints
- Identify and track defects, and verify fixes in collaboration with Developers
- Own quality gates prior to release (see [Release & Deployment Guide](octoacme-release-and-deployment.md))
- Provide sign-off on release readiness and regression status
- Contribute quality insights to retrospectives (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md))

### Goals
- Prevent defects from reaching production by enforcing quality standards at every stage
- Increase automated test coverage to reduce manual regression effort
- Ensure acceptance criteria are clear and verifiable before development begins

### Typical Communication
- Sprint demos and test-result summaries shared with Project Manager and Product Manager
- Defect triage and bug reports coordinated with Developers
- Pre-release quality sign-off communicated to Project Manager and DevOps Engineer

### Collaboration with Other Roles
- **Developers**: Partners on testability, reviews acceptance criteria, validates fixes, and collaborates on automated test frameworks.
- **Product Manager**: Aligns on acceptance criteria and definition of done; flags ambiguous requirements early.
- **Project Manager**: Reports test progress and release readiness; escalates blocking defects that affect delivery timelines.
- **DevOps Engineer**: Coordinates on CI pipeline test execution and environment stability for test runs.
- **UX/UI Designer**: Reviews UI components against design specifications during acceptance testing.

---

## UX/UI Designer

### Role Summary
The UX/UI Designer shapes the user experience and product usability through research, design, and iterative collaboration. They partner with the Product Manager to validate user needs, and with Developers to ensure designs are implemented accurately and feasibly.

### Responsibilities
- Conduct user research and synthesize findings to inform design decisions
- Create wireframes, workflows, prototypes, and high-fidelity mockups
- Define and maintain the design system and UI standards
- Participate in design reviews and usability testing sessions
- Communicate design feasibility constraints and trade-offs to Product Manager and Developers

### Goals
- Deliver intuitive, accessible, and visually consistent user interfaces
- Reduce rework by validating design assumptions early with users and engineering
- Ensure user feedback informs product decisions and iterative improvements

### Typical Communication
- Design reviews and prototype walkthroughs shared with Product Manager and Developers
- Usability testing findings documented and shared with the broader team
- Handoff documentation (specs, assets, annotations) provided to Developers before implementation begins

### Collaboration with Other Roles
- **Product Manager**: Co-defines user problems, validates personas and journeys, and aligns on feature scope and acceptance criteria.
- **Developers**: Provides design specs and assets; participates in implementation reviews to verify visual and interaction fidelity.
- **QA Lead**: Supports acceptance testing of UI components against design specifications and design system standards.
- **Project Manager**: Flags design dependencies and timeline constraints; ensures design work is reflected in project plans.
- **Support/Customer Success Liaison**: Incorporates user feedback and pain points surfaced from support channels into design iterations.

---

## DevOps Engineer

### Role Summary
The DevOps Engineer automates deployment processes, manages CI/CD infrastructure, and monitors application reliability. They ensure that releases are stable and rollback-ready, and support Developers in troubleshooting environment and deployment issues.

### Responsibilities
- Build and maintain CI/CD pipelines for automated testing, building, and deployment
- Manage infrastructure-as-code, environment configurations, and secrets management
- Monitor application health, performance, and availability post-deployment
- Define and execute rollback and incident response procedures
- Collaborate with Project Manager on release scheduling and deployment windows (see [Release & Deployment Guide](octoacme-release-and-deployment.md))

### Goals
- Achieve reliable, repeatable, and low-risk deployment processes
- Reduce time-to-production through automation and optimized pipelines
- Maintain high system availability and fast incident recovery times

### Typical Communication
- Release readiness status and deployment plans shared with Project Manager and QA Lead
- Incident and post-mortem reports circulated to the full team
- Pipeline and infrastructure health metrics reviewed regularly with Developers

### Collaboration with Other Roles
- **Developers**: Advises on build configuration, deployment requirements, and environment parity; unblocks environment issues during development.
- **Project Manager**: Coordinates on deployment scheduling, change windows, and risk communication (see [Risk Management & Communication](octoacme-risks-and-communication.md)).
- **QA Lead**: Ensures test environments are stable and that CI pipeline integrates automated test execution.
- **Product Manager**: Communicates infrastructure constraints or capacity limitations that may affect feature delivery timelines.
- **Support/Customer Success Liaison**: Provides incident status updates and post-mortem summaries to help the support team communicate with customers.

---

## Support/Customer Success Liaison

### Role Summary
The Support/Customer Success Liaison gathers customer feedback, surfaces support insights during feature planning, and ensures user-reported issues are documented and prioritized. They serve as a bridge between the engineering and product teams and end users to support continuous improvement.

### Responsibilities
- Collect, triage, and document customer feedback and support requests
- Escalate recurring user issues and pain points to the Product Manager for backlog consideration
- Communicate product changes, release notes, and known issues to customers
- Collaborate with QA Lead and Developers on reproducing and validating customer-reported bugs
- Represent user perspective in planning and retrospective sessions

### Goals
- Reduce customer friction by ensuring user issues are visible and prioritized
- Improve customer satisfaction through timely communication of fixes and improvements
- Create a closed feedback loop between users and the product and engineering teams

### Typical Communication
- Regular feedback summaries and escalation reports shared with Product Manager and Project Manager
- Release notes and customer-facing communication coordinated with DevOps Engineer and Product Manager
- Bug reproduction details and support tickets shared with Developers and QA Lead

### Collaboration with Other Roles
- **Product Manager**: Provides customer insight and usage data to inform roadmap decisions; reviews upcoming features for user impact.
- **Project Manager**: Escalates urgent customer issues that require schedule adjustments or expedited fixes; participates in retrospectives (see [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)).
- **Developers**: Reports reproduction steps for customer-reported bugs; validates fixes from a user perspective.
- **QA Lead**: Coordinates on bug verification and validating that customer-reported issues are resolved before release.
- **DevOps Engineer**: Receives incident and outage status updates to communicate service disruptions to affected customers.
- **UX/UI Designer**: Shares user feedback and usability pain points to inform design improvements.

---

## Role Interaction Summary

The following table summarizes key handoffs and touchpoints between roles:

| From | To | Handoff / Interaction |
|---|---|---|
| Product Manager | QA Lead | Acceptance criteria and definition of done |
| QA Lead | Developers | Defect reports and test feedback |
| QA Lead | Project Manager | Release readiness sign-off |
| QA Lead | DevOps Engineer | CI test integration and environment health |
| UX/UI Designer | Developers | Design specs, assets, and implementation review |
| UX/UI Designer | Product Manager | Usability findings and design decisions |
| DevOps Engineer | Project Manager | Deployment plans and release window coordination |
| DevOps Engineer | QA Lead | Stable test environments and CI pipeline |
| Support/Customer Success Liaison | Product Manager | Customer feedback and issue escalations |
| Support/Customer Success Liaison | QA Lead | Bug reproduction details for customer-reported issues |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- For cross-functional scenarios, combine personas to simulate handoffs (e.g., QA Lead signing off before a DevOps Engineer deploys a release).

