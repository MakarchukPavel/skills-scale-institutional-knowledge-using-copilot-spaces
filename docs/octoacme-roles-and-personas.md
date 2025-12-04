# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises. It covers both existing core roles and extended team roles, along with their communication patterns and collaboration scenarios.

---

## Core Team Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

#### Collaboration with Other Roles
- **With Tech Lead:** Receive technical guidance, participate in architecture decisions, and code reviews
- **With Scrum Master:** Report blockers, participate in ceremonies, provide feedback on process
- **With Business Analyst:** Clarify requirements, discuss technical feasibility, estimate effort
- **With UX Designer:** Implement designs, provide feedback on feasibility, collaborate on prototypes
- **With QA:** Address bugs, collaborate on test coverage, support acceptance testing

---

### Product Managers (PdM)

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

#### Collaboration with Other Roles
- **With Project Manager (PM):** Align on timelines, communicate priorities, coordinate releases
- **With Tech Lead:** Discuss technical constraints, evaluate trade-offs, align on architecture decisions
- **With Business Analyst:** Define requirements, validate user stories, prioritize backlog items
- **With UX Designer:** Collaborate on user research, validate designs against business goals
- **With Scrum Master:** Support sprint planning, provide backlog clarity, participate in retrospectives

---

### Project Managers (PM)

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

#### Collaboration with Other Roles
- **With Product Manager (PdM):** Weekly syncs, priority alignment, release coordination
- **With Scrum Master:** Coordinate on process, share risk visibility, align on team health
- **With Tech Lead:** Understand technical risks, coordinate resource allocation
- **With Business Analyst:** Track requirements status, manage scope changes
- **With UX Designer:** Coordinate design timelines, track design deliverables

---

### QA / Testing

#### Role Summary
QA specialists validate quality against acceptance criteria and ensure features meet the expected standards before release.

#### Responsibilities
- Create and execute test plans and test cases
- Perform functional, regression, and exploratory testing
- Document and track defects
- Collaborate with developers on bug resolution
- Support acceptance testing with stakeholders

#### Goals
- Ensure high-quality releases with minimal defects
- Maintain comprehensive test coverage
- Reduce time to identify and resolve issues

#### Typical Communication
- Daily standups and sprint planning
- Bug reports and test result documentation
- Collaboration with developers on defect resolution

#### Collaboration with Other Roles
- **With Developers:** Report bugs, verify fixes, collaborate on test automation
- **With Tech Lead:** Align on quality standards, test strategy, and technical debt
- **With Business Analyst:** Validate acceptance criteria, ensure requirements are testable
- **With UX Designer:** Test usability, accessibility, and design consistency
- **With Scrum Master:** Report testing progress, identify quality-related blockers

---

## Extended Team Roles

### Scrum Master

#### Role Summary
Scrum Masters facilitate Agile ceremonies, remove impediments, and coach the team on Scrum practices. They serve as servant leaders who help the team continuously improve.

#### Responsibilities
- Facilitate Scrum ceremonies (daily standups, sprint planning, retrospectives, sprint reviews)
- Remove blockers and impediments that slow the team
- Coach the team on Agile/Scrum best practices
- Shield the team from external distractions and scope creep
- Track and report team velocity and sprint progress
- Foster a culture of continuous improvement

#### Goals
- Enable consistent, predictable delivery
- Improve team velocity and efficiency over time
- Promote self-organization and accountability
- Maintain a healthy, collaborative team dynamic

#### Typical Communication
- Facilitate daily standups (15 min max)
- Lead sprint planning and backlog refinement sessions
- Conduct retrospectives and track action items
- Escalate blockers to PM or leadership when needed

#### Collaboration with Other Roles
- **With Developers:** Support daily work, remove blockers, track progress, facilitate estimation
- **With Project Manager (PM):** Share risk visibility, coordinate on process improvements, align on team capacity
- **With Product Manager (PdM):** Support backlog refinement, ensure sprint goals are clear
- **With Tech Lead:** Coordinate on technical blockers, support architecture discussions
- **With Business Analyst:** Ensure user stories are well-defined before sprint planning
- **With UX Designer:** Track design dependencies, ensure design work is sprint-ready
- **With QA:** Monitor testing progress, address quality-related blockers

#### Typical Collaboration Scenario
> **Scenario:** A developer reports a blocker during standup—they're waiting on a design decision.
> **Action:** The Scrum Master immediately follows up with the UX Designer after standup to clarify the timeline, then updates the team and adjusts sprint commitments if needed.

---

### Business Analyst (BA)

#### Role Summary
Business Analysts bridge the gap between stakeholders and the delivery team. They gather, refine, and document requirements to ensure the team builds the right thing.

#### Responsibilities
- Gather and document business requirements from stakeholders
- Translate requirements into user stories with clear acceptance criteria
- Facilitate requirements workshops and discovery sessions
- Validate that delivered features meet business needs
- Maintain requirements traceability and documentation
- Support UAT (User Acceptance Testing) coordination

#### Goals
- Ensure requirements are clear, complete, and testable
- Minimize requirements churn and rework
- Bridge communication between business and technical teams
- Deliver features that meet actual user needs

#### Typical Communication
- Stakeholder interviews and discovery sessions
- Requirements documentation and user story creation
- Backlog refinement sessions with Product Manager
- UAT coordination with QA and stakeholders

#### Collaboration with Other Roles
- **With Product Manager (PdM):** Refine backlog items, validate priorities, ensure requirements align with product vision
- **With Developers:** Clarify requirements, answer questions, validate technical feasibility
- **With Tech Lead:** Discuss technical constraints, evaluate implementation options
- **With QA:** Define acceptance criteria, support test case creation, coordinate UAT
- **With UX Designer:** Align on user flows, validate designs against requirements
- **With Scrum Master:** Ensure stories are sprint-ready, participate in refinement sessions
- **With Project Manager (PM):** Track requirements status, manage scope changes

#### Typical Collaboration Scenario
> **Scenario:** A stakeholder requests a new feature with vague requirements.
> **Action:** The BA schedules a discovery session with the stakeholder, documents the requirements, collaborates with the UX Designer on user flows, then works with developers to estimate effort and writes user stories for the Product Manager to prioritize.

---

### UX Designer

#### Role Summary
UX Designers create user-centered designs that are intuitive, accessible, and aligned with business goals. They research user needs, design interfaces, and validate solutions through testing.

#### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define user flows and information architecture
- Establish and maintain design systems and style guides
- Collaborate with developers on implementation feasibility
- Validate designs against accessibility standards (WCAG)

#### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Ensure design consistency across the product
- Validate designs through user feedback before development

#### Typical Communication
- Design reviews and critiques
- User research presentations and findings
- Design handoff sessions with developers
- Usability testing reports

#### Collaboration with Other Roles
- **With Product Manager (PdM):** Align designs with product vision, validate against business goals, collaborate on user research
- **With Developers:** Provide design specifications, discuss implementation feasibility, iterate on designs
- **With Tech Lead:** Evaluate technical constraints, align on component architecture
- **With Business Analyst:** Validate user flows, ensure designs meet requirements
- **With QA:** Support usability testing, provide test scenarios, validate accessibility
- **With Scrum Master:** Communicate design timeline, flag dependencies early
- **With Project Manager (PM):** Track design deliverables, manage design-related risks

#### Typical Collaboration Scenario
> **Scenario:** A new feature is being planned that requires a significant UI change.
> **Action:** The UX Designer conducts user research to understand needs, creates wireframes and presents to the team, collaborates with the Tech Lead on feasibility, iterates based on feedback, then hands off final designs to developers with detailed specifications.

---

### Tech Lead

#### Role Summary
Tech Leads provide technical leadership and guidance to the development team. They make architectural decisions, ensure code quality, and mentor team members on best practices.

#### Responsibilities
- Make architecture and technology decisions
- Lead technical design discussions and reviews
- Mentor developers and conduct code reviews
- Ensure code quality, security, and maintainability
- Identify and address technical debt
- Collaborate with Product and Project Managers on technical trade-offs
- Support incident response and production issues

#### Goals
- Maintain a scalable, secure, and maintainable codebase
- Reduce technical debt and improve system reliability
- Enable developer productivity and growth
- Deliver technical solutions that meet business needs

#### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code review feedback and mentoring sessions
- Technical sync meetings with PM and PdM
- Incident postmortems and technical retrospectives

#### Collaboration with Other Roles
- **With Developers:** Provide guidance, conduct code reviews, mentor on best practices, lead architecture discussions
- **With Product Manager (PdM):** Evaluate technical feasibility, communicate constraints, propose alternatives
- **With Project Manager (PM):** Identify technical risks, estimate complexity, support resource planning
- **With Scrum Master:** Address technical blockers, participate in sprint planning
- **With Business Analyst:** Evaluate implementation options, clarify technical constraints
- **With UX Designer:** Discuss design feasibility, align on component architecture
- **With QA:** Define quality standards, support test strategy, address critical bugs

#### Typical Collaboration Scenario
> **Scenario:** The team is considering adopting a new technology for a critical feature.
> **Action:** The Tech Lead researches options, creates a technical design document with pros/cons, presents to the team and stakeholders, collaborates with the PM on timeline impact, and leads a proof-of-concept implementation with developers.

---

## Role Interaction Matrix

This matrix shows the primary communication flows between roles:

| From / To | PM | PdM | Developers | QA | Scrum Master | BA | UX Designer | Tech Lead |
|-----------|----|----|------------|----|--------------|----|-------------|-----------|
| **PM** | — | Weekly sync | Status updates | Release coord | Process alignment | Scope mgmt | Timeline coord | Risk assessment |
| **PdM** | Priority alignment | — | Backlog clarity | UAT support | Sprint goals | Requirements | Design direction | Trade-offs |
| **Developers** | Blockers | Technical Q&A | Code reviews | Bug fixes | Progress updates | Requirement Q&A | Implementation | Technical guidance |
| **QA** | Test status | Acceptance | Bug reports | — | Quality blockers | Test criteria | Usability testing | Quality standards |
| **Scrum Master** | Process updates | Backlog health | Blocker removal | Testing progress | — | Story readiness | Design dependencies | Tech blockers |
| **BA** | Scope changes | Backlog refinement | Clarifications | UAT coord | Sprint readiness | — | User flow alignment | Feasibility |
| **UX Designer** | Design timeline | Design review | Design handoff | Usability testing | Dependencies | Flow validation | — | Feasibility |
| **Tech Lead** | Technical risks | Constraints | Code reviews | Test strategy | Tech blockers | Tech feasibility | Design feasibility | — |

---

## Communication Cadence by Role

| Role | Daily | Weekly | Sprint-Based | As Needed |
|------|-------|--------|--------------|-----------|
| **PM** | — | PM-PdM sync, Status reports | Sprint planning, Retrospectives | Stakeholder escalations |
| **PdM** | — | PM-PdM sync, Stakeholder updates | Sprint planning, Backlog refinement | Priority decisions |
| **Developers** | Standup | — | Sprint planning, Retrospectives | Code reviews, Technical discussions |
| **QA** | Standup | — | Sprint planning, Retrospectives | Bug triage, Test reviews |
| **Scrum Master** | Standup facilitation | Team health check | All ceremonies | Blocker escalation |
| **BA** | Standup (optional) | Stakeholder sessions | Backlog refinement | Discovery sessions |
| **UX Designer** | Standup (optional) | Design reviews | Backlog refinement | User research, Design crits |
| **Tech Lead** | Standup | Technical sync | Sprint planning, Retrospectives | Architecture reviews |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the interaction matrix when planning cross-functional work.
- Use the collaboration scenarios as examples for onboarding new team members.

## Related Documents
- [Onboarding Checklist](octoacme-onboarding-checklist.md) — Getting new team members up to speed
- [Persona Workflow Checklist](octoacme-persona-workflow-checklist.md) — Role-specific task checklists
- [Communication and Escalation Guide](octoacme-communication-escalation-guide.md) — Best practices for collaboration and escalation

