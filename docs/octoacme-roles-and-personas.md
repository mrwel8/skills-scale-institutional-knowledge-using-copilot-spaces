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

### Who Owns It?
Development team lead or Engineering Manager

### Typical Handoffs
- To QA: completed features for testing
- To Release Manager: merged code ready for deployment
- To Support: documentation and known limitations

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

### Who Owns It?
VP of Product or Chief Product Officer

### Typical Handoffs
- To Developers: prioritized backlog and acceptance criteria
- To UX Researcher: research goals and hypotheses
- To Data Analyst: success metrics and KPI definitions
- To Project Manager: timeline and priority signals

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

### Who Owns It?
Program Manager or VP of Delivery

### Typical Handoffs
- To Stakeholders: status updates and risk reports
- To Developers: sprint plans and priority guidance
- To Release Manager: readiness assessments and deployment scheduling
- To Product Manager: capacity and timeline constraints

---

## UX Researcher

### Role Summary
UX Researchers plan and conduct user research to surface pain points, validate assumptions, and deliver insights that inform product decisions and design. They translate customer needs into actionable recommendations.

### Responsibilities
- Plan and execute user research activities (interviews, surveys, usability testing, journey mapping)
- Surface user pain points and unmet needs
- Validate product assumptions through research
- Deliver research artifacts (interview notes, journey maps, personas, insights summaries)
- Advocate for user perspective in product and design decisions

### Goals
- Ensure product decisions are grounded in user needs
- Reduce risk by validating assumptions early
- Accelerate product-market fit through continuous user feedback
- Build shared understanding across cross-functional teams

### Typical Communication
- Research kickoff meetings with Product Manager and Product Designer
- Research readouts and insight synthesis with stakeholders
- Collaboration on acceptance criteria informed by user needs
- Design review participation

### Who Owns It?
Head of User Research or Head of Product Design

### Typical Handoffs
- To Product Manager: validated insights and prioritization recommendations
- To Product Designer: research findings and usability implications
- To Developers: usability considerations and accessibility requirements
- To QA: user acceptance test scenarios based on research

---

## Release Manager

### Role Summary
Release Managers coordinate release schedules, manage deployment runbooks, define rollback strategies, and ensure smooth transitions from development to production. They bridge engineering and operations to enable reliable, predictable releases.

### Responsibilities
- Coordinate release schedules and deployment windows
- Create and maintain release runbooks and deployment playbooks
- Define and test rollback plans and mitigation strategies
- Obtain necessary approvals and sign-offs before deployment
- Run post-deployment verifications and health checks
- Communicate release status to stakeholders and support teams

### Goals
- Ensure reliable, zero-downtime (or minimal-downtime) deployments
- Reduce mean time to recovery (MTTR) in case of issues
- Maintain audit trails and compliance documentation
- Enable rapid iteration through streamlined release processes

### Typical Communication
- Release planning meetings with Engineering and Product
- Deployment readiness reviews
- Stakeholder release announcements and schedule coordination
- Incident response and rollback communications

### Who Owns It?
VP of Engineering or Release Engineering Lead

### Typical Handoffs
- From Developers: merged and tested code ready for release
- To Operations: deployment runbooks and infrastructure requirements
- To Support: release notes and known issues
- To Stakeholders: release schedule and communications

---

## Implementation / Solutions Engineer

### Role Summary
Implementation / Solutions Engineers own customer-specific integrations, deployment configurations, and go-live activities. They translate customer requirements into technical solutions and ensure successful onboarding and adoption.

### Responsibilities
- Design and build customer-specific integrations and configurations
- Create implementation guides and runbooks for customer deployments
- Support pilot programs and phased rollouts
- Manage customer onboarding and training
- Troubleshoot integration issues and provide solutions
- Gather customer feedback on product capabilities and limitations

### Goals
- Accelerate time to value for customers
- Reduce customer implementation effort and risk
- Build strong customer relationships and trust
- Identify product gaps and improvement opportunities through customer interactions

### Typical Communication
- Direct customer communication and status updates
- Implementation planning and scope definition with customers
- Technical architecture discussions with Developers
- Handoff to Support for post-implementation support

### Who Owns It?
VP of Solutions or Head of Professional Services

### Typical Handoffs
- From Developers: product capabilities and technical APIs
- To Customers: go-live readiness and post-launch support plans
- To Support: customer-specific configurations and known workarounds
- To Product Manager: feature requests and integration feedback

---

## Support & Documentation Lead

### Role Summary
Support & Documentation Leads maintain user-facing documentation, triage support patterns, create knowledge base articles, and own first-line incident communication. They are the voice and interface between product and customers.

### Responsibilities
- Create and maintain comprehensive user documentation and guides
- Triage and prioritize customer support requests and issues
- Build and maintain a searchable knowledge base (FAQ, troubleshooting guides)
- Identify recurring support issues and escalate to product teams
- Own first-line incident communication and customer status updates
- Train support teams on product features and common customer issues

### Goals
- Reduce support volume through self-service documentation
- Improve customer satisfaction and resolution times
- Surface product issues and friction points to engineering and product
- Ensure consistent, professional customer communication

### Typical Communication
- Customer support channels (email, chat, help desk)
- Documentation reviews with Product and Developers
- Support pattern analysis and retrospectives
- Release note and known-issue coordination with Release Manager

### Who Owns It?
VP of Customer Success or Head of Support

### Typical Handoffs
- From Developers: technical documentation and API specifications
- From Release Manager: release notes and known issues
- To Support Team: training and escalation procedures
- To Product Manager: top support issues and customer feedback

---

## Data Analyst

### Role Summary
Data Analysts define, build, and maintain success metrics; create dashboards for monitoring; validate experiment results; and provide data-driven recommendations to inform product decisions.

### Responsibilities
- Define and implement success metrics aligned with business goals
- Build dashboards and reports for real-time monitoring of key signals
- Validate experiment results and provide statistical analysis
- Identify trends, anomalies, and opportunities in product data
- Provide data-driven recommendations to Product and Engineering
- Ensure data quality and correct telemetry implementation

### Goals
- Enable data-driven decision making across the organization
- Accelerate learning from product usage and experiments
- Identify optimization opportunities and areas for improvement
- Build trust in metrics and analytics across teams

### Typical Communication
- Metrics definition workshops with Product Manager
- Dashboard reviews and ad-hoc analysis requests from Product and Developers
- Data validation discussions with QA teams
- Results presentations and insights summaries for stakeholders

### Who Owns It?
Head of Analytics or Chief Data Officer

### Typical Handoffs
- From Developers: telemetry implementation and data validation
- To Product Manager: metrics dashboards and insights on product performance
- To Project Manager: velocity and delivery metrics
- To QA: data quality validation procedures

---

## Security / Compliance Owner

### Role Summary
Security / Compliance Owners identify security and compliance requirements, conduct security reviews, manage vulnerability remediation, and ensure the product meets regulatory and organizational standards.

### Responsibilities
- Identify applicable compliance requirements (SOC 2, GDPR, HIPAA, etc.)
- Conduct security design reviews and threat modeling
- Run security testing and vulnerability scanning
- Manage remediation tracking for security findings
- Coordinate with external auditors and compliance assessments
- Trigger incident response procedures for security incidents

### Goals
- Ensure product meets security and compliance standards
- Reduce risk of data breaches and compliance violations
- Maintain customer trust and market credibility
- Enable regulatory compliance and audit success

### Typical Communication
- Security design review discussions with Developers and Product
- Vulnerability and remediation status updates
- Compliance and audit communications with stakeholders
- Incident response escalations and post-incident reviews

### Who Owns It?
Chief Security Officer or VP of Security

### Typical Handoffs
- From Developers: security design decisions and threat models
- To Release Manager: security sign-off before production deployment
- To Support: security incident procedures and escalation paths
- To Project Manager: security risks and mitigation timelines

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the "Who Owns It?" and "Typical Handoffs" sections to clarify accountability and communication flow across roles.
