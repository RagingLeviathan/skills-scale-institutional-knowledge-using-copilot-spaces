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

## QA Lead

### Role Summary
The QA Lead owns the overall quality strategy for a project. They design test plans, coordinate testing activities across the team, and act as the final gate before features are released.

### Responsibilities
- Define and maintain the test strategy, test plan, and Definition of Done quality criteria
- Coordinate manual and automated testing across sprint cycles
- Triage defects, prioritize bug fixes, and track resolution
- Review acceptance criteria for testability before sprint start
- Collaborate with Developers on test automation and CI integration
- Sign off on release readiness from a quality perspective

### Goals
- Prevent defect leakage to production
- Increase automated test coverage over time
- Ensure every feature meets its acceptance criteria before release

### Typical Communication
- Sprint planning and backlog grooming (testability review)
- Daily standups (blocker reporting and QA status)
- Release readiness sign-off reports

### Collaboration Touchpoints
- **Developers**: Pair on unit/integration test coverage and CI configuration
- **Product Manager**: Clarify acceptance criteria and edge cases
- **Project Manager**: Report test status and flag quality-related risks
- **Security Champion**: Coordinate security testing and penetration test results

---

## UX Designer

### Role Summary
The UX Designer ensures products are usable, accessible, and aligned with user needs. They translate user research and requirements into interaction patterns, wireframes, and design specifications.

### Responsibilities
- Conduct user research, interviews, and usability testing
- Produce wireframes, prototypes, and high-fidelity design specs
- Define and maintain design guidelines and component libraries
- Review implemented features against design specs before release
- Advocate for accessibility (WCAG) and inclusive design practices

### Goals
- Deliver intuitive, delightful user experiences
- Reduce rework caused by late-stage usability issues
- Maintain design consistency across the product

### Typical Communication
- Design reviews and critiques with Developers and Product Manager
- User research readouts and usability test findings
- Async feedback via design tool comments (e.g., Figma)

### Collaboration Touchpoints
- **Developers**: Hand off design specs and review implementations for fidelity
- **Product Manager**: Align on user stories, priorities, and research findings
- **QA Lead**: Confirm UI/UX acceptance criteria and accessibility checks
- **Technical Writer**: Provide UX copy and microcopy guidelines

---

## Technical Writer

### Role Summary
The Technical Writer creates and maintains user-facing and internal documentation, ensuring that processes, APIs, and features are clearly understood by all audiences.

### Responsibilities
- Write, edit, and publish user guides, API references, release notes, and process docs
- Collaborate with Developers and Product Managers to gather accurate content
- Maintain a documentation style guide and ensure consistency
- Review and update docs as part of the Definition of Done for each release
- Identify documentation gaps and proactively propose improvements

### Goals
- Ensure every feature shipped has clear, accurate documentation
- Reduce support tickets and onboarding friction through better docs
- Maintain a single source of truth for product and process knowledge

### Typical Communication
- Sprint reviews to capture feature changes needing documentation
- Async collaboration via doc drafts and PR reviews
- Coordination with Product Manager on release notes and changelog

### Collaboration Touchpoints
- **Developers**: Review technical accuracy of API docs and code examples
- **Product Manager**: Align on feature descriptions and user-facing messaging
- **QA Lead**: Confirm documented steps match actual product behavior
- **UX Designer**: Obtain UX copy, microcopy, and UI terminology

---

## Security Champion

### Role Summary
The Security Champion embeds security thinking into the development process. They act as the team's security advocate, ensuring threats are identified early and security standards are upheld throughout the lifecycle.

### Responsibilities
- Conduct threat modeling during planning and design phases
- Review code and architecture for security vulnerabilities
- Ensure security scanning (SAST, DAST, dependency checks) is integrated into CI
- Triage and prioritize security findings and coordinate remediation
- Maintain and communicate the team's security incident runbook
- Stay current on CVEs and emerging threats relevant to the stack

### Goals
- Shift security left — identify and fix issues before they reach production
- Ensure compliance with internal security policies and regulatory requirements
- Reduce mean time to remediate (MTTR) for security vulnerabilities

### Typical Communication
- Planning sessions (threat modeling and security requirements)
- Security scan reports and vulnerability triage meetings
- Incident post-mortems with security implications

### Collaboration Touchpoints
- **Developers**: Pair on secure coding practices and vulnerability remediation
- **QA Lead**: Integrate security testing into the test plan
- **Project Manager**: Communicate security risks and timelines for remediation
- **DevOps/Infrastructure**: Enforce secrets management and hardened pipeline configs

---

## Data Analyst

### Role Summary
The Data Analyst turns raw data into actionable insights that inform product decisions, track project health, and validate the impact of shipped features.

### Responsibilities
- Define and track key metrics and KPIs aligned to project success criteria
- Build dashboards and reports for project and product health monitoring
- Analyze usage data, experiment results, and business outcomes
- Support A/B test design and statistical analysis
- Identify data quality issues and work with Engineering to resolve them

### Goals
- Enable data-informed decision-making across the team
- Provide timely, accurate reporting on project outcomes
- Surface early signals of risk or opportunity from product data

### Typical Communication
- Weekly metrics reviews with Product Manager and Project Manager
- Ad-hoc analysis requests from stakeholders
- Experiment readouts at sprint reviews or milestone checkpoints

### Collaboration Touchpoints
- **Product Manager**: Co-define success metrics and interpret experiment results
- **Project Manager**: Provide data to support status reporting and risk assessment
- **Developers**: Collaborate on instrumentation, event tracking, and data pipelines
- **QA Lead**: Validate that tracking and analytics implementations are accurate

---

## Cross-Role Interactions Summary

| Handoff / Interaction | Roles Involved | Key Output |
|---|---|---|
| Feature scoping & acceptance criteria | Product Manager, Developers, QA Lead, UX Designer | Backlog items with testable acceptance criteria |
| Design to development handoff | UX Designer, Developers, Technical Writer | Design specs, UX copy, and dev-ready stories |
| Security review during planning | Security Champion, Project Manager, Developers | Threat model, security requirements |
| Test readiness sign-off | QA Lead, Developers, Security Champion | Release readiness report |
| Documentation before release | Technical Writer, Product Manager, QA Lead | Updated docs, release notes |
| Post-release metrics review | Data Analyst, Product Manager, Project Manager | Outcome report, next iteration data |
| Retrospective action items | All roles | Improvement backlog items with clear owners |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See `docs/octoacme-onboarding-checklist.md` for a reusable checklist to assign roles and onboard new team members.

