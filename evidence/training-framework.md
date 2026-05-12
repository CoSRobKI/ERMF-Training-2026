# KeyInvest Risk Learning Framework

**Document classification:** Internal
**Owner:** Risk & Compliance Team
**Status:** In effect
**Aligned to:** Enterprise-wide Risk Management Strategy (ERMS) — Board-approved June 2025
**Approver:** Chief Risk Officer

---

## 1. Purpose

This Framework documents how KeyInvest meets the staff training and capability requirements of:

- **APRA CPS 220** — clause requiring all staff to understand their role within the Risk Management Framework
- **APRA CPS 230** — operational resilience, requiring staff capability proportionate to role
- **APRA CPS 234** — information security capability across the workforce
- **ERMS Section 5 — Accountability and Risk Culture** — requires a regular, comprehensive risk awareness training program for all employees, led by Line 2 Risk and Compliance
- **Incident Management Policy Section 3.8** — all staff must receive training on Incident Management expectations relevant to their roles
- **Issue Management Policy Section 3.7** — equivalent requirement for Issue Management

The Framework provides the structure, evidence trail, and assurance basis for KeyInvest's risk learning programme.

---

## 2. Design principles

The risk learning programme is designed around five principles:

1. **Behavioural, not just informational.** Modules force decision-making in realistic scenarios. Awareness alone does not change behaviour; practice does.
2. **Anchored to policy.** Every module explicitly cites the KeyInvest policies and procedures it supports, with the source documents listed in-module.
3. **Calibrated to role.** The All Staff stream covers baseline obligations everyone must meet. The Manager stream (in development) layers in governance, oversight, and decision-making content for those with ownership accountabilities.
4. **Evidenced.** Each completion produces a structured record (name, role, date, time, score, reference code) transmitted to the LMS via SCORM 1.2 or displayed on screen.
5. **Stable.** Modules use softened policy-timeframe language to remain accurate across minor policy updates, with assessment questions retaining specific timeframes where staff recall is the learning objective.

---

## 3. Learning architecture

The programme is structured as a sequenced pathway:

| # | Module | Learning behaviour | Primary CPS alignment |
|---|---|---|---|
| 1 | Understanding Risk at KeyInvest | Understand the framework, risk appetite, and Line 1 ownership | CPS 220 |
| 2 | Recognising and Reporting Incidents | Recognise an Incident and respond within 24 hours | CPS 230, CPS 234 |
| 3 | Identifying and Raising Issues | Recognise a control weakness and work it through the remediation lifecycle | CPS 220, CPS 230, CPS 234 |

Each module builds on the previous one. Module 1 establishes the conceptual baseline; Module 2 operationalises the response behaviour; Module 3 operationalises the remediation behaviour.

---

## 4. Module design pattern

Every module follows the same seven-component structure:

1. **Hero intro** — title, audience, duration, CPS hooks
2. **What you will learn** — five concrete learning objectives
3. **Policy anchoring card** — explicit citation of source policies
4. **Behavioural anchor card** — the 3- or 4-step action sequence for this domain
5. **Concept section** — foundational knowledge with at most two light visuals (e.g. risk pyramid, role comparison table, regulatory timeline)
6. **Four scenarios** — multi-choice responses with detailed feedback on both correct and incorrect answers
7. **Completion screen** — score, key takeaways, declaration, SCORM reporting

This pattern is deliberately consistent across modules to support cognitive familiarity for staff, and structural consistency for audit walkthrough.

---

## 5. Behavioural anchors (cross-module)

Two repeating principles run through every module and represent the cultural intent of the programme:

### Identify — Act — Report
1. **Identify** risks, Incidents, and Issues in your work — including near-misses.
2. **Act** to take the immediate safe action — contain the problem, follow the control, escalate without delay.
3. **Report** through Drova, or to your manager / Risk & Compliance if you cannot access Drova.

### Assume — Escalate — Log — Let the framework decide
1. **Assume** it is an Incident — even if you are unsure.
2. **Escalate** immediately to your manager, or directly to Risk & Compliance if unavailable.
3. **Log** it in Drova promptly and within required policy timeframes.
4. **Let the framework decide** — classification, severity rating, and regulatory reportability are Risk & Compliance's role, not yours.

Both anchors reinforce the same cultural shift: *staff identify and raise; the framework classifies and decides.* This division of work is essential to data quality in Drova and to KeyInvest's ability to meet regulatory notification deadlines.

---

## 6. Evidence capture

Each module captures a structured completion record. Records are stored in two places:

- **In-LMS** via SCORM 1.2 (`cmi.core.score.raw`, `cmi.core.lesson_status`, `cmi.suspend_data`)
- **On-screen** as a completion declaration for staff to screenshot, print, or forward

Fields captured per completion:

- Staff member's full name (self-declared)
- Team or role (self-declared)
- Module identifier
- Date and time of completion
- Quiz score (raw, out of 4)
- Pass / fail status (pass mark: 3 out of 4, or 75%)
- Unique reference code

Reference codes follow the format `KI-RMFn-YYYYMMDD-XXXXX` where `n` is the module number and `XXXXX` is a random alphanumeric string. The structure supports unique identification across the training register without requiring centralised numbering.

---

## 7. Effectiveness measurement

The Risk & Compliance Team monitors the following indicators quarterly, reporting to the BRGC:

- **Completion rate** — by team, role, and tenure
- **Score distribution** — particularly the proportion failing the 75% threshold
- **Time-to-completion** — by team, indicating engagement
- **Scenario-specific failure rates** — to identify which behavioural messages need reinforcement
- **Correlation with Drova data quality** — over time, do teams with higher completion show better Incident / Issue reporting behaviour?

The last indicator is the strategic one: training is judged on whether it changes behaviour, not whether it was attended.

---

## 8. Governance

- **Policy owner:** Chief Risk Officer
- **Content owner:** Risk & Compliance Team (Line 2)
- **Delivery channel:** KeyInvest LMS, with fallback hosting via SharePoint or GitHub Pages
- **Review cycle:** annually, or upon material change to any anchor policy or regulatory standard
- **Update triggers:**
  - Policy amendment
  - Regulatory change (CPS updates, Privacy Act, AML/CTF)
  - Material Incident or Issue indicating a learning gap
  - Internal Audit or external review finding
- **Approval for material content change:** Chief Risk Officer

---

## 9. Alignment with KIT 3.1

This learning programme is a designed closure artefact for the following KIT 3.1 evidence requirements:

- **Policies documented** — the ERMS, Incident Management, and Issue Management policies are referenced and anchored in-module
- **Procedure operationalised** — modules translate policy text into staff-level behaviour with worked examples
- **Staff trained** — completion records evidence training delivery
- **Understanding tested** — quiz scores evidence comprehension, not just attendance

See `/evidence/module-policy-mapping.xlsx` for the detailed mapping of learning outcomes to KeyInvest policies and CPS clauses.

---

## 10. References

- KeyInvest Enterprise-wide Risk Management Strategy (ERMS)
- KeyInvest Risk Appetite Statement (RAS)
- KeyInvest Incident Management Policy and Procedure
- KeyInvest Issue Management Policy and Procedure
- APRA Prudential Standard CPS 220 — Risk Management
- APRA Prudential Standard CPS 230 — Operational Risk Management
- APRA Prudential Standard CPS 234 — Information Security

---

## Document history

| Version | Date | Author | Change |
|---|---|---|---|
| 1.0 | November 2025 | Risk & Compliance | Initial Framework — Modules 1 and 2 in production, Module 3 in development |

---

*This Framework is reviewed and re-approved triennially in line with the parent policies, or sooner on material change. Next scheduled review: November 2028.*
