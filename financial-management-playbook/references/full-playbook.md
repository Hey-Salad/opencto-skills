# Financial Management Full Playbook — Detailed Reference

## Table of Contents
1. [Cash Flow Deep Dive](#1-cash-flow-deep-dive)
2. [Budgeting & Forecasting Advanced](#2-budgeting--forecasting-advanced)
3. [Financial Reporting Templates & Board Packs](#3-financial-reporting--board-packs)
4. [Capital Allocation & Fundraising Mechanics](#4-capital-allocation--fundraising-mechanics)
5. [Cost Optimisation Detailed Strategies](#5-cost-optimisation-detailed-strategies)
6. [Tax Planning by Jurisdiction](#6-tax-planning-by-jurisdiction)
7. [Revenue & Pricing Deep Dive](#7-revenue--pricing-deep-dive)
8. [Financial Risk Management Framework](#8-financial-risk-management-framework)
9. [Financial Technology Stack](#9-financial-technology-stack)
10. [KPI Reference Library](#10-kpi-reference-library)

---

## 1. Cash Flow Deep Dive

### Cash Conversion Cycle (CCC)
```
CCC = Days Sales Outstanding (DSO) + Days Inventory Outstanding (DIO) − Days Payable Outstanding (DPO)
```
- **Target:** Minimise CCC. Negative CCC = you get paid before you pay suppliers (ideal for platforms).
- **DSO reduction:** Invoice same-day, offer electronic payment, automate collections.
- **DPO optimisation:** Negotiate Net 45/60 with suppliers while maintaining relationships.

### Cash Flow Forecasting Model Structure
```
Week 1–4:   Transaction-level detail (known invoices, confirmed payments, payroll)
Week 5–8:   Category-level estimates (pipeline-weighted revenue, committed spend)
Week 9–13:  Trend-based projections (historical patterns + growth assumptions)
```

### Working Capital Optimisation for Fintech
- **Payment float management:** In payment processing, understand settlement windows per corridor:
  - Card acquiring: T+1 to T+3 depending on acquirer
  - Mobile money (MTN/Airtel): T+0 to T+1
  - Bank transfers: T+0 (Faster Payments UK) to T+2 (international)
- **Regulatory reserve buffers:** Always maintain 120% of minimum regulatory capital requirement.
- **Intercompany cash pooling:** When operating UK + Estonia + Zambia entities, use a master cash pool with sweep arrangements (subject to transfer pricing and thin capitalisation rules).

### Cash Flow Emergency Protocol
1. Freeze all non-essential hiring and discretionary spend immediately.
2. Accelerate collections: offer 5% discount for payment within 7 days.
3. Renegotiate payment terms with top 5 vendors — extend to Net 60/90.
4. Draw on existing credit facilities if available.
5. Communicate transparently with board and lead investors within 48 hours.
6. Model revised runway under new constraints — present options with trade-offs.

---

## 2. Budgeting & Forecasting Advanced

### Zero-Based Budgeting (ZBB) Process
1. Define decision units (each team/function is a unit).
2. Each unit builds budget from zero — no carry-forward from prior year.
3. Create decision packages: minimum viable, current level, growth level.
4. Rank all packages across the organisation by strategic impact.
5. Allocate budget based on ranking until funds are exhausted.
6. Review quarterly — kill underperforming packages, fund emerging needs.

### Rolling Forecast Implementation
- **Window:** Always looking 12–18 months ahead.
- **Update cadence:** Monthly for revenue/cash; quarterly for full P&L and balance sheet.
- **Variance triggers:** >10% deviation from forecast triggers root cause analysis and reforecast.
- **Driver-based:** Link forecasts to operational drivers (users, transactions, conversion rates) not just financial line items.

### Scenario Modelling Template
| Scenario | Revenue Assumption | Burn Assumption | Hiring | Probability |
|---|---|---|---|---|
| Bull case | 150% of plan | Plan + 20% (investment) | Accelerated | 20% |
| Base case | 100% of plan | As planned | As planned | 50% |
| Bear case | 60% of plan | Plan − 30% (cuts) | Freeze | 25% |
| Crisis case | 30% of plan | Survival mode | Reductions | 5% |

For each scenario: model cash runway, identify trigger points for switching between scenarios, and define actions required.

### FP&A Rhythm (Annual Calendar)
| Month | Activity |
|---|---|
| January | Annual plan finalisation. Board approval. |
| February | Q4 close. Year-end reporting. Tax prep. |
| March | Q1 forecast update. Budget vs actual review. |
| April | Q1 board meeting. Updated full-year forecast. |
| May | Mid-year planning kickoff if needed. |
| June | Q2 forecast update. Half-year review. |
| July | Q2 board meeting. Consider plan pivot if needed. |
| August | Preliminary next-year planning assumptions. |
| September | Q3 forecast update. Next-year budget drafting begins. |
| October | Q3 board meeting. Draft budget review. |
| November | Next-year budget finalisation. |
| December | Board budget approval for next year. |

---

## 3. Financial Reporting & Board Packs

### Monthly Investor Update Template
```
Subject: [Company] — [Month] Update

🔑 Highlights (3–5 bullets)
- [Biggest win]
- [Key metric milestone]
- [Product/customer update]

📊 Key Metrics
- Revenue/MRR: £X (+Y% MoM)
- Burn rate: £X/month
- Cash runway: X months
- Users/customers: X (+Y)
- Churn: X%

👥 Team
- [New hires, departures, org changes]

⚠️ Challenges
- [Be honest. Transparency builds trust.]

🙏 Asks (Specific & actionable)
1. [Introduction to specific person at specific company]
2. [Advice on specific decision — frame the question]
3. [Hiring: specific role profile, not generic request]
```

### Board Reporting Package (Series A+)
1. **Executive summary** — 1 page. Key wins, key risks, top asks.
2. **Financial performance** — P&L actual vs budget vs prior year. Waterfall chart for revenue.
3. **Cash position** — Cash balance, burn rate, runway. Cash flow forecast for next 6 months.
4. **KPI dashboard** — Product metrics, customer metrics, operational metrics.
5. **Strategic update** — Progress against OKRs/annual plan milestones.
6. **Risk register** — Top 5 risks with status, mitigation progress, and owner.
7. **Appendix** — Detailed financials, customer pipeline, hiring plan.

### Reporting by Stage

| Stage | Report Depth | Frequency | Audience |
|---|---|---|---|
| Pre-seed | Lightweight email update | Monthly | Angels, advisors |
| Seed | Structured email + 3 KPIs | Monthly | Angels, seed VCs |
| Series A | Full board pack (7 components) | Quarterly + monthly email | Board, all investors |
| Series B+ | Enterprise-grade reporting | Quarterly board + monthly KPIs | Board, all investors, lenders |

---

## 4. Capital Allocation & Fundraising Mechanics

### SAFE vs Convertible Note vs Priced Round

| Feature | SAFE | Convertible Note | Priced Round |
|---|---|---|---|
| Debt instrument? | No | Yes (has interest, maturity) | No (equity) |
| Valuation required? | No (cap + discount) | No (cap + discount) | Yes |
| Legal complexity | Low | Medium | High |
| Cost | £1K–£5K | £3K–£10K | £15K–£50K+ |
| Best for | Pre-seed/seed | Bridge rounds | Series A+ |
| Dilution timing | At conversion | At conversion | Immediate |

### Dilution Planning
| Round | Typical Dilution | Founder Ownership After |
|---|---|---|
| Pre-seed | 5–15% | 85–95% |
| Seed | 15–25% | 65–80% |
| Series A | 15–25% | 45–65% |
| Series B | 15–20% | 35–55% |
| Series C | 10–17% | 25–45% |
| IPO/Exit | Variable | 15–30% (typical) |

### Due Diligence Preparation Checklist
- [ ] Certificate of incorporation + articles of association (all entities)
- [ ] Cap table (fully diluted, all SAFE/convertible notes modelled)
- [ ] 2–3 years historical financials (or since inception)
- [ ] Financial model with assumptions documentation
- [ ] Customer contracts and pipeline summary
- [ ] IP ownership documentation (assignments, licences)
- [ ] Employment agreements and option pool details
- [ ] Regulatory licences, applications, and correspondence
- [ ] Material contracts (vendors, partners, landlords)
- [ ] Insurance policies
- [ ] Litigation summary (or confirmation of none)
- [ ] Data protection compliance evidence (GDPR, etc.)
- [ ] Technical architecture documentation

### Fundraising Process Optimisation
- **Batch meetings.** Schedule investor meetings in compressed 2–3 week sprints to create urgency.
- **Create FOMO through transparency.** Share that you're in active conversations (without naming names).
- **Lead investor first.** Focus on securing a lead before filling the round.
- **Term sheet within 4–6 weeks** of first meeting with lead = healthy pace.
- **Never stop building.** The best fundraising strategy is visible, measurable progress during the raise.

---

## 5. Cost Optimisation Detailed Strategies

### Cloud Cost Optimisation (FinOps)
| Strategy | Savings Potential | Implementation Effort |
|---|---|---|
| Reserved instances / Savings Plans | 30–60% | Medium |
| Spot/preemptible instances | 60–90% | High (needs fault tolerance) |
| Rightsizing (CPU/memory) | 20–40% | Low |
| Auto-scaling policies | 15–30% | Medium |
| Serverless migration | 40–70% | High |
| Storage tiering (hot/warm/cold) | 20–50% | Low |
| Delete unused resources | 10–20% | Low |

### SaaS Stack Audit Process
1. **Inventory:** List every SaaS subscription with owner, cost, and user count.
2. **Usage analysis:** Login frequency, feature utilisation, API call volume.
3. **Consolidation:** Identify overlapping tools. One platform > three point solutions.
4. **Renegotiation:** Annual contracts at renewal. Multi-year for critical tools.
5. **Elimination:** Kill anything with < 50% utilisation or no clear business owner.

### Headcount Cost Framework
| Role Type | Approach | Rationale |
|---|---|---|
| Core differentiator (engineering, product) | Full-time hire | IP retention, culture, speed |
| Specialist (legal, compliance, tax) | Fractional / outsourced | Cost efficiency, expertise access |
| Variable demand (design, content) | Contract / agency | Flexibility, project-based |
| Administrative | Automate first, then hire | Reduce fixed cost base |

---

## 6. Tax Planning by Jurisdiction

### United Kingdom
- **Corporation tax:** 25% (profits > £250K), 19% small profits rate (< £50K), marginal relief between.
- **R&D tax credits:** Enhanced deduction for qualifying R&D expenditure. SME scheme or RDEC.
- **SEIS:** Up to £250K investment. Investors get 50% income tax relief + CGT exemption. Company must be < 3 years old, < £350K gross assets, < 25 employees.
- **EIS:** Up to £5M/year (£12M lifetime). 30% income tax relief for investors. More flexible than SEIS.
- **Patent Box:** 10% effective tax rate on profits from patented inventions.
- **EMI options:** Tax-efficient employee share options for qualifying companies.
- **VAT:** Register when turnover exceeds £90K threshold. Digital services have specific place-of-supply rules.

### Estonia
- **Corporation tax:** 0% on retained earnings. 20% (14% reduced rate for regular distributions) on distributed profits only.
- **Advantage:** Reinvest profits tax-free indefinitely. Pay tax only when you distribute.
- **e-Residency:** Digital identity for remote company management. Does not create tax residency.
- **PE risk:** If management decisions are made from UK, the Estonian company may create a UK PE — get advice.
- **VAT:** Standard rate 22%. EU intra-community supply rules apply.

### Zambia
- **Corporate income tax:** 30% standard rate (varies by sector — mining, agriculture have different rates).
- **Withholding tax:** Dividends (15%/20%), interest (15%/20%), royalties (15%/20%). Treaty relief may apply.
- **Transfer pricing:** Zambia has transfer pricing rules. Intercompany transactions must be at arm's length.
- **Bank of Zambia levies:** Regulatory fees for licensed financial institutions.
- **VAT:** 16% standard rate.

### Cross-Border Planning
- **Transfer pricing documentation:** Mandatory for intercompany transactions. Use OECD guidelines.
- **Double tax treaties:** UK-Zambia, UK-Estonia. Check treaty rates for withholding tax reduction.
- **Permanent establishment risk:** Management activities in one country can create tax presence for another entity.
- **Holding company location:** Consider optimal holding company jurisdiction for dividend flows and IP ownership.
- **Exit planning:** Structure early for tax-efficient exit (QSBS equivalents, entrepreneurs' relief).

---

## 7. Revenue & Pricing Deep Dive

### Pricing Development Process
1. **Customer research:** Willingness-to-pay surveys, Van Westendorp pricing sensitivity meter.
2. **Competitive mapping:** Position on value vs price matrix relative to alternatives.
3. **Cost floor:** Calculate minimum viable price (all variable costs + contribution to fixed).
4. **Value ceiling:** Maximum price customers will pay based on perceived value.
5. **Strategic positioning:** Choose point between floor and ceiling aligned with brand and growth goals.
6. **A/B testing:** Test 2–3 price points with real customers before committing.
7. **Monitor and iterate:** Review pricing quarterly. Markets and value perceptions shift.

### Payment/Fintech Revenue Models
| Model | Description | Example |
|---|---|---|
| Transaction fee (% + fixed) | Per-transaction charge | 1.5% + 20p per card payment |
| Subscription (SaaS) | Monthly/annual platform fee | £49/month for merchant dashboard |
| Interchange plus | Pass-through interchange + markup | IC + 0.3% for payment processing |
| Float income | Interest on held funds | Settlement float interest |
| FX markup | Spread on currency conversion | 0.5% on cross-border transactions |
| Premium features | Tiered add-ons | Advanced analytics, priority support |
| Data services | Anonymised transaction insights | Industry benchmarking reports |

### Revenue Recognition (IFRS 15 / ASC 606)
- **Five-step model:** Identify contract → identify obligations → determine price → allocate to obligations → recognise when satisfied.
- **Subscription revenue:** Recognise ratably over the subscription period.
- **Transaction revenue:** Recognise at the point the service is delivered.
- **Setup fees:** Defer and recognise over the estimated customer relationship period.
- **Variable consideration:** Estimate and constrain. Volume discounts, refund provisions.

---

## 8. Financial Risk Management Framework

### Enterprise Risk Register Template
| Risk ID | Category | Description | Likelihood (1-5) | Impact (1-5) | Risk Score | Mitigation | Owner | Status |
|---|---|---|---|---|---|---|---|---|
| FIN-001 | Liquidity | Cash runway < 6 months | | | | Cash reserve policy, credit facility | CFO | |
| FIN-002 | FX | GBP/ZMW exposure > £50K | | | | Hedging policy, natural hedging | Treasury | |
| REG-001 | Compliance | FCA reporting deadline miss | | | | Automated compliance calendar | Compliance | |
| OPS-001 | Technology | Payment processing outage > 1hr | | | | Redundancy, failover, monitoring | CTO | |
| CYB-001 | Cybersecurity | Customer data breach | | | | SOC2, pen testing, encryption | CISO/CTO | |

### AML/KYC Programme Components (Fintech Non-Negotiable)
1. **Risk assessment:** Document your ML/TF risk assessment covering products, customers, geographies, channels.
2. **CDD/KYC procedures:** Identity verification, address verification, source of funds (for higher-risk).
3. **EDD:** Enhanced checks for high-risk customers, PEPs, high-risk jurisdictions.
4. **Transaction monitoring:** Rules-based + anomaly detection. Calibrated to business model.
5. **SAR filing:** Clear procedures for identifying, escalating, and filing suspicious activity reports.
6. **Training:** Annual AML training for all staff. Role-specific training for front-line.
7. **MLRO appointment:** Designated Money Laundering Reporting Officer with board access.
8. **Record keeping:** 5-year minimum retention for all KYC records and transaction data.

### Business Continuity Framework
- **Business Impact Analysis (BIA):** Identify critical processes, recovery time objectives (RTO), recovery point objectives (RPO).
- **Disaster Recovery Plan:** Technology recovery procedures, backup strategies, failover systems.
- **Crisis Communication Plan:** Internal and external communication templates, spokesperson designation.
- **Testing:** Annual tabletop exercise + annual technical recovery test.
- **Third-party continuity:** Ensure critical vendors have their own BCP. Include in TPRM assessments.

---

## 9. Financial Technology Stack

### Recommended Stack by Stage

| Function | Pre-Seed/Seed | Series A | Series B+ |
|---|---|---|---|
| Accounting | Xero / QuickBooks | Xero + integration layer | NetSuite / Sage Intacct |
| Banking | Mercury / Revolut Business | Mercury + multi-currency | J.P. Morgan / HSBC + treasury |
| Expense management | Pleo / Dext | Pleo + approval workflows | SAP Concur / Brex |
| FP&A / Modelling | Spreadsheets | Causal / Pigment | Anaplan / Adaptive Planning |
| Investor relations | Email + Notion | Visible.vc | Visible.vc + Carta |
| Cap table | Carta / SeedLegals | Carta | Carta |
| Tax compliance | Accountant | Accountant + Avalara/Kintsugi | Big 4 + tax automation |
| Payroll | Gusto / PayFit | Deel / Remote | Deel + local providers |
| Revenue analytics | Manual / Stripe Dashboard | ChartMogul / Baremetrics | Looker / Tableau |

### Integration Principles
- Single source of truth for financial data (accounting system is master).
- Automate data flows between systems — no manual re-keying.
- Bank feed reconciliation daily (automated).
- Monthly close process documented and repeatable.

---

## 10. KPI Reference Library

### Financial KPIs

| KPI | Formula | Target | Frequency |
|---|---|---|---|
| Gross margin | (Revenue − COGS) ÷ Revenue | > 60% (SaaS), > 30% (payments) | Monthly |
| Operating margin | Operating income ÷ Revenue | Improving trend toward breakeven | Monthly |
| Burn rate (net) | Cash out − Cash in (monthly) | Declining over time | Monthly |
| Cash runway | Cash balance ÷ Net burn rate | > 18 months post-raise | Monthly |
| Burn multiple | Net burn ÷ Net new ARR | < 2x (good), < 1x (excellent) | Quarterly |
| Rule of 40 | Revenue growth % + profit margin % | > 40% | Quarterly |
| Quick ratio (SaaS) | (New MRR + Expansion MRR) ÷ (Churned MRR + Contraction MRR) | > 4x | Monthly |
| Working capital ratio | Current assets ÷ Current liabilities | 1.5–2.0 | Monthly |
| Debt-to-equity | Total debt ÷ Total equity | < 0.5 for early-stage | Quarterly |

### Operational/Product KPIs

| KPI | What It Measures | Target |
|---|---|---|
| Monthly active users (MAU) | Product engagement | Growing MoM |
| Daily active / Monthly active (DAU/MAU) | Stickiness | > 20% (good), > 50% (excellent) |
| Activation rate | % of signups completing key action | > 25% |
| Churn rate (monthly) | % of customers lost per month | < 5% (SMB), < 1% (enterprise) |
| Net Promoter Score (NPS) | Customer satisfaction/loyalty | > 40 (good), > 70 (excellent) |
| Time to value | Time from signup to first value moment | Minimise relentlessly |
| Support ticket volume | Operational efficiency / product quality | Declining per user over time |

### Fundraising KPIs

| KPI | What It Measures | Benchmark |
|---|---|---|
| Investor meetings to term sheet | Fundraising efficiency | 50–80 meetings per term sheet |
| Time to close | Fundraising velocity | 3–6 months total |
| Follow-on rate | Investor satisfaction | > 50% of existing investors follow on |
| Investor update open rate | Engagement quality | > 70% |
| Warm intro conversion | Network effectiveness | 30–50% meeting rate from warm intros |

---

**End of detailed reference. Return to SKILL.md for the condensed operational framework.**
