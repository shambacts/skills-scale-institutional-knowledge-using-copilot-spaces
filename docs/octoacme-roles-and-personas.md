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

### Interactions with Other Roles
- Collaborate with **Technical Leads** on architecture and design decisions
- Work with **QA/Testing Leads** to ensure testability and coverage
- Receive acceptance criteria and feedback from **Product Managers**
- Coordinate with **Project Managers** on scheduling and dependencies
- Support **Scrum Masters** in process adherence and sprint execution

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

### Interactions with Other Roles
- Align with **Business Stakeholders/Sponsors** on business objectives and priorities
- Define acceptance criteria and success metrics for **Developers**
- Work with **QA/Testing Leads** on test strategy and acceptance validation
- Coordinate with **Project Managers** on timeline and resource planning
- Receive technical feasibility input from **Technical Leads**

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

### Interactions with Other Roles
- Partner with **Scrum Masters** to facilitate agile ceremonies and remove blockers
- Escalate risks and dependencies identified by **Developers** and **Technical Leads**
- Coordinate with **Business Stakeholders/Sponsors** on approvals and decisions
- Track progress and quality metrics from **QA/Testing Leads**
- Report status to **Product Managers** and stakeholders

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy, test planning, and acceptance validation. They work closely with developers and product managers to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Define test strategy and test plans aligned with release priorities
- Create and maintain automated test suites (unit, integration, end-to-end)
- Execute manual QA and acceptance testing
- Collaborate with developers on testability and test coverage
- Identify and triage defects with severity and priority
- Validate acceptance criteria before sign-off
- Report quality metrics and risks to the team

### Goals
- Ensure features meet quality gates before release
- Maintain high test coverage and automation
- Reduce post-release defects and rework
- Enable fast feedback loops to developers

### Typical Communication
- QA review in sprint planning
- Daily standups and test status updates
- Defect reports and quality dashboards
- Pre-release sign-off coordination

### Interactions with Other Roles
- Collaborate with **Developers** on test design, automation, and defect resolution
- Review acceptance criteria with **Product Managers** to ensure clarity
- Report quality metrics and release readiness to **Project Managers** and **Technical Leads**
- Work with **Release/Deployment Teams** on smoke tests and validation
- Escalate critical defects to **Technical Leads** and **Project Managers**

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide technical strategy, design guidance, and system oversight. They ensure scalability, performance, and maintainability across the project.

### Responsibilities
- Define technical architecture and design patterns
- Review code and technical designs for quality and risk
- Identify technical risks and propose mitigations
- Mentor developers on technical best practices
- Make go/no-go decisions on technical approaches
- Ensure compliance with security and performance standards
- Participate in retrospectives to identify technical process improvements

### Goals
- Deliver technically sound, maintainable solutions
- Reduce technical debt and system complexity
- Enable team velocity through clear technical guidance
- Ensure system reliability and security

### Typical Communication
- Design review meetings
- Code review feedback
- Technical decision logs
- Risk escalation and mitigation planning

### Interactions with Other Roles
- Guide **Developers** on architecture, design patterns, and best practices
- Advise **Product Managers** on technical feasibility and effort estimates
- Collaborate with **QA/Testing Leads** on quality standards and test coverage
- Report technical risks to **Project Managers** and escalation paths
- Work with **Security/Compliance Officers** on security and performance requirements
- Support **Scrum Masters** in identifying and removing technical blockers

---

## Scrum Master / Process Facilitator

### Role Summary
Scrum Masters facilitate agile processes, sprint planning, and retrospectives. They remove blockers, coach the team on process adherence, and enable continuous improvement.

### Responsibilities
- Facilitate sprint planning, daily standups, and retrospectives
- Remove impediments and blockers for the team
- Coach team members on agile principles and practices
- Maintain sprint board and team velocity metrics
- Escalate process issues and organizational impediments
- Ensure team adheres to Definition of Done and agreed processes
- Facilitate continuous improvement discussions

### Goals
- Enable team velocity and sustainable pace
- Foster psychological safety and open communication
- Reduce process waste and bottlenecks
- Support team self-organization and accountability

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching conversations
- Retrospective facilitation and action item tracking
- Process improvement recommendations

### Interactions with Other Roles
- Support all team members in following agreed processes
- Partner with **Project Managers** to track progress and escalate organizational impediments
- Facilitate collaboration between **Developers**, **QA/Testing Leads**, and **Technical Leads**
- Help **Product Managers** refine backlog during planning sessions
- Coach **Business Stakeholders** on agile ceremonies and decision-making

---

## Business Stakeholder / Sponsor

### Role Summary
Business Stakeholders represent business priorities, funding, and executive visibility. They provide context for decisions and approval at key gates.

### Responsibilities
- Define business requirements and priorities
- Provide executive sponsorship and funding
- Make go/no-go decisions at project gates
- Communicate project status to broader organization
- Address business-level risks and dependencies
- Validate alignment with strategic objectives

### Goals
- Maximize business value delivery
- Ensure alignment with organizational strategy
- Enable fast decision-making at key milestones
- Maintain visibility and accountability

### Typical Communication
- Stakeholder alignment meetings
- Monthly status reports
- Gate reviews and approval meetings
- Incident escalation and communication

### Interactions with Other Roles
- Align with **Product Managers** on business objectives and priorities
- Provide approval and funding decisions for **Project Managers**
- Receive status updates and escalations from **Project Managers**
- Validate success metrics and business impact with **Product Managers** and **QA/Testing Leads**
- Make final go/no-go decisions on releases with input from **Technical Leads** and **Project Managers**

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure that projects meet security standards, compliance requirements, and threat mitigation practices.

### Responsibilities
- Define security and compliance requirements for features
- Conduct security reviews and threat assessments
- Coordinate security scanning in CI/CD pipeline
- Manage compliance audits and certifications
- Respond to security incidents and breaches
- Provide security training and guidance to teams
- Escalate security risks and manage remediation

### Goals
- Ensure all features meet security and compliance standards
- Reduce security vulnerabilities and data risks
- Maintain certifications and regulatory compliance
- Enable secure, trustworthy products

### Typical Communication
- Security review checkpoints
- Incident response coordination
- Compliance audit participation
- Security training and awareness updates

### Interactions with Other Roles
- Review technical architecture and designs with **Technical Leads** and **Developers**
- Define security acceptance criteria with **Product Managers** and **Project Managers**
- Integrate security requirements into test plans with **QA/Testing Leads**
- Report security compliance status to **Business Stakeholders/Sponsors**
- Escalate critical security issues through **Project Managers** to leadership
- Partner with **Release/Deployment Teams** on security verification before production

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Understand cross-functional interactions and dependencies between roles for realistic project scenarios.
