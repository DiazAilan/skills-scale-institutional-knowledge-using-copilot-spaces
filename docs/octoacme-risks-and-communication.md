# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- **Identify**: during planning and ongoing execution (all roles contribute)
  - Business Analyst identifies requirement and scope risks
  - Design Lead flags UX research gaps and design dependencies
  - QA Lead highlights testing coverage and quality risks
  - DevOps Engineer identifies infrastructure, security, and deployment risks
  - Support Lead surfaces customer impact and communication risks
- **Assess**: estimate impact and likelihood (PM coordinates with role owners)
- **Mitigate**: reduced via actions, contingency plans (assigned owners by area)
- **Monitor**: review at weekly syncs and update status (PM tracks, all roles report)

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support, customers)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status
- **Customer-facing communication** coordinated by Support Lead
- **Design feedback loops** with stakeholders facilitated by Design Lead
- **Infrastructure status updates** provided by DevOps Engineer
- **Quality metrics and test results** shared by QA Lead

## Communication Templates

### Weekly Status Template
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

### Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

### Customer Release Communication (Support Lead)
- What's new in this release
- Benefits to users
- Any required actions or migrations
- Where to get help
- Known issues (if applicable)

### Design Review Communication (Design Lead)
- UX goals for the feature
- Key design decisions and rationale
- Usability testing results
- Accessibility considerations
- Feedback requested

### QA Status Report (QA Lead)
- Test execution progress
- Pass/fail rates
- Critical and high-priority bugs
- Quality gate status
- Release readiness recommendation

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call
