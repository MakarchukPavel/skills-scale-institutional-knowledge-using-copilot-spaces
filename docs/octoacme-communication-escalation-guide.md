# OctoAcme — Communication and Escalation Guide

## Purpose
Provide clear guidance on communication practices, escalation paths, and blocker management to ensure efficient collaboration and timely resolution of issues across all roles.

## When to Use
- When encountering blockers that need escalation
- When unclear about communication channels or cadences
- During onboarding to understand team communication norms
- When planning cross-team collaboration

---

## Communication Principles

1. **Default to Transparency:** Share information openly unless there's a specific reason not to
2. **Prefer Async When Possible:** Use written communication for non-urgent matters to respect time zones and focus time
3. **Be Clear and Actionable:** State what you need, by when, and from whom
4. **Close the Loop:** Confirm receipt and completion of requested actions
5. **Escalate Early:** Don't wait until a blocker becomes critical—escalate proactively

---

## Communication Channels

### When to Use Each Channel

| Channel | Best For | Response Expectation |
|---------|----------|---------------------|
| **Slack/Teams (DM)** | Quick questions, casual coordination | Within 4 hours |
| **Slack/Teams (Channel)** | Team-wide updates, async discussions | Within 1 business day |
| **Email** | Stakeholder communication, formal decisions, documentation | Within 1 business day |
| **Project Board** | Task status, work tracking | Updated daily |
| **Video Call** | Complex discussions, sensitive topics, relationship building | Scheduled in advance |
| **Document Comments** | Feedback on specific content | Within 2 business days |

### Channel Selection Guidelines

**Use Slack/Teams DM for:**
- Quick clarifications that don't need to be documented
- Scheduling requests
- Checking availability

**Use Slack/Teams Channel for:**
- Questions that might benefit the whole team
- Daily standup updates (if async)
- Celebrating wins and sharing news

**Use Email for:**
- Stakeholder status updates
- Decisions that need documentation
- External communication

**Use Meetings for:**
- Sprint ceremonies
- Design reviews requiring discussion
- Conflict resolution
- 1:1s and performance conversations

---

## Communication Cadence

### Daily
| Activity | Participants | Duration | Owner |
|----------|-------------|----------|-------|
| Standup | Delivery team | 15 min | Scrum Master |
| Blocker follow-up | As needed | Variable | Scrum Master |

### Weekly
| Activity | Participants | Duration | Owner |
|----------|-------------|----------|-------|
| PM-PdM Sync | PM, PdM | 30 min | PM |
| Status Report | Stakeholders | Async | PM |
| Backlog Refinement | PdM, BA, Tech Lead, Team | 60 min | PdM |
| Design Review | UX, PdM, Developers | 30 min | UX Designer |

### Sprint-Based
| Activity | Participants | Duration | Owner |
|----------|-------------|----------|-------|
| Sprint Planning | Full team | 2-4 hours | Scrum Master |
| Sprint Review/Demo | Team, Stakeholders | 60 min | Scrum Master |
| Retrospective | Team | 60-90 min | Scrum Master |

### Monthly
| Activity | Participants | Duration | Owner |
|----------|-------------|----------|-------|
| Stakeholder Update | Stakeholders, PM, PdM | 30-60 min | PM |
| Architecture Review | Tech Lead, Developers | 60 min | Tech Lead |

---

## Escalation Framework

### What is Escalation?
Escalation is the process of raising an issue to someone with more authority or capability to resolve it. Escalation is **not** a sign of failure—it's a tool for effective problem-solving.

### When to Escalate
- Blocker cannot be resolved at your level
- Issue impacts sprint goals or release timeline
- Decision requires authority you don't have
- Cross-team dependency is not being addressed
- Risk has increased beyond acceptable threshold
- Stakeholder conflict needs mediation

### Escalation Levels

```
Level 1: Team-Level Resolution
    ↓ (If unresolved after 1 business day)
Level 2: PM / Tech Lead Escalation
    ↓ (If unresolved after 2 business days)
Level 3: Product Lead / Engineering Manager
    ↓ (If business-impacting)
Level 4: Sponsor / Executive Escalation
```

### Level 1: Team-Level Resolution
**Who:** Team members directly involved
**When:** First attempt at resolution
**Actions:**
- Discuss in standup or direct communication
- Collaborate to find solution
- Document attempted solutions

### Level 2: PM / Tech Lead Escalation
**Who:** Project Manager and/or Tech Lead
**When:** Team cannot resolve within 1 business day
**Actions:**
- PM coordinates with other teams or stakeholders
- Tech Lead provides technical alternatives
- Reprioritize work if needed

### Level 3: Product Lead / Engineering Manager
**Who:** Product Lead, Engineering Manager
**When:** Impact to sprint goals or release timeline
**Actions:**
- Resource reallocation
- Priority decisions
- Cross-functional coordination

### Level 4: Sponsor / Executive Escalation
**Who:** Project Sponsor, Director/VP level
**When:** Business-impacting issues, budget/resource decisions
**Actions:**
- Strategic decisions
- External partner coordination
- Significant scope changes

---

## Blocker Management

### What is a Blocker?
A blocker is any impediment that prevents work from progressing. This includes:
- **Technical blockers:** System access, environment issues, dependencies
- **Information blockers:** Unclear requirements, missing designs, pending decisions
- **Resource blockers:** Missing expertise, unavailable team members
- **External blockers:** Third-party dependencies, vendor issues

### Blocker Reporting Template

```markdown
**Blocker Title:** [Brief description]

**Description:** [What is blocked and why]

**Impact:** 
- Affected work items: [List tickets/stories]
- Sprint impact: [Can sprint goal still be met?]
- Timeline impact: [Days/hours of delay if unresolved]

**What's Needed:** [Specific resolution needed]

**Who Can Help:** [Person or team who can resolve]

**Deadline:** [When do we need resolution to avoid impact?]

**Status:** [Open/In Progress/Resolved]
```

### Blocker Management Process

1. **Identify:** Recognize and document the blocker immediately
2. **Communicate:** Raise in standup and/or Slack channel
3. **Assign:** Scrum Master or PM takes ownership of resolution
4. **Track:** Add to blocker list or board
5. **Escalate:** Follow escalation path if not resolved quickly
6. **Resolve:** Document resolution for future reference
7. **Update:** Communicate resolution to affected parties

### Blocker SLA Guidelines

| Blocker Severity | Expected Resolution Time | Escalation Trigger |
|-----------------|-------------------------|-------------------|
| **Critical** (Sprint goal at risk) | 4 hours | After 2 hours |
| **High** (Story blocked) | 1 business day | After 4 hours |
| **Medium** (Work slowed) | 2 business days | After 1 day |
| **Low** (Minor inconvenience) | 1 week | After 3 days |

---

## Cross-Role Communication Best Practices

### Developer ↔ QA
- **Developers:** Provide test instructions in PR, flag edge cases, be responsive to bug reports
- **QA:** Report bugs with clear reproduction steps, prioritize critical bugs, communicate testing timeline

### Developer ↔ UX Designer
- **Developers:** Ask clarifying questions early, flag feasibility concerns, share implementation constraints
- **UX:** Provide detailed specs, be available during implementation, review implemented designs promptly

### BA ↔ Product Manager
- **BA:** Ensure requirements are complete and validated, flag scope changes, support prioritization
- **PdM:** Communicate priorities clearly, provide context on business value, make timely decisions

### Scrum Master ↔ PM
- **Scrum Master:** Share team health and velocity, communicate process blockers, support risk identification
- **PM:** Provide project context, escalate external dependencies, support process improvements

### Tech Lead ↔ Product Manager
- **Tech Lead:** Communicate technical constraints, provide estimates, flag technical risks
- **PdM:** Share business context, be open to technical trade-offs, involve tech lead in planning

---

## Meeting Best Practices

### Before the Meeting
- [ ] Define clear purpose and desired outcomes
- [ ] Send agenda at least 24 hours in advance
- [ ] Include only necessary participants
- [ ] Share pre-read materials if needed
- [ ] Set up virtual meeting link and tools

### During the Meeting
- [ ] Start on time
- [ ] Assign note-taker and facilitator
- [ ] Stick to the agenda
- [ ] Ensure all voices are heard
- [ ] Document decisions and action items
- [ ] End on time (or get agreement to extend)

### After the Meeting
- [ ] Share notes within 24 hours
- [ ] Clearly list action items with owners and due dates
- [ ] Follow up on action items
- [ ] Request feedback on meeting effectiveness

### Meeting Notes Template

```markdown
**Meeting:** [Name]
**Date:** [Date]
**Attendees:** [List]

## Agenda
- Item 1
- Item 2

## Discussion Summary
- [Key points discussed]

## Decisions
- [Decision 1]
- [Decision 2]

## Action Items
| Action | Owner | Due Date |
|--------|-------|----------|
| [Task] | [Name] | [Date] |

## Next Meeting
[Date/Time or TBD]
```

---

## Conflict Resolution

### Common Sources of Conflict
- Priority disagreements
- Resource constraints
- Technical approach differences
- Unclear ownership
- Miscommunication

### Resolution Approach

1. **Address Early:** Don't let conflicts fester
2. **Focus on Facts:** Separate opinions from facts
3. **Seek Understanding:** Listen to all perspectives
4. **Find Common Ground:** Identify shared goals
5. **Collaborate on Solutions:** Work together toward resolution
6. **Escalate if Needed:** Involve PM or manager if unable to resolve

### Escalation for Conflicts
If direct resolution fails, escalate to:
- **Technical disagreements:** Tech Lead
- **Priority disagreements:** Product Manager
- **Process disagreements:** Scrum Master
- **Interpersonal conflicts:** Direct manager or HR

---

## Continuous Improvement for Communication

### Regular Reviews
- Discuss communication effectiveness in retrospectives
- Gather feedback on meeting quality
- Review escalation trends for systemic issues

### Improvement Actions
- Adjust communication channels based on team feedback
- Update escalation paths as team structure changes
- Document and share communication wins and lessons learned

---

## Quick Reference: Who to Contact

| Need | Contact | Backup |
|------|---------|--------|
| Requirements clarification | Business Analyst | Product Manager |
| Technical guidance | Tech Lead | Senior Developer |
| Process/ceremony questions | Scrum Master | Project Manager |
| Priority decisions | Product Manager | Project Sponsor |
| Schedule/resource issues | Project Manager | Engineering Manager |
| Design questions | UX Designer | Product Manager |
| Testing/quality questions | QA Lead | Tech Lead |
| Blocker escalation | Scrum Master → PM | Tech Lead |

---

## Related Documents
- [Roles & Personas](octoacme-roles-and-personas.md)
- [Onboarding Checklist](octoacme-onboarding-checklist.md)
- [Persona Workflow Checklist](octoacme-persona-workflow-checklist.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
