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

## Technical Program Manager (TPM)

### Role Summary
Technical Program Managers coordinate cross-team technical dependencies and manage architecture-level risks. They facilitate technical decision-making and maintain visibility into integration points across large initiatives.

### Responsibilities
- Coordinate cross-team technical dependencies and integration points
- Track architecture-level risks and escalate technical blockers
- Facilitate technical decision meetings and design reviews
- Maintain dependency register for complex initiatives
- Collaborate with developers and tech leads on technical feasibility
- Support planning activities with technical complexity assessments

### Goals
- Minimize integration delays and technical rework
- Reduce risk of architectural misalignment across teams
- Enable faster technical decision-making through clear ownership
- Improve visibility into technical dependencies

### Interactions
- **Partners with PM**: aligns schedule to technical complexity and dependencies
- **Works with Developers and Tech Leads**: understands design decisions, integration requirements, and identifies technical risks
- **Escalates to Product Lead and SRE**: raises platform-level or infrastructure-level risks that impact delivery
- **Collaborates with other TPMs**: coordinates when dependencies cross multiple initiatives

### Typical Communication
- Technical dependency maps and integration plans
- Risk escalation notes to Product Lead and SRE
- Design review summaries and decision logs
- Weekly cross-team sync updates

---

## Delivery Lead

### Role Summary
Delivery Leads drive iteration or sprint-level planning and ensure backlog readiness. They remove operational blockers, shepherd release readiness activities, and maintain focus on team commitments.

### Responsibilities
- Drive sprint/iteration planning and backlog grooming
- Ensure backlog items meet Definition of Done before sprint commitment
- Track and remove operational blockers impeding team velocity
- Shepherd release readiness activities (builds, testing, documentation)
- Report sprint status at weekly delivery syncs
- Coordinate between QA, developers, and release stakeholders

### Goals
- Maximize team velocity and predictability
- Maintain high-quality, ready-to-ship increments
- Reduce friction in the build-test-release pipeline
- Enable smooth handoffs to production

### Interactions
- **Works with PM and PdM**: aligns sprint priorities and manages scope expectations
- **Coordinates with Developers and QA**: ensures tasks are ready, removes blockers, tracks progress
- **Engages with SRE and Support Owner**: prepares for release requirements and supports early incident response
- **Reports to Project Manager**: provides sprint metrics and identifies systemic issues

### Typical Communication
- Sprint planning agendas and retrospectives
- Daily standup summaries highlighting blockers
- Release checklists and readiness reports
- Weekly delivery sync updates with metrics

---

## SRE / Platform Engineer

### Role Summary
Site Reliability Engineers and Platform Engineers own system reliability, observability, and the deployment infrastructure. They ensure production systems are stable and provide support for deploying and monitoring changes.

### Responsibilities
- Ownership of reliability, uptime, and performance of production systems
- Design and maintain observability (logging, metrics, alerting, dashboards)
- Build and maintain deployment pipelines and infrastructure-as-code
- Create and maintain runbooks for common operational tasks
- Provide production troubleshooting support and incident response
- Collaborate on deployability and operational readiness of features
- Establish SLOs and error budgets for services

### Goals
- Maintain high system reliability and performance
- Enable fast, safe deployments with minimal manual intervention
- Reduce mean time to resolution (MTTR) for incidents
- Improve observability and root cause analysis capability

### Interactions
- **Collaborates with Developers**: ensures features are deployable, reviewable, and observable; provides deployment guidance
- **Works with Delivery Lead**: participates in release checklists and smoke testing
- **Coordinates with Support Owner**: during incidents, provides triage and technical context
- **Engages with Product Lead**: communicates about capacity, performance limits, and reliability trade-offs

### Typical Communication
- Deployment runbooks and smoke test procedures
- On-call schedules and incident playbooks
- Post-incident reviews and action items
- Infrastructure change logs and architecture diagrams

---

## Support Owner (Customer Support Liaison)

### Role Summary
Support Owners triage customer-impacting issues, maintain incident handoffs, and ensure clear communication with support teams and customers. They serve as the voice of the customer and escalation point for urgent issues.

### Responsibilities
- Triage customer-reported issues and assess impact
- Own communication to support teams and escalate urgent issues
- Maintain incident handoffs between development and support
- Provide customer-facing updates during incidents and releases
- Capture customer feedback and known issues for product improvement
- Coordinate between development, QA, and support on workarounds

### Goals
- Minimize customer impact from production issues
- Reduce time to customer communication during incidents
- Improve customer satisfaction and trust
- Identify and escalate systemic issues from customer feedback

### Interactions
- **Notifies Product Manager and Project Manager**: escalates customer-impacting bugs and feature requests
- **Coordinates with Developers and SRE**: obtains technical context, workarounds, and ETAs for fixes
- **Works with QA**: validates fixes and workarounds before customer deployment
- **Engages with Release Lead**: provides known issues and customer communication plans

### Typical Communication
- Customer issue reports and severity assessments
- Incident summaries and customer communication drafts
- Known issues and workaround documentation
- Weekly customer feedback summaries for product planning

---

## UX Researcher / Designer

### Role Summary
UX Researchers and Designers validate that features meet user needs and deliver intuitive, accessible experiences. They conduct research, review acceptance criteria from a usability perspective, and provide design guidance to developers.

### Responsibilities
- Conduct user research to validate problem statements and solutions
- Review feature designs and acceptance criteria for usability
- Provide design assets, wireframes, and interaction specifications
- Ensure accessibility standards are met (WCAG, etc.)
- Validate features with users and gather feedback
- Participate in design reviews and retrospectives

### Goals
- Ensure features deliver genuine customer value
- Reduce post-launch usability issues and support burden
- Maintain consistent, accessible design patterns
- Enable data-driven design decisions

### Interactions
- **Works closely with Product Manager**: validates problem framing and success metrics through research
- **Collaborates with Developers**: provides design specifications, reviews implementations, ensures accessibility
- **Engages with QA**: contributes usability test cases and acceptance criteria
- **Participates in retrospectives**: captures user feedback and design learnings

### Typical Communication
- Research findings and personas
- Design specifications and wireframes
- Accessibility checklists and guidance
- Usability feedback and iteration notes

---

## Stakeholder Representative (Business Sponsor Rep)

### Role Summary
Stakeholder Representatives serve as the voice of business priorities and sponsors. They attend milestone reviews, approve scope changes, and ensure that the project remains aligned with business objectives and budget constraints.

### Responsibilities
- Represent business priorities and stakeholder interests
- Attend milestone reviews and provide feedback
- Approve scope changes and trade-offs
- Advocate for business value and ROI
- Escalate business-level risks and strategic issues
- Provide domain expertise and context to the delivery team

### Goals
- Ensure project delivers measurable business value
- Maintain alignment between delivery team and business strategy
- Enable fast decision-making on scope and trade-offs
- Reduce re-work due to changing business priorities

### Interactions
- **Engages with Project Manager and Product Manager**: participates in planning, scope reviews, and milestone gates
- **Provides context to delivery team**: shares domain knowledge and business constraints
- **Escalates decisions**: raises business-impacting issues to executive sponsors
- **Reviews outcomes**: validates that success metrics are achieved

### Typical Communication
- Milestone review presentations
- Scope change approvals and decisions
- Business case updates and ROI tracking
- Escalation summaries for executive stakeholders

---

## Interaction Map: How Roles Work Together

### Project Initiation
**Stakeholder Rep** → **Product Manager** → **Project Manager** → **Delivery Lead** & **Developers**
- Stakeholder Rep frames business priority
- Product Manager defines success metrics
- Project Manager creates high-level plan
- Delivery Lead and team size effort

### Planning Phase
**TPM** coordinates cross-team technical dependencies
**UX Researcher/Designer** validates problem statement
**PM/PdM** refine backlog with acceptance criteria
**Team** estimates and commits to sprint

### Execution Phase
**Developers** build features with **Delivery Lead** removing blockers
**SRE** ensures deployment infrastructure is ready
**Support Owner** prepares for customer communication
**QA** validates acceptance criteria

### Release Phase
**Delivery Lead** shepherds release readiness
**SRE** runs deployment and monitors for issues
**Support Owner** communicates with customers
**Product Manager** measures impact against success metrics

### Post-Incident
**Support Owner** escalates customer impact
**SRE** investigates and fixes
**Developers** address root cause
**Delivery Lead** and **PM** capture action items for process improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the **Interaction Map** section to understand how roles collaborate across project lifecycle phases.
- When identifying missing accountability, refer to this list to determine if additional role clarity is needed.
