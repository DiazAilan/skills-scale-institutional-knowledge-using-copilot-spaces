# OctoAcme Project Management Overview

## Purpose
Provide a concise, shareable introduction to how OctoAcme runs projects so new teammates can quickly understand our approach, roles, and key artifacts.

## Scope
Applies to all cross-functional projects that deliver product features, services, or integrations.

## Principles
- Customer-first: prioritize customer value and usability.
- Iterative delivery: deliver small, testable increments.
- Clear ownership: each project has a named Project Manager (PM) and Product Lead.
- Data-informed decisions: measure impact and iterate based on evidence.
- Psychological safety: encourage feedback and learning.

## Core Roles
- **Project Manager (PM)**: coordinates delivery, schedules, risk, communications.
- **Product Manager (PdM)**: defines outcomes, prioritizes backlog, and measures success.
- **Developers**: implement features, collaborate on design and testability.
- **Design Lead / UX Designer**: owns user experience design, creates wireframes and prototypes, conducts usability testing.
- **QA Lead**: defines test strategy, validates quality and acceptance criteria, manages bug tracking.
- **DevOps / Infrastructure Engineer**: manages CI/CD pipelines, deployments, monitoring, and infrastructure.
- **Business Analyst**: gathers and documents requirements, analyzes data, bridges business and technical teams.
- **Support Lead / Customer Success**: communicates with customers, triages feedback, represents customer voice.
- **Stakeholders**: provide inputs and approvals.

## Key Artifacts
- **Project Charter / One-pager**: problem statement, objectives, success metrics
- **Roadmap and Release Plan**: milestones, timelines, dependencies
- **Sprint/Iteration Backlog**: prioritized work items with acceptance criteria
- **Design Artifacts**: wireframes, mockups, prototypes, design specifications
- **Test Plans & QA Sign-off**: test strategy, test cases, quality gates
- **Acceptance Criteria & Definition of Done**: feature requirements and completion standards
- **Infrastructure & Deployment Plans**: CI/CD configuration, deployment runbooks
- **Risk Register**: identified risks, mitigations, owners
- **Customer Communication Plan**: release notes, user notifications, support documentation
- **Retrospective notes and action items**: learnings and continuous improvement actions

## Lifecycle (high-level)
1. **Initiation**: problem statement, stakeholders, high-level timeline. Business Analyst helps gather requirements.
2. **Planning**: scope, resources, milestones, dependencies. Design Lead creates UX plans, QA Lead drafts test strategy, DevOps plans infrastructure needs.
3. **Execution**: build, test, review, iterate. Developers implement, QA validates, Design reviews UI/UX implementation.
4. **Release**: deploy, verify, announce. DevOps manages deployment, QA provides sign-off, Support Lead coordinates customer communications.
5. **Close & Retrospective**: capture learnings and next steps. All roles contribute insights for continuous improvement.

## Communication Cadence
- Weekly sync between PM + PdM
- Twice-weekly standups for delivery team (or as agreed)
- Monthly stakeholder updates
- Ad-hoc escalations as needed

## How to use these docs
- Keep the Project Charter updated in the project repo.
- Add process-specific docs into `.copilot/` if you want Copilot Spaces to use them as context.
