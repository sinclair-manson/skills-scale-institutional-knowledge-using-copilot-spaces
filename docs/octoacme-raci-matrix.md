# OctoAcme — RACI Matrix Template

## Purpose
Use this RACI matrix to clarify ownership and accountability for key decisions and activities in an OctoAcme project. A completed RACI reduces confusion, prevents duplicated effort, and ensures no activity falls through the cracks.

## How to Use
1. Copy this template into your project documentation folder.
2. Review the default assignments and adjust them to match your project team.
3. Share with all roles at project kickoff and revisit at each phase transition.

## RACI Definitions
| Letter | Role | Description |
|--------|------|-------------|
| **R** | Responsible | Does the work. There should be at least one R per activity. |
| **A** | Accountable | Owns the outcome. Signs off on the work. Only one A per activity. |
| **C** | Consulted | Provides input before or during the activity. Two-way communication. |
| **I** | Informed | Kept up to date on progress or outcomes. One-way communication. |

---

## RACI Matrix

### Project Initiation

| Activity | Project Manager | Product Manager | Business Analyst | Developers | UX Designer | QA Lead | Release Manager | Stakeholders |
|----------|----------------|----------------|-----------------|------------|-------------|---------|----------------|--------------|
| Define problem statement | A | R | C | I | I | I | I | C |
| Identify stakeholders | R | C | C | I | I | I | I | I |
| Establish project charter | A | C | R | I | I | I | I | R |
| Confirm project sponsorship | I | I | I | I | I | I | I | A |

### Planning

| Activity | Project Manager | Product Manager | Business Analyst | Developers | UX Designer | QA Lead | Release Manager | Stakeholders |
|----------|----------------|----------------|-----------------|------------|-------------|---------|----------------|--------------|
| Define scope and milestones | A | C | R | C | C | C | C | I |
| Prioritize backlog | C | A | C | C | I | I | I | I |
| Gather and document requirements | C | C | A | C | C | I | I | R |
| Create test strategy | C | I | C | C | I | A | I | I |
| Create UX design plan | I | C | I | C | A | I | I | I |
| Plan release schedule | C | C | I | I | I | C | A | I |
| Identify risks and mitigations | A | C | C | C | C | C | C | I |

### Execution

| Activity | Project Manager | Product Manager | Business Analyst | Developers | UX Designer | QA Lead | Release Manager | Stakeholders |
|----------|----------------|----------------|-----------------|------------|-------------|---------|----------------|--------------|
| Implement features | I | I | I | A | C | C | I | I |
| Conduct design reviews | I | C | I | C | A | I | I | I |
| Write and run tests | I | I | I | R | I | A | I | I |
| Triage defects | C | I | I | R | C | A | I | I |
| Manage blockers and escalations | A | C | I | R | R | R | R | I |
| Update risk register | A | C | C | C | C | C | C | I |
| Conduct sprint demos | C | A | I | R | R | R | I | I |

### Release

| Activity | Project Manager | Product Manager | Business Analyst | Developers | UX Designer | QA Lead | Release Manager | Stakeholders |
|----------|----------------|----------------|-----------------|------------|-------------|---------|----------------|--------------|
| Validate release readiness | C | C | I | C | C | R | A | I |
| Schedule deployment window | C | I | I | I | I | I | A | I |
| Deploy to staging and production | I | I | I | R | I | C | A | I |
| Draft and distribute release notes | I | C | I | I | I | I | A | I |
| Post-deploy verification | I | I | I | R | I | R | A | I |
| Communicate release to stakeholders | C | C | I | I | I | I | A | I |

### Close & Retrospective

| Activity | Project Manager | Product Manager | Business Analyst | Developers | UX Designer | QA Lead | Release Manager | Stakeholders |
|----------|----------------|----------------|-----------------|------------|-------------|---------|----------------|--------------|
| Conduct retrospective | A | C | I | R | R | R | R | I |
| Capture lessons learned | A | C | C | C | C | C | C | I |
| Archive project artifacts | A | I | C | I | I | I | I | I |
| Confirm project closure | A | R | I | I | I | I | I | R |

---

## Notes
- Update this matrix at the start of each major project phase.
- If multiple people share an **R**, clarify individual tasks to prevent ambiguity.
- Only one person should be **A** (Accountable) per activity. If you find multiple, resolve ownership before the project begins.
