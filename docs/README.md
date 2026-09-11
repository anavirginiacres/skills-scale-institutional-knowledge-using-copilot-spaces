# OctoAcme Project Management Documentation

## Welcome

This documentation suite contains all the processes, workflows, and guidance used by OctoAcme to run projects successfully. Whether you're starting a new initiative, planning a release, or leading a retrospective, you'll find the process guidance you need here.

## OctoAcme Project Management Overview

OctoAcme follows a structured, lifecycle-based approach to project delivery that emphasizes customer-first principles, iterative development, and clear ownership. The organization runs projects through five distinct phases:

1. **Initiation** — Validate business need and stakeholder alignment
2. **Planning** — Break work into shippable increments with acceptance criteria
3. **Execution** — Day-to-day delivery with daily standups and demos
4. **Release** — Standardized deployment with rollback plans
5. **Close & Retrospective** — Capture learnings for continuous improvement

This phased approach is supported by key artifacts including a Project One-pager for alignment, a prioritized backlog with acceptance criteria, a risk register, and sprint backlogs that guide teams through each stage.

### Core Principles

- **Customer-first**: Prioritize customer value and usability in every decision
- **Iterative delivery**: Deliver small, testable increments and gather feedback early
- **Clear ownership**: Every project has named owners with clear accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

### Execution & Quality

OctoAcme emphasizes quality, transparency, and continuous learning through multiple mechanisms:

- **Work Management**: Teams manage work using GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done)
- **Code Quality**: Small pull requests (≤400 lines), automated testing and linting in CI, and mandatory approval before merging
- **Testing Strategy**: Unit tests, integration tests, end-to-end smoke tests, security scanning, and manual QA for critical features
- **Risk Management**: Active risk tracking using a risk register with likelihood, impact, and mitigation strategies
- **Escalation Paths**: Clear escalation from team level → PM → Product Lead → Sponsor
- **Continuous Improvement**: Retrospectives held after sprints, releases, or milestones to drive iterative enhancements

### Core Roles

OctoAcme projects involve collaboration across key roles:

- **Project Managers** — Coordinate delivery, manage schedules, risks, and communications
- **Product Managers** — Define what should be built, prioritize the backlog, and measure outcomes
- **Developers** — Implement features, write tests, and participate in design reviews
- **QA/Testing** — Validate quality and acceptance criteria
- **Stakeholders** — Provide inputs and approvals

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed responsibilities and communication patterns for each role.

### Communication Cadence

- **Weekly sync** between PM + Product Manager
- **Twice-weekly standups** for delivery teams (or as agreed)
- **Monthly stakeholder updates**
- **Ad-hoc escalations** as needed

## Process Documentation

### Getting Started

- **[Project Management Overview](octoacme-project-management-overview.md)** — Concise introduction to OctoAcme's approach, roles, and key artifacts
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Detailed descriptions of each role and their responsibilities

### Project Lifecycle

1. **[Project Initiation](octoacme-project-initiation.md)** — Validate business need, align stakeholders, create lightweight initial plan
2. **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify dependencies and risks
3. **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day work, track progress toward milestones
4. **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize releases to production with reduced risk
5. **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert to actionable improvements

### Cross-Cutting Concerns

- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks; stakeholder communication templates

## Quick Links

- **Need to start a new project?** Begin with [Project Initiation](octoacme-project-initiation.md)
- **Running a sprint?** Check [Execution & Tracking](octoacme-execution-and-tracking.md)
- **Preparing a release?** See [Release & Deployment](octoacme-release-and-deployment.md)
- **Managing risks?** Refer to [Risk Management & Communication](octoacme-risks-and-communication.md)
- **Reflecting on a milestone?** Use [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## For New Team Members

1. Start with this README to understand OctoAcme's philosophy and structure
2. Read [Project Management Overview](octoacme-project-management-overview.md) for a concise introduction
3. Review [Roles & Personas](octoacme-roles-and-personas.md) to understand your role and how it fits in the organization
4. Explore the lifecycle docs relevant to your current project phase

## Providing Feedback

If you have suggestions for improving these processes, create a new issue using the "[Process Doc Update]" template. Your feedback helps us continuously improve how we run projects.
