# OctoAcme — Persona Workflow Checklist

## Purpose
Provide role-specific task checklists for common workflows to ensure consistency, completeness, and cross-role collaboration throughout the project lifecycle.

## When to Use
- As a reference during daily work
- When onboarding to understand role expectations
- During planning to ensure all role responsibilities are covered
- In retrospectives to identify process gaps

---

## Scrum Master Workflow Checklist

### Daily Activities
- [ ] Facilitate daily standup (15 min max)
  - [ ] Each team member shares: progress, plans, blockers
  - [ ] Note any blockers or dependencies
  - [ ] Follow up on blockers immediately after standup
- [ ] Update team board/burndown if needed
- [ ] Check in with anyone who missed standup

### Sprint Planning Checklist
- [ ] Ensure Product Manager has refined backlog items ready
- [ ] Confirm team capacity and availability for the sprint
- [ ] Facilitate sprint goal discussion and commitment
- [ ] Ensure all sprint items have:
  - [ ] Clear acceptance criteria
  - [ ] Appropriate size/estimate
  - [ ] Assigned owner or pair
- [ ] Document sprint commitment and goal
- [ ] Set up sprint board/tracking

### Sprint Retrospective Checklist
- [ ] Prepare retrospective format and materials
- [ ] Create safe space for honest feedback
- [ ] Facilitate discussion:
  - [ ] What went well?
  - [ ] What could improve?
  - [ ] Action items
- [ ] Document action items with owners and due dates
- [ ] Follow up on action items from previous retrospective
- [ ] Share retrospective summary with team

### Blocker Management
- [ ] Document blocker clearly (what, impact, needed resolution)
- [ ] Identify who can help resolve
- [ ] Escalate to PM if blocker impacts sprint goals
- [ ] Track resolution and communicate to team
- [ ] Update board/status when resolved

---

## Business Analyst Workflow Checklist

### Requirements Discovery Checklist
- [ ] Identify stakeholders and schedule discovery sessions
- [ ] Prepare discussion guide and questions
- [ ] Document current state and pain points
- [ ] Capture desired outcomes and success criteria
- [ ] Identify constraints and dependencies
- [ ] Summarize findings and share with stakeholders for validation

### User Story Creation Checklist
- [ ] Write user story in standard format:
  - As a [user type], I want [goal] so that [benefit]
- [ ] Define clear, testable acceptance criteria
- [ ] Include any relevant:
  - [ ] Business rules
  - [ ] Edge cases
  - [ ] Dependencies
  - [ ] Links to designs or specs
- [ ] Review with Product Manager for priority
- [ ] Review with Tech Lead for feasibility
- [ ] Ensure story is ready for sprint planning

### Backlog Refinement Checklist
- [ ] Review upcoming backlog items with Product Manager
- [ ] Ensure items have sufficient detail for estimation
- [ ] Clarify requirements with stakeholders if needed
- [ ] Update acceptance criteria based on team questions
- [ ] Confirm dependencies are identified and tracked
- [ ] Mark items as "Ready" when fully refined

### UAT Coordination Checklist
- [ ] Define UAT scope and test scenarios
- [ ] Coordinate UAT schedule with stakeholders and QA
- [ ] Prepare test environment and data
- [ ] Support stakeholders during UAT
- [ ] Document UAT feedback and issues
- [ ] Confirm sign-off and track any follow-up items

---

## UX Designer Workflow Checklist

### Design Discovery Checklist
- [ ] Review requirements and user stories
- [ ] Conduct user research (interviews, surveys, analytics)
- [ ] Create user personas or validate existing ones
- [ ] Map user journeys and identify pain points
- [ ] Document research findings and insights
- [ ] Share findings with Product Manager and team

### Design Creation Checklist
- [ ] Create wireframes for key flows
- [ ] Review wireframes with Product Manager and BA
- [ ] Create high-fidelity mockups
- [ ] Ensure designs follow design system and style guide
- [ ] Validate accessibility (WCAG compliance)
- [ ] Create interactive prototype if needed
- [ ] Document design rationale and decisions

### Design Review Checklist
- [ ] Schedule design review with relevant stakeholders
- [ ] Present design context and rationale
- [ ] Gather feedback and document decisions
- [ ] Iterate based on feedback
- [ ] Confirm final design approval
- [ ] Update design files with any changes

### Design Handoff Checklist
- [ ] Prepare design specifications (spacing, colors, typography)
- [ ] Annotate complex interactions
- [ ] Export assets in required formats
- [ ] Share design files with developers
- [ ] Schedule handoff meeting to walk through designs
- [ ] Be available for developer questions during implementation
- [ ] Review implemented design and provide feedback

---

## Tech Lead Workflow Checklist

### Technical Planning Checklist
- [ ] Review upcoming features and requirements
- [ ] Identify technical approach and alternatives
- [ ] Create technical design document or ADR if significant
- [ ] Review with team and gather feedback
- [ ] Identify technical risks and dependencies
- [ ] Estimate complexity and communicate to PM/PdM
- [ ] Break down technical work into tasks

### Code Review Checklist
- [ ] Review for correctness and logic errors
- [ ] Check for security vulnerabilities
- [ ] Verify test coverage is adequate
- [ ] Ensure code follows style guide and conventions
- [ ] Look for maintainability and readability
- [ ] Check for performance implications
- [ ] Provide constructive, actionable feedback
- [ ] Approve or request changes with clear rationale

### Architecture Decision Checklist
- [ ] Document the decision context and problem
- [ ] List options considered with pros/cons
- [ ] Document the decision and rationale
- [ ] Identify any trade-offs or risks
- [ ] Communicate decision to affected teams
- [ ] Update architecture documentation

### Technical Debt Management Checklist
- [ ] Identify and document technical debt items
- [ ] Assess impact and urgency of each item
- [ ] Prioritize with Product Manager
- [ ] Allocate time in sprints for debt reduction
- [ ] Track progress and measure improvement
- [ ] Celebrate debt reduction wins

---

## Developer Workflow Checklist

### Feature Development Checklist
- [ ] Review acceptance criteria and designs
- [ ] Ask clarifying questions to BA/UX/Tech Lead
- [ ] Plan technical approach
- [ ] Write tests first (TDD) or alongside code
- [ ] Implement feature in small, reviewable increments
- [ ] Self-review code before requesting review
- [ ] Create PR with clear description and issue link
- [ ] Address code review feedback
- [ ] Verify feature works in test environment
- [ ] Support QA with testing if needed

### Pull Request Checklist
- [ ] PR is focused and <= 400 lines when possible
- [ ] PR description includes:
  - [ ] Issue/ticket link
  - [ ] Summary of changes
  - [ ] Testing done
  - [ ] Screenshots (for UI changes)
- [ ] All tests pass
- [ ] No linting errors
- [ ] Security scan passes
- [ ] At least one approval received
- [ ] Merge conflicts resolved

### Bug Fix Checklist
- [ ] Reproduce the bug and understand root cause
- [ ] Write a test that fails with the bug
- [ ] Implement fix
- [ ] Verify test passes
- [ ] Check for similar issues elsewhere
- [ ] Create PR with clear description
- [ ] Verify fix in test environment

---

## QA Workflow Checklist

### Test Planning Checklist
- [ ] Review requirements and acceptance criteria
- [ ] Identify test scenarios (happy path, edge cases, errors)
- [ ] Create test cases with steps and expected results
- [ ] Identify test data requirements
- [ ] Plan test environment needs
- [ ] Estimate testing effort

### Test Execution Checklist
- [ ] Prepare test environment and data
- [ ] Execute test cases systematically
- [ ] Document results (pass/fail)
- [ ] Report bugs with clear reproduction steps
- [ ] Retest fixed bugs
- [ ] Track test progress and coverage

### Bug Reporting Checklist
- [ ] Clear, descriptive title
- [ ] Steps to reproduce
- [ ] Expected vs. actual behavior
- [ ] Environment details (browser, OS, etc.)
- [ ] Screenshots or video if helpful
- [ ] Severity and priority assessment
- [ ] Related issue/feature link

### Release Testing Checklist
- [ ] Complete regression testing
- [ ] Execute smoke tests for critical paths
- [ ] Verify all acceptance criteria met
- [ ] Check for known issues and document
- [ ] Perform performance/load testing if applicable
- [ ] Validate accessibility compliance
- [ ] Sign off on release readiness

---

## Product Manager Workflow Checklist

### Backlog Management Checklist
- [ ] Review and prioritize incoming requests
- [ ] Define problem statement and success metrics
- [ ] Create epics and high-level stories
- [ ] Collaborate with BA on detailed requirements
- [ ] Review and approve acceptance criteria
- [ ] Communicate priorities to team
- [ ] Keep backlog groomed and prioritized

### Sprint Planning Checklist
- [ ] Ensure top priority items are refined and ready
- [ ] Communicate sprint goals and priorities
- [ ] Be available to answer questions during planning
- [ ] Confirm sprint commitment aligns with roadmap
- [ ] Document any scope trade-offs

### Stakeholder Management Checklist
- [ ] Maintain stakeholder communication plan
- [ ] Provide regular status updates
- [ ] Gather and incorporate feedback
- [ ] Manage expectations on timeline and scope
- [ ] Escalate blockers that need stakeholder input
- [ ] Celebrate wins and share successes

---

## Project Manager Workflow Checklist

### Weekly Status Checklist
- [ ] Review project board and progress
- [ ] Update risk register
- [ ] Prepare status update (progress, blockers, risks)
- [ ] Send status to stakeholders
- [ ] Follow up on open action items

### Risk Management Checklist
- [ ] Review risk register weekly
- [ ] Identify new risks from team discussions
- [ ] Assess impact and likelihood
- [ ] Define mitigation strategies
- [ ] Assign risk owners
- [ ] Monitor and update risk status
- [ ] Escalate high-impact risks appropriately

### Meeting Facilitation Checklist
- [ ] Send agenda in advance
- [ ] Start and end on time
- [ ] Ensure all voices are heard
- [ ] Document decisions and action items
- [ ] Share meeting notes promptly
- [ ] Follow up on action items

---

## Cross-Role Collaboration Checklist

### Sprint Readiness (All Roles)
- [ ] **BA:** Requirements documented with acceptance criteria
- [ ] **UX:** Designs complete and handed off
- [ ] **Tech Lead:** Technical approach validated
- [ ] **PdM:** Priority confirmed
- [ ] **Scrum Master:** Team capacity confirmed
- [ ] **QA:** Test approach identified

### Release Readiness (All Roles)
- [ ] **Developers:** Code complete and merged
- [ ] **QA:** Testing complete and signed off
- [ ] **Tech Lead:** Architecture and security reviewed
- [ ] **BA:** Acceptance criteria verified
- [ ] **PdM:** Feature validated against requirements
- [ ] **PM:** Stakeholders informed, release notes ready
- [ ] **UX:** Design implementation verified

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Onboarding Checklist](octoacme-onboarding-checklist.md)
- [Communication and Escalation Guide](octoacme-communication-escalation-guide.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
