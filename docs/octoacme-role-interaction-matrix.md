# OctoAcme Role Interaction Matrix

## Purpose
Visualize and clarify how different roles interact, collaborate, and hand off work within OctoAcme projects. This matrix helps team members understand communication patterns, dependencies, and collaboration touchpoints across the project lifecycle.

## Scope
Applies to all cross-functional project teams. Use this matrix during onboarding, when clarifying responsibilities, or when diagnosing communication gaps.

---

## Primary Collaboration Patterns

This section describes the most frequent and critical interactions between roles. The intensity levels are:
- **High**: Daily or multiple times per week interaction
- **Medium**: Weekly or as-needed interaction
- **Low**: Occasional or milestone-based interaction

### Collaboration Matrix

| Role | Project Manager | Product Manager | Developer | Scrum Master | UX/UI Designer | Business Analyst | DevOps Engineer | QA Automation Engineer | Technical Writer | Sponsor/Executive |
|------|----------------|-----------------|-----------|--------------|----------------|------------------|-----------------|----------------------|------------------|-------------------|
| **Project Manager** | - | High | Medium | High | Medium | Medium | Medium | Medium | Low | High |
| **Product Manager** | High | - | High | Medium | High | High | Low | Medium | Medium | High |
| **Developer** | Medium | High | High | High | High | Medium | High | High | Medium | Low |
| **Scrum Master** | High | Medium | High | - | Medium | Medium | Low | Medium | Low | Low |
| **UX/UI Designer** | Medium | High | High | Medium | - | Medium | Low | Medium | Medium | Low |
| **Business Analyst** | Medium | High | Medium | Medium | Medium | - | Low | Low | Medium | Medium |
| **DevOps Engineer** | Medium | Low | High | Low | Low | Low | - | High | Low | Low |
| **QA Automation Engineer** | Medium | Medium | High | Medium | Medium | Low | High | - | Low | Low |
| **Technical Writer** | Low | Medium | Medium | Low | Medium | Medium | Low | Low | - | Low |
| **Sponsor/Executive** | High | High | Low | Low | Low | Medium | Low | Low | Low | - |

---

## Role Interaction Details by Project Phase

### Initiation Phase

**Primary Interactions:**
- **Sponsor/Executive ↔ Product Manager**: Define business case, strategic alignment, and success metrics
- **Product Manager ↔ Project Manager**: Establish project scope, timeline, and resource needs
- **Project Manager ↔ Business Analyst**: Gather initial requirements and stakeholder landscape
- **Business Analyst ↔ Stakeholders**: Elicit detailed requirements and constraints

**Key Handoffs:**
- Sponsor approves project charter and funding
- Product Manager defines problem statement and success criteria
- Project Manager creates project one-pager and initial plan
- Business Analyst delivers requirements document

---

### Planning Phase

**Primary Interactions:**
- **Project Manager ↔ Scrum Master**: Define iteration structure and team cadence
- **Product Manager ↔ UX/UI Designer**: Share user research and design priorities
- **Business Analyst ↔ Developer**: Clarify requirements and technical feasibility
- **Developer ↔ DevOps Engineer**: Plan infrastructure and deployment needs
- **Developer ↔ QA Automation Engineer**: Define testing strategy and coverage goals
- **Project Manager ↔ Technical Writer**: Identify documentation requirements

**Key Handoffs:**
- Product Manager prioritizes backlog
- UX/UI Designer provides design specifications and prototypes
- Business Analyst defines acceptance criteria
- DevOps Engineer outlines infrastructure requirements
- QA Automation Engineer creates test plan
- Project Manager publishes project plan and schedule

---

### Execution Phase

**Primary Interactions:**
- **Scrum Master ↔ Developer**: Daily standups, blocker removal, sprint ceremonies
- **Developer ↔ QA Automation Engineer**: Test development, failure investigation, quality metrics
- **Developer ↔ DevOps Engineer**: CI/CD pipeline, environment issues, deployment support
- **Developer ↔ UX/UI Designer**: Design implementation questions, design review feedback
- **Product Manager ↔ Developer**: Feature clarification, scope adjustments, priority changes
- **Project Manager ↔ All Roles**: Status updates, risk management, dependency coordination
- **Technical Writer ↔ Developer**: Documentation of new features and APIs

**Key Handoffs:**
- Developer submits pull requests for review
- QA Automation Engineer reports test results and coverage
- UX/UI Designer validates design implementation
- DevOps Engineer deploys to staging/production environments
- Technical Writer publishes updated documentation
- Scrum Master facilitates sprint review and retrospective

---

### Release & Deployment Phase

**Primary Interactions:**
- **Project Manager ↔ DevOps Engineer**: Coordinate deployment schedule and rollback plans
- **DevOps Engineer ↔ Developer**: Deployment execution and verification
- **QA Automation Engineer ↔ DevOps Engineer**: Production smoke testing and monitoring
- **Product Manager ↔ Sponsor/Executive**: Release readiness and business impact review
- **Technical Writer ↔ Product Manager**: Release notes and user-facing announcements

**Key Handoffs:**
- DevOps Engineer executes deployment
- QA Automation Engineer validates production deployment
- Technical Writer publishes release notes
- Product Manager announces feature availability
- Project Manager updates stakeholders on release status

---

### Retrospective & Continuous Improvement Phase

**Primary Interactions:**
- **Scrum Master ↔ All Team Members**: Facilitate retrospective discussion
- **Project Manager ↔ Scrum Master**: Review action items and process improvements
- **Product Manager ↔ Developer**: Review technical debt and improvement opportunities
- **Project Manager ↔ Sponsor/Executive**: Share lessons learned and recommendations

**Key Handoffs:**
- Scrum Master documents retrospective action items
- Project Manager archives project artifacts and lessons learned
- Product Manager incorporates feedback into roadmap
- All roles commit to improvement actions

---

## Common Collaboration Scenarios

### Scenario 1: New Feature Request
1. **Sponsor/Executive** → **Product Manager**: Business need identified
2. **Product Manager** → **Business Analyst**: Requirements elicitation needed
3. **Business Analyst** → **UX/UI Designer** & **Developer**: Share requirements for feasibility
4. **UX/UI Designer** → **Product Manager**: Present design concepts
5. **Product Manager** → **Project Manager**: Request timeline and resource estimate
6. **Project Manager** → **Scrum Master** & **Developer**: Estimate effort
7. **Project Manager** → **Sponsor/Executive**: Present proposal for approval

### Scenario 2: Production Issue Escalation
1. **DevOps Engineer**: Detects production issue
2. **DevOps Engineer** → **Developer**: Request investigation and fix
3. **Developer** → **QA Automation Engineer**: Validate fix in staging
4. **QA Automation Engineer** → **DevOps Engineer**: Approve deployment
5. **DevOps Engineer** → **Project Manager**: Report resolution
6. **Project Manager** → **Product Manager** & **Sponsor**: Status update if business-impacting

### Scenario 3: Requirements Clarification
1. **Developer**: Encounters unclear requirement
2. **Developer** → **Business Analyst**: Request clarification
3. **Business Analyst** → **Stakeholder**: Validate interpretation
4. **Business Analyst** → **Developer**: Provide clarification
5. **Developer** → **Scrum Master**: Remove blocker, continue work

### Scenario 4: Design Implementation Feedback
1. **Developer**: Implements design specification
2. **Developer** → **UX/UI Designer**: Request design review
3. **UX/UI Designer**: Identifies design deviations
4. **UX/UI Designer** → **Developer**: Provide feedback and updated specs
5. **Developer**: Adjusts implementation
6. **UX/UI Designer** → **QA Automation Engineer**: Confirm design validation in QA

### Scenario 5: Infrastructure Change Request
1. **Developer**: Needs new infrastructure capability
2. **Developer** → **DevOps Engineer**: Request infrastructure change
3. **DevOps Engineer** → **Project Manager**: Assess timeline impact
4. **Project Manager** → **Product Manager**: Evaluate priority vs. schedule
5. **Product Manager**: Approve or defer
6. **DevOps Engineer**: Implement if approved
7. **DevOps Engineer** → **Developer**: Infrastructure ready

---

## Role-Specific Interaction Guidelines

### For Project Managers
- **Daily**: Coordinate with Scrum Master on team blockers and progress
- **Weekly**: Sync with Product Manager on priorities and scope changes
- **Weekly**: Update Sponsor/Executive on status, risks, and decisions
- **As-needed**: Facilitate cross-role dependencies and escalations

### For Product Managers
- **Daily/Weekly**: Collaborate with Developers on feature clarification
- **Weekly**: Sync with UX/UI Designer on design priorities and user feedback
- **Weekly**: Align with Business Analyst on requirements and backlog refinement
- **Sprint-based**: Review progress with Scrum Master and team

### For Developers
- **Daily**: Coordinate with other Developers and Scrum Master in standups
- **Frequent**: Collaborate with QA Automation Engineer on testing
- **Frequent**: Work with DevOps Engineer on deployments and environment issues
- **As-needed**: Clarify requirements with Business Analyst or Product Manager
- **As-needed**: Consult UX/UI Designer on implementation details

### For Scrum Masters
- **Daily**: Facilitate standup with entire delivery team
- **Weekly**: Coordinate with Project Manager on project-level dependencies
- **Sprint-based**: Facilitate ceremonies with Product Manager and team
- **Continuous**: Remove blockers across all roles

### For UX/UI Designers
- **Weekly**: Sync with Product Manager on design priorities
- **Frequent**: Collaborate with Developers during implementation
- **As-needed**: Partner with Business Analyst on requirements validation
- **Review cycles**: Work with QA to validate design implementation

### For Business Analysts
- **Weekly**: Align with Product Manager and Project Manager on priorities
- **Frequent**: Clarify requirements for Developers
- **Regular**: Conduct stakeholder meetings and requirement workshops
- **As-needed**: Support UX/UI Designer with business context

### For DevOps Engineers
- **Daily/Weekly**: Support Developers with infrastructure and deployment needs
- **Regular**: Coordinate with QA Automation Engineer on test environments
- **Milestone-based**: Align with Project Manager on deployment schedules
- **Incident-based**: Escalate production issues quickly

### For QA Automation Engineers
- **Daily/Frequent**: Collaborate with Developers on test development
- **Regular**: Work with DevOps Engineer on test infrastructure
- **Sprint-based**: Report quality metrics to Project Manager and Product Manager
- **Continuous**: Validate features against acceptance criteria

### For Technical Writers
- **Sprint/Release-based**: Coordinate with Product Manager on documentation priorities
- **As-needed**: Work with Developers to document technical features
- **Review cycles**: Collaborate with UX/UI Designer on in-product help
- **Regular**: Sync with Project Manager to include docs in Definition of Done

### For Sponsors/Executive Stakeholders
- **Weekly/Monthly**: Review status with Project Manager
- **Strategic reviews**: Align with Product Manager on roadmap and business value
- **Decision points**: Provide input on scope, timeline, or resource changes
- **Escalations**: Resolve high-level organizational barriers

---

## Tips for Effective Cross-Role Collaboration

1. **Clarify handoff points**: Make explicit when work passes from one role to another
2. **Document decisions**: Use decision logs to capture context for cross-role agreements
3. **Respect expertise**: Trust each role's domain knowledge and professional judgment
4. **Communicate proactively**: Don't wait for scheduled meetings if you need input
5. **Use shared artifacts**: Reference common documents (project board, risk register, backlog)
6. **Default to transparency**: Share context broadly unless there's a reason not to
7. **Escalate appropriately**: Know when to resolve directly vs. when to involve Project Manager

---

## Updating This Matrix

This interaction matrix should evolve as team structures and processes mature. Propose updates via pull request when:
- New roles are added to the team
- Collaboration patterns change significantly
- Common interaction issues are identified
- Process improvements require different handoff points

---

## Related Resources
- [Roles and Personas](octoacme-roles-and-personas.md)
- [Team Onboarding Checklist](octoacme-team-onboarding-checklist.md)
- [Project Management Overview](octoacme-project-management-overview.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risks & Communication](octoacme-risks-and-communication.md)
