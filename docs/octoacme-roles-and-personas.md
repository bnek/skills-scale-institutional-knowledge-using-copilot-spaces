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
Scrum Masters facilitate Agile ceremonies, remove impediments, and champion Agile principles. They coach the team on self-organization and continuous improvement, ensuring delivery flow is optimized.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and organizational impediments
- Coach team on Agile/Scrum practices and principles
- Shield the team from external distractions
- Foster a culture of continuous improvement and psychological safety

### Goals
- Maximize team velocity and predictability
- Reduce impediments and delivery friction
- Improve team collaboration and self-organization

### Typical Communication
- Daily facilitation of standups
- Sprint ceremonies (planning, review, retro)
- One-on-one coaching with team members
- Coordination with Project Managers on cross-team dependencies

### Interactions with Other Roles
- **Project Manager**: Collaborates on project timelines, dependencies, and escalations. While PM focuses on cross-project coordination and stakeholder management, Scrum Master focuses on team-level delivery flow and Agile practices.
- **Product Manager**: Participates in backlog refinement and ensures the team understands acceptance criteria and priorities.
- **Developers**: Coaches on Agile practices, facilitates ceremonies, and removes blockers that prevent development progress.

---

## UX/UI Designer

### Role Summary
UX/UI Designers create intuitive, user-centered experiences and interfaces. They research user needs, design prototypes, and collaborate with Product Managers and Developers to validate requirements and ensure designs are technically feasible.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user interfaces aligned with brand guidelines
- Collaborate with developers to ensure design feasibility
- Validate designs through user feedback and metrics

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction scores
- Ensure design consistency across the product

### Typical Communication
- Weekly syncs with Product Managers and developers
- Design reviews and critique sessions
- User research findings and recommendations
- Handoff documentation and design specs

### Interactions with Other Roles
- **Product Manager**: Partners closely to understand user needs, validate design solutions, and ensure alignment with product vision and business goals.
- **Developers**: Provides design specifications, assets, and guidance during implementation. Reviews implementation to ensure design fidelity.
- **Project Manager**: Coordinates on design milestones, dependencies, and timeline impacts when design iterations are needed.
- **QA/Testing**: Collaborates on usability testing and validates that implemented features match design specifications.

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business stakeholders and delivery teams. They elicit requirements, document business logic, analyze processes, and ensure acceptance criteria are clear and testable.

### Responsibilities
- Gather and document business requirements
- Create process flows and business logic documentation
- Define and refine acceptance criteria with stakeholders
- Analyze data to support decision-making
- Facilitate requirements workshops with stakeholders

### Goals
- Ensure clear, complete requirements
- Reduce rework from misunderstood requirements
- Improve alignment between business needs and technical solutions

### Typical Communication
- Requirements workshops and stakeholder interviews
- Documentation of business processes and logic
- Backlog refinement sessions
- Impact analysis reports

### Interactions with Other Roles
- **Product Manager**: Supports requirement gathering and helps translate business needs into product features. May work alongside PdM or fill this role in projects without a dedicated Product Manager.
- **Project Manager**: Provides detailed requirements documentation and supports scope definition and change management.
- **Developers**: Clarifies business logic, answers questions about requirements, and validates technical solutions meet business needs.
- **Stakeholders**: Acts as primary liaison for requirement elicitation and validation.

---

## DevOps Engineer

### Role Summary
DevOps Engineers design, build, and maintain CI/CD pipelines, infrastructure, and deployment automation. They enable reliable, frequent releases and ensure development and production environments are stable and secure.

### Responsibilities
- Build and maintain CI/CD pipelines
- Manage infrastructure as code (IaC)
- Monitor system health, performance, and security
- Automate deployment and rollback procedures
- Ensure development and production environment parity

### Goals
- Enable fast, reliable deployments with minimal manual intervention
- Maintain high system availability and performance
- Reduce time from commit to production

### Typical Communication
- Daily coordination with developers on build and deployment issues
- Incident response and postmortem participation
- Infrastructure planning with Project Managers and architects
- Security and compliance reporting

### Interactions with Other Roles
- **Developers**: Provides infrastructure, tooling, and pipeline support. Collaborates on build optimization and deployment strategies.
- **Project Manager**: Coordinates on infrastructure timelines, capacity planning, and deployment schedules.
- **QA/Testing**: Provides test environments and collaborates on automation infrastructure for testing.
- **Product Manager**: Informs about infrastructure constraints that may affect feature delivery or performance.

---

## Sponsor / Executive Stakeholder

### Role Summary
Sponsors and Executive Stakeholders provide strategic direction, funding, and business context for projects. They resolve high-level escalations, validate business case alignment, and ensure projects deliver organizational value.

### Responsibilities
- Provide project funding and resource authorization
- Set strategic priorities and business objectives
- Review project status and key decisions
- Resolve escalations that impact business outcomes
- Approve major scope or timeline changes

### Goals
- Ensure projects deliver expected business value and ROI
- Maintain portfolio alignment with strategic objectives
- Enable teams to deliver with appropriate support and resources

### Typical Communication
- Monthly or quarterly project status reviews
- Executive briefings and decision points
- Strategic planning sessions
- Escalation resolution

### Interactions with Other Roles
- **Project Manager**: Receives regular status updates, escalations, and requests for decisions on scope, timeline, or resource changes.
- **Product Manager**: Reviews product strategy, validates business case, and provides strategic direction on priorities.
- **All Roles**: Provides organizational context and removes high-level organizational barriers to project success.

---

## QA Automation Engineer

### Role Summary
QA Automation Engineers design, build, and maintain automated test suites and frameworks. They work with Developers, QA, and Project Managers to improve test coverage, reduce manual testing overhead, and increase product quality.

### Responsibilities
- Design and implement automated test frameworks
- Build and maintain automated test suites (unit, integration, E2E)
- Integrate automated tests into CI/CD pipelines
- Monitor test results and investigate failures
- Mentor developers on testing best practices

### Goals
- Achieve comprehensive automated test coverage
- Reduce manual testing time and effort
- Catch defects early in the development process

### Typical Communication
- Daily standup participation and blocker resolution
- Test strategy discussions with developers and QA
- CI/CD pipeline reviews with DevOps Engineers
- Quality metrics reporting

### Interactions with Other Roles
- **Developers**: Collaborates on testability, reviews test code, and provides guidance on testing practices and frameworks.
- **Project Manager**: Reports on test coverage, quality metrics, and testing-related risks or timeline impacts.
- **DevOps Engineer**: Integrates automated tests into CI/CD pipelines and ensures test environments are stable.
- **QA/Testing**: Complements manual testing efforts and helps prioritize automation opportunities.

---

## Technical Writer

### Role Summary
Technical Writers create and maintain comprehensive technical documentation, API guides, user help content, and process documentation. They ensure documentation is accurate, clear, accessible, and up-to-date.

### Responsibilities
- Write and maintain product documentation and user guides
- Create API documentation and developer resources
- Document processes and operational procedures
- Maintain documentation repositories and style guides
- Collaborate with subject matter experts to ensure accuracy

### Goals
- Provide clear, accurate documentation for all audiences
- Reduce support burden through self-service documentation
- Ensure documentation stays current with product changes

### Typical Communication
- Regular syncs with Product Managers and developers
- Documentation reviews with subject matter experts
- User feedback sessions
- Content planning and strategy discussions

### Interactions with Other Roles
- **Product Manager**: Aligns on documentation priorities, user needs, and product roadmap to plan documentation updates.
- **Developers**: Collaborates to document technical features, APIs, and integration guides. Reviews code comments and specifications.
- **Project Manager**: Coordinates documentation milestones and ensures docs are included in Definition of Done.
- **UX/UI Designer**: Partners on in-product help, tooltips, and user-facing guidance to ensure consistency.
- **All Roles**: Documents processes and serves as a resource for maintaining accurate project and operational documentation.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

