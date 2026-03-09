# Extended Playbook — Operations & Execution

## Table of Contents
1. [Tools & Technology Stack](#tools--technology-stack)
2. [Case Studies & Reference Models](#case-studies--reference-models)
3. [Advanced Frameworks](#advanced-frameworks)
4. [Templates](#templates)
5. [Recommended Reading & Sources](#recommended-reading--sources)

---

## Tools & Technology Stack

### By Capability

| Capability | Recommended | Budget Alternative |
|---|---|---|
| Process Mapping | Lucidchart, Miro, Visio | Draw.io (free), Mermaid diagrams |
| Project Management | Linear, Jira, Asana | GitHub Projects, Notion |
| Procurement | Zapro, ProcureDesk, Precoro | Notion tracker + contract templates |
| Quality/Testing | Datadog, PagerDuty, Sentry, SonarQube | Grafana (free), Uptime Kuma |
| Inventory/Assets | Snipe-IT, Asset Panda | Notion/Airtable registry |
| Vendor Management | Vendr, Zluri, Productiv | Spreadsheet + calendar reminders |
| Documentation | Notion, Confluence, GitBook | Notion + SKILL.md architecture |
| Analytics/BI | Metabase, Looker, Grafana | Metabase (open-source), Redash |
| Monitoring | Datadog, New Relic, Grafana Cloud | Grafana + Prometheus (free) |
| FinOps | Vantage, Infracost, CloudHealth | AWS Cost Explorer + manual review |

### AI-Augmented Operations

- **Process mining:** Use AI to analyse event logs and discover actual process flows vs documented
- **Anomaly detection:** ML models on operational metrics to flag deviations before they become incidents
- **Automated reconciliation:** AI-assisted matching for payment reconciliation, invoice matching
- **Incident classification:** NLP to auto-categorise and route support tickets/incidents
- **Predictive maintenance:** ML on infrastructure metrics to predict failures before impact
- **Document generation:** AI-assisted SOP writing, runbook creation, incident report drafting

---

## Case Studies & Reference Models

### Amazon: Operational Excellence as Strategy
Amazon's model proves process excellence IS the strategy. Systematic optimisation
enables industry-leading fulfilment. Their "Working Backwards" approach embeds
customer-back thinking into every operational decision. By 2025, AWS reached 32%
global cloud market share through operational discipline applied to infrastructure.

**Lesson:** Don't separate operations from strategy. The best operations ARE strategy.

### Toyota Production System: The Gold Standard
Just-In-Time, Jidoka (automation with human touch), and Kaizen created a system where
quality is built in, waste is eliminated continuously, and every worker can stop the
line. Competitors copy tools but fail to adopt the culture.

**Lesson:** Tools without culture produce theatre, not improvement. Respect for people
enables everything else.

### Danaher Business System
Drives consistent operational excellence across diverse portfolio. Integrates lean,
performance management, and CI into a repeatable playbook applied to every acquisition.

**Lesson:** Operational excellence CAN be codified and deployed systematically across
multiple entities — powerful for multi-company portfolios.

### GE: Six Sigma at Scale ($12B in Savings)
Systematic Six Sigma generated $12B savings over 15 years. Required executive sponsorship,
investment in training (belt certification), and rigorous project selection.

**Lesson:** Without executive sponsorship and disciplined project selection, Six Sigma
becomes bureaucratic overhead, not a value driver.

### Stripe: Developer-First Operational Design
API-first, documentation-obsessed approach treats developer onboarding time as core
metric. Every API change undergoes rigorous backward-compatibility testing.

**Lesson:** In tech, operational excellence and product excellence are the same thing.
The developer/user experience IS the operation.

### Pixar: Quality Through Iteration
Applied continuous improvement to creative output using structured review cycles
("Braintrust") where candid feedback drives improvement. Reduced risk of expensive
movie failures while maintaining creative ambition.

**Lesson:** Quality frameworks apply to creative/knowledge work, not just manufacturing.
Psychological safety in feedback is the enabler.

---

## Advanced Frameworks

### Value Stream Mapping (VSM) — Step by Step

1. **Define scope:** Select the process/value stream to map (e.g., "customer onboarding")
2. **Walk the process:** Follow a single unit of work from start to finish
3. **Draw current state:** Map each step with cycle time, wait time, %C&A (complete & accurate)
4. **Calculate metrics:** Total lead time = sum of cycle times + wait times. Process efficiency = value-add time / total lead time
5. **Identify waste:** Mark steps that don't add customer value (waiting, handoffs, rework, approvals)
6. **Design future state:** Remove waste, combine steps, automate, reduce handoffs
7. **Create implementation plan:** Prioritised actions to close the gap

Target process efficiency: >25% for knowledge work (most start at 5-15%).

### Operational Maturity Model

| Level | Name | Characteristics |
|---|---|---|
| 1 | Ad Hoc | No documented processes. Success depends on heroics. |
| 2 | Defined | Core processes documented. Consistency improving. |
| 3 | Managed | Processes measured with KPIs. Data-driven decisions. |
| 4 | Optimised | Continuous improvement culture. Statistical process control. |
| 5 | Innovating | Predictive analytics. Self-optimising systems. Industry-leading. |

Most startups operate at Level 1-2. Target Level 3 by end of Year 1, Level 4 by Year 2.

### FinOps Framework (Cloud Cost Management)

| Phase | Activities |
|---|---|
| Inform | Tag all resources. Allocate costs to teams/products. Visibility dashboards. |
| Optimise | Right-size instances. Reserved capacity. Spot instances. Eliminate waste. |
| Operate | Set budgets/alerts. Anomaly detection. Regular cost reviews. Showback/chargeback. |

Target: Cloud spend efficiency ratio >70% (utilised resources / total provisioned).

### Incident Management Framework

| Severity | Definition | Response Time | Communication |
|---|---|---|---|
| SEV-1 (Critical) | Service down, data loss, security breach | < 15 min | All-hands, customer notification |
| SEV-2 (Major) | Degraded service, significant impact | < 1 hour | On-call + engineering lead |
| SEV-3 (Minor) | Limited impact, workaround available | < 4 hours | On-call team |
| SEV-4 (Low) | Cosmetic, no immediate impact | Next business day | Backlog |

Post-incident: Blameless retrospective within 48 hours. RCA document. Prevention actions tracked.

### Vendor Risk Matrix

| | Low Business Impact | High Business Impact |
|---|---|---|
| **Low Switching Cost** | Transactional — manage on cost | Preferred — invest in relationship |
| **High Switching Cost** | Locked-in — plan exit strategy | Strategic — deep partnership |

Review quarterly. No vendor should remain in "locked-in" quadrant without an active mitigation plan.

---

## Templates

### Standard Operating Procedure (SOP) Template

```markdown
# SOP: [Process Name]

## Metadata
- Version: X.X | Effective: YYYY-MM-DD | Owner: [Name]
- Review cycle: [Quarterly/Annual] | Next review: YYYY-MM-DD
- Jurisdiction: [All / UK / EE / ZM]

## Purpose
Why this process exists and what outcome it delivers.

## Scope
What this SOP covers and explicitly what it does NOT cover.

## Prerequisites
What must be in place before starting (access, approvals, tools).

## Procedure
1. Step 1 — [Clear action with expected outcome]
2. Step 2 — [Clear action with expected outcome]
   - If [condition]: [alternative path]
3. Step 3 — [Clear action]

## Quality Checks
- [ ] [Verification point 1]
- [ ] [Verification point 2]

## Exceptions & Escalation
- If [exception]: escalate to [role] via [channel]

## Related Documents
- [Link to related SOP/policy/runbook]
```

### Project Charter Template

```markdown
# Project Charter: [Project Name]

## Problem Statement
What problem are we solving? For whom? What's the impact of not solving it?

## Objectives
1. [Specific, measurable objective]
2. [Specific, measurable objective]

## Scope
### In Scope: [What's included]
### Out of Scope: [What's explicitly excluded]

## Success Criteria
- [Measurable criterion 1]
- [Measurable criterion 2]

## Key Stakeholders
| Name | Role | RACI |
|---|---|---|
| [Name] | [Role] | A |

## Timeline
| Milestone | Target Date |
|---|---|
| Kick-off | YYYY-MM-DD |
| [Phase 1 complete] | YYYY-MM-DD |
| Go-live | YYYY-MM-DD |

## Risks & Mitigations
| Risk | Impact | Likelihood | Mitigation |
|---|---|---|---|
| [Risk] | High/Med/Low | High/Med/Low | [Action] |

## Budget
- Estimated cost: £[X]
- Approved by: [Name]
```

### Vendor Evaluation Scorecard

```markdown
# Vendor Evaluation: [Vendor Name] for [Requirement]

## Scoring (1-5 per criterion, weighted)

| Criterion | Weight | Score | Weighted |
|---|---|---|---|
| Capability | 25% | /5 | |
| Reliability | 20% | /5 | |
| Cost (TCO) | 20% | /5 | |
| Compliance | 15% | /5 | |
| Strategic Fit | 10% | /5 | |
| Support | 10% | /5 | |
| **Total** | **100%** | | **/5.0** |

## Compliance Checklist
- [ ] GDPR/DPA compliant
- [ ] PCI-DSS (if payment data)
- [ ] Data residency requirements met
- [ ] Audit rights in contract
- [ ] Sub-processor list reviewed

## Commercial Summary
- Pricing model: [Per-seat/Usage/Flat]
- Annual cost: £[X]
- Contract term: [X months]
- Exit provisions: [Summary]

## Recommendation
[Proceed / Shortlist / Reject] — [Rationale]
```

### Incident Retrospective Template

```markdown
# Incident Retrospective: [INC-XXXX]

## Summary
- Severity: SEV-[X] | Duration: [X hours/minutes]
- Impact: [Who/what was affected]
- Detection: [How we found out]

## Timeline
| Time (UTC) | Event |
|---|---|
| HH:MM | [First alert/report] |
| HH:MM | [Action taken] |
| HH:MM | [Resolution] |

## Root Cause
[What actually caused the incident — use 5 Whys]

## What Went Well
- [What worked in our response]

## What Didn't Go Well
- [Where we stumbled]

## Action Items
| Action | Owner | Due | Status |
|---|---|---|---|
| [Prevention action] | [Name] | YYYY-MM-DD | Open |

## Lessons Learned
[Key takeaway for the team/organisation]
```

---

## Recommended Reading & Sources

### Books
- **The Goal** — Eliyahu Goldratt (Theory of Constraints, essential)
- **The Phoenix Project** — Kim, Behr, Spafford (DevOps/IT operations as narrative)
- **The Toyota Way** — Jeffrey Liker (14 principles of operational excellence)
- **Lean Thinking** — Womack & Jones (value stream, flow, pull, perfection)
- **Out of the Crisis** — W. Edwards Deming (quality management foundations)
- **The Lean Startup** — Eric Ries (MVP, validated learning, build-measure-learn)
- **Accelerate** — Forsgren, Humble, Kim (DORA metrics, software delivery)
- **Turn the Ship Around!** — L. David Marquet (leader-leader, not leader-follower)
- **High Output Management** — Andy Grove (leverage, indicators, meetings as ops)
- **The Checklist Manifesto** — Atul Gawande (checklists for complex operations)

### Frameworks & Standards
- APQC Process Classification Framework — standard process taxonomy
- ITIL 4 — IT service management best practices
- ISO 9001 — Quality management systems
- ISO 27001 — Information security management
- PCI-DSS — Payment card industry data security
- DORA Metrics — Software delivery performance measurement
- SAFe — Scaled Agile Framework for enterprise agility
- COBIT — Governance of enterprise IT

### Research
- McKinsey — Organisations with systematic process optimisation outperform peers by 47%
- Deloitte 2024 Global Operations Study — 84% executives identify process optimisation as critical
- Eastgate Software 2025 — Process optimisation cuts costs by 30%, cycle times by 40%
- Forbes Insights — 81% C-Level executives rate agility as most important characteristic
- PEX Network 2025 — AI is biggest investment area for operational excellence
- Goldratt (2004) — Theory of Constraints and the integrated TLS framework

---

**This reference document supports the main SKILL.md. Return to the main skill for
quick-reference frameworks and decision-making guidance.**
