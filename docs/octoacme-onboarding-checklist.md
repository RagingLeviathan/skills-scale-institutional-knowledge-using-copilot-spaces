# OctoAcme — Onboarding & Role Assignment Checklist

## Purpose
A reusable checklist to onboard new team members and confirm role assignments at the start of every project. Complete this checklist during project initiation or when a new person joins the team.

---

## Part 1: Role Assignment

Use this section to confirm which person fills each role. Update the project one-pager and project board accordingly.

| Role | Assigned To | Confirmed? |
|---|---|---|
| Project Manager | | ☐ |
| Product Manager | | ☐ |
| Developer(s) | | ☐ |
| QA Lead | | ☐ |
| UX Designer | | ☐ |
| Technical Writer | | ☐ |
| Security Champion | | ☐ |
| Data Analyst | | ☐ |
| Stakeholder(s) | | ☐ |

> **Note:** Some roles may be filled by the same person on smaller teams. Confirm explicitly rather than assuming coverage. Refer to `docs/octoacme-roles-and-personas.md` for full role descriptions.

---

## Part 2: New Team Member Onboarding

Complete for each new person joining the project.

### Access & Tooling
- [ ] Added to the repository with appropriate permissions
- [ ] Added to the project board and relevant GitHub teams
- [ ] Communication channels set up (Slack/Teams channels, email lists)
- [ ] Access granted to required tools (design tools, analytics dashboards, CI/CD, etc.)
- [ ] Credentials or secrets provisioned through the approved secrets manager (not shared directly)

### Context & Documentation
- [ ] Project one-pager shared and reviewed
- [ ] Roles and responsibilities doc (`docs/octoacme-roles-and-personas.md`) shared
- [ ] Project management overview (`docs/octoacme-project-management-overview.md`) shared
- [ ] Current sprint backlog and board reviewed together
- [ ] Risk register and open risks reviewed
- [ ] Definition of Done reviewed and agreed upon

### Introductions & Meetings
- [ ] Introduced to the full team in standup or kickoff meeting
- [ ] 1:1 with Project Manager scheduled (first week)
- [ ] 1:1 with direct collaborators in adjacent roles scheduled
- [ ] Upcoming sprint ceremonies (planning, retrospective, review) added to calendar

### Role-Specific Onboarding

#### For QA Lead
- [ ] Test strategy and test plan locations shared
- [ ] CI test suite walkthrough completed
- [ ] Defect triage process reviewed
- [ ] Release sign-off process reviewed

#### For UX Designer
- [ ] Design tool workspace access granted (e.g., Figma project)
- [ ] Component library and design guidelines shared
- [ ] UX review cadence with developers established
- [ ] Accessibility standards reviewed

#### For Technical Writer
- [ ] Docs repository structure and style guide shared
- [ ] Documentation workflow (review, publish, versioning) explained
- [ ] Release notes process reviewed
- [ ] Existing docs gaps list shared if available

#### For Security Champion
- [ ] Security scanning tools and CI integration reviewed
- [ ] Threat model (if existing) shared
- [ ] Security incident runbook shared
- [ ] Dependency and SAST scan results reviewed

#### For Data Analyst
- [ ] Analytics platform access granted
- [ ] Success metrics and KPIs from project one-pager reviewed
- [ ] Instrumentation and event tracking plan shared
- [ ] Reporting cadence and stakeholder audience agreed

---

## Part 3: Ongoing Responsibility Confirmation

Review at the start of each new sprint or milestone to confirm ownership:

- [ ] All open backlog items have a named owner
- [ ] Risk register entries each have a named risk owner
- [ ] Documentation tasks are assigned (not left as "team")
- [ ] Security review items for the sprint are assigned to the Security Champion
- [ ] Test coverage responsibilities for the sprint are confirmed with the QA Lead
- [ ] Any open cross-role handoffs (design → dev, dev → QA, QA → release) are explicitly tracked on the project board

---

## References
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning Guide](octoacme-project-planning.md)
- [Execution & Tracking Guide](octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
