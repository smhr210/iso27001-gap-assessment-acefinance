# ISO 27001:2022 Annex A Compliance Gap Assessment
**Organization:** AceFinance Pvt. Ltd. (Fictional Fintech)
**Framework:** ISO/IEC 27001:2022 Annex A
**Scope:** 4 Control Domains | 24 Controls
**Date:** 2026
**Author:** Hammaad

---

## Project Overview

This project simulates an internal ISO 27001:2022 Annex A compliance gap assessment conducted for AceFinance Pvt. Ltd., a fictional 50-person fintech startup in Bengaluru handling customer PII and payment data.

The assessment evaluates control maturity across 4 domains, identifies gaps, scores risk using a Likelihood x Impact model, and produces an audit-ready compliance report with a remediation roadmap.

---

## Scope

| Domain | Annex A Reference | Controls Assessed |
|---|---|---|
| Access Control | A.5.15–A.5.18, A.8.2–A.8.5 | 8 |
| Asset Management | A.5.9–A.5.14 | 6 |
| Incident Management | A.5.24–A.5.28 | 5 |
| Supplier Relationships | A.5.19–A.5.23 | 5 |

---

## Methodology

### Maturity Scoring (0–4 Scale)

| Score | Level |
|---|---|
| 0 | Not implemented |
| 1 | Ad hoc / undocumented |
| 2 | Defined but inconsistently applied |
| 3 | Implemented and documented |
| 4 | Monitored and continuously improved |

### Risk Scoring

Risk Score = Likelihood (1–5) × Impact (1–5)

| Score Range | Rating | Action |
|---|---|---|
| 1–6 | Low | Monitor |
| 7–12 | Medium | Remediate within 90 days |
| 13–16 | High | Remediate within 60 days |
| 17–25 | Critical | Remediate within 30 days |

---

## Key Findings

- **Overall Maturity:** 1.33 / 4.00 — controls largely ad hoc and undocumented
- **Critical/High Gaps:** 6 findings requiring remediation within 30–60 days
- **Weakest Domain:** Incident Management — no formal IR plan, triage criteria, or evidence handling procedure
- **Strongest Domain:** Asset Management — existing inventory documentation from prior network security project

### Top 5 Highest-Risk Gaps

| Control | Domain | Gap | Risk Score |
|---|---|---|---|
| A.5.24 | Incident Management | No formal IR plan exists | 15 |
| A.5.19 | Supplier Relationships | No vendor risk assessment process | 20 |
| A.8.2 | Access Control | No privileged access review cadence | 20 |
| A.5.16 | Access Control | No deprovisioning SLA | 16 |
| A.5.17 | Access Control | No MFA mandate or password policy | 16 |

---

## Remediation Roadmap Summary

| Phase | Actions | Focus |
|---|---|---|
| 30-Day | 6 actions | MFA, deprovisioning SLA, IR plan initiation |
| 60-Day | 11 actions | Access reviews, supplier framework, incident runbooks |
| 90-Day | 7 actions | Asset labelling, cloud policy, annual reassessment cycle |

---

## Deliverables

- `gap-assessment/control_assessment.csv` — full 24-control assessment with maturity scores and risk ratings
- `gap-assessment/risk_register.csv` — risk register of all identified gaps
- `remediation/remediation_roadmap.csv` — 30/60/90-day action plan with owners and timelines
- `methodology/scoring_methodology.md` — detailed methodology documentation
- `reports/` — formal compliance gap assessment report (Word/PDF)

---

## Frameworks Referenced

- ISO/IEC 27001:2022 Annex A
- NIST Cybersecurity Framework (for cross-reference)
- CVSS v3.1 (risk scoring methodology)

---

## Skills Demonstrated

- ISO 27001:2022 control assessment and gap analysis
- Risk register maintenance and maturity scoring
- Audit evidence documentation and compliance reporting
- Remediation tracking and closure management
- GRC report writing for management and senior stakeholder audiences