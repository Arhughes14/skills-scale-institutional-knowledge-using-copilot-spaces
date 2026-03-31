# OctoAcme — Role Handoff Checklist

## Purpose
Ensure smooth handoffs between roles at key transition points in the project lifecycle — particularly at release time and when transitioning to production support. Use this checklist to verify that all parties are aligned and informed before moving forward.

---

## Release Readiness Handoff (Engineering → Release Manager)

Completed by: **Development team lead / Project Manager**  
Verified by: **Release Manager**

### Code & CI
- [ ] All planned features and fixes are merged to the release branch
- [ ] CI pipeline is green (tests, linting, security scans)
- [ ] No open critical or high-severity bugs targeting this release
- [ ] Feature flags configured for staged rollout (if applicable)

### Documentation & Communication
- [ ] Release notes drafted and reviewed by Product Manager
- [ ] CHANGELOG updated
- [ ] API or schema migration steps documented (if any)
- [ ] Internal announcement drafted (Slack, email, etc.)

### Deployment & Rollback
- [ ] Deployment window confirmed with stakeholders
- [ ] Rollback plan documented and reviewed
- [ ] Smoke test scripts prepared and verified in staging
- [ ] On-call schedule confirmed for the deployment window

---

## Post-Deploy Handoff (Release Manager → Customer Support Lead)

Completed by: **Release Manager**  
Verified by: **Customer Support Lead**

### Support Readiness
- [ ] Release notes shared with Customer Support team
- [ ] Known issues and workarounds documented
- [ ] FAQs or knowledge base articles updated (if needed)
- [ ] Support runbooks updated for any changed workflows
- [ ] Support team briefed on new features or behavior changes

### Monitoring & Escalation
- [ ] Post-deploy dashboards and alerts confirmed active
- [ ] Escalation path to on-call engineering defined
- [ ] SLA/SLO thresholds reviewed for new features
- [ ] Customer Support Lead added to incident notification channels

---

## Sprint Handoff (Scrum Master → Project Manager — end of sprint)

Completed by: **Scrum Master**  
Verified by: **Project Manager**

- [ ] Sprint velocity and burndown captured
- [ ] Carried-over items re-estimated and moved to next sprint backlog
- [ ] Retrospective action items documented and assigned
- [ ] Updated risk register shared with Project Manager
- [ ] Blockers and dependencies communicated to relevant stakeholders

---

## Design Handoff (UX/UI Designer → Developers)

Completed by: **UX/UI Designer**  
Verified by: **Developer lead**

- [ ] Final design specs published and linked in the relevant issue/PR
- [ ] Interactive prototype or annotated mockups shared
- [ ] Edge cases and error states documented
- [ ] Accessibility requirements (WCAG level) noted
- [ ] Design review session scheduled with implementation team

---

## References
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) — Full role descriptions and responsibilities
- [octoacme-role-interaction-matrix.md](./octoacme-role-interaction-matrix.md) — RACI-style overview of role interactions
- [octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md) — Full release and deployment guide
