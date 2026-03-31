# OctoAcme — Role Interaction Matrix

## Purpose
Provide a quick-reference RACI-style overview of how each OctoAcme role interacts across key project activities. This helps teams clarify ownership, reduce confusion, and ensure the right people are involved at each stage.

## RACI Key
| Code | Meaning |
|------|---------|
| **R** | Responsible — does the work |
| **A** | Accountable — owns the outcome |
| **C** | Consulted — provides input before/during |
| **I** | Informed — kept up-to-date on decisions/results |

---

## Role Interaction Matrix

| Activity | Developer | Product Manager | Project Manager | Scrum Master | UX/UI Designer | Data Analyst | Release Manager | Customer Support Lead |
|----------|-----------|-----------------|-----------------|--------------|----------------|--------------|-----------------|----------------------|
| Define project goals & success metrics | C | A/R | C | I | C | C | I | I |
| Backlog refinement & prioritization | C | A/R | C | R | C | C | I | C |
| Sprint planning | R | C | I | A/R | C | I | I | I |
| UX research & design | C | C | I | I | A/R | C | I | I |
| Feature implementation | A/R | I | I | C | C | I | I | I |
| Code review & quality | A/R | I | I | C | I | I | I | I |
| Data instrumentation & telemetry | R | C | I | I | I | A/C | I | I |
| Metrics analysis & reporting | I | C | C | I | I | A/R | I | I |
| Risk identification & mitigation | C | C | A/R | C | I | I | C | C |
| Release readiness & go/no-go | C | C | C | I | I | I | A/R | C |
| Deployment execution | R | I | I | I | I | I | A/R | I |
| Post-deploy verification | R | I | C | I | I | C | A/R | I |
| Post-launch support triage | C | C | I | I | I | I | I | A/R |
| Stakeholder communication | I | C | A/R | I | I | C | C | C |
| Retrospective facilitation | R | C | C | A/R | C | C | C | C |
| Process improvement tracking | C | I | C | A/R | I | I | I | I |

---

## Notes
- Where a cell shows two codes (e.g., **A/R**), the same role is both Accountable and Responsible.
- Activities may involve more or fewer roles depending on project size and team structure — adapt as needed.
- For detailed role descriptions, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).
- For release and support handoff steps, see [octoacme-role-handoff-checklist.md](./octoacme-role-handoff-checklist.md).
