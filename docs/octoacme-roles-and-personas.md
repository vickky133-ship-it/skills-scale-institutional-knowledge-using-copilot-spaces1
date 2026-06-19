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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

### Tech Lead / Architect
**Role summary:** Provides technical direction and architectural guidance for the project.

**Responsibilities:**
- Define and validate high-level architecture and component boundaries
- Make technology trade-offs and own major design decisions
- Lead design reviews and ensure alignment to standards
- Mentor developers and drive engineering best practices
- Surface technical risks and mitigation plans

**Interactions:** Works closely with Developers (implementation & reviews), Product Managers (feasibility & constraints), Project Managers (scheduling & risks), and QA (non-functional requirements).

---

### DevOps / Platform Engineer
**Role summary:** Maintain CI/CD pipelines, infrastructure-as-code, and platform reliability.

**Responsibilities:**
- Implement and maintain deployment pipelines and automated testing gates
- Manage infrastructure-as-code, environments, and provisioning
- Configure observability, alerts, and runbooks
- Support release automation and rollback capabilities
- Assist incident response and post-incident remediation

**Interactions:** Collaborates with Developers (build & deploy readiness), Release Manager (deployment coordination), SRE/on-call, and Project Manager (deployment windows & risk mitigation).

---

### Security Engineer
**Role summary:** Ensure security considerations are embedded throughout the lifecycle.

**Responsibilities:**
- Run threat modeling and security reviews for designs and PRs
- Configure and monitor automated vulnerability and dependency scans
- Validate secrets handling, access controls, and compliance needs
- Coordinate remediation and advise on secure coding practices

**Interactions:** Partners with Developers (secure fixes & instrumentation), QA (security test cases), Product Manager (risk acceptance), and Compliance/Legal when required.

---

### UX Researcher / Designer
**Role summary:** Represent user needs through research, prototypes, and design guidance.

**Responsibilities:**
- Conduct user research and usability testing
- Produce wireframes, prototypes, and design specs
- Define UX acceptance criteria and validate implementation
- Collaborate on accessibility and user flows

**Interactions:** Works with Product Managers (requirements & success metrics), Developers (implementation fidelity), and QA (usability checks during acceptance testing).

---

### Data Analyst / Measurement Lead
**Role summary:** Define success metrics, instrumentation, and analyze product/feature performance.

**Responsibilities:**
- Define metrics, events, and dashboards to measure outcomes
- Validate instrumentation and ensure data quality
- Run experiments and analyses to inform decisions
- Translate findings into recommendations for the team

**Interactions:** Works with Product Managers (success metrics), Developers (instrumentation), Project Manager (status reporting), and Stakeholders (insights & decisions).

---

### Release Manager
**Role summary:** Coordinate and own the release process for production deployments.

**Responsibilities:**
- Create and maintain release checklists and schedules
- Coordinate release windows and stakeholder communications
- Author release notes and run post-release verifications
- Coordinate rollback and mitigation plans when needed

**Interactions:** Coordinates with DevOps, Project Manager, QA, Support, and Product Manager to ensure smooth releases.

---

### Technical Writer / Documentation Owner
**Role summary:** Own user-facing and internal documentation including runbooks and release notes.

**Responsibilities:**
- Maintain product and operational documentation
- Update runbooks and troubleshooting guides
- Author release notes, change logs, and user guides
- Ensure documentation is discoverable and accurate

**Interactions:** Works with Developers (technical accuracy), Product Manager (feature descriptions), Support (triage guidance), and Release Manager (release notes).

