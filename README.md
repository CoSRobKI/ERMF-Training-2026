# KeyInvest Risk Learning Portal

A modular, SCORM-compatible online learning programme for KeyInvest staff, anchored to the Enterprise-wide Risk Management Framework (ERMF) and APRA CPS 220, 230 and 234.

---

## Purpose

This learning portal exists to:

- **Build risk capability** across all KeyInvest staff in a consistent, evidenced way.
- **Operationalise the ERMF** by translating policy into practical, day-to-day behaviour.
- **Evidence training effectiveness** for APRA, internal audit, and KIT 3.1 closure.
- **Reduce risk culture failure points** — under-reporting, control bypass, role confusion.

Each module is designed as a *behavioural intervention*, not just an awareness piece. Scenarios force decision-making under pressure, with feedback that explains both correct and incorrect responses.

---

## Structure

```
risk-learning/
│
├── index.html                                    ← Learning portal (entry point)
├── README.md                                     ← This file
│
├── modules/
│   ├── module1-understanding-risk/
│   │   └── index.html
│   │
│   ├── module2-incident-management/
│   │   └── index.html
│   │
│   └── module3-issue-management/
│       └── index.html
│
├── assets/                                       ← (reserved for future use)
│   ├── css/
│   ├── js/
│   └── images/
│
└── evidence/                                     ← APRA / audit artefacts
    ├── training-framework.md
    └── module-policy-mapping.xlsx
```

Each module is a single self-contained HTML file with embedded CSS, JavaScript, and SCORM 1.2 wrapper. No external dependencies — modules run from local file, GitHub Pages, SharePoint, or any LMS that supports SCORM.

---

## Modules

| # | Title | Audience | Duration | Status | CPS Alignment |
|---|---|---|---|---|---|
| 1 | Understanding Risk at KeyInvest | All staff | ~10 min | **Available** | CPS 220 |
| 2 | Recognising and Reporting Incidents | All staff | ~10 min | **Available** | CPS 230 / 234 |
| 3 | Identifying and Raising Issues | All staff | ~10 min | In development | CPS 220 / 230 / 234 |

Planned future modules (Manager stream): Managing Risk within Appetite, Incident Leadership & Escalation, Issue Ownership & Remediation, Governance Reporting & Assurance.

---

## Module design pattern

Every module follows the same consistent structure for cognitive familiarity and regulatory defensibility:

1. **Hero intro** — module title, audience, duration, CPS hooks
2. **What you will learn** — clear learning objectives
3. **Policy anchoring** — explicit citation of the source policies and procedures
4. **Behavioural anchor** — the 3- or 4-step action sequence for this module's domain
5. **Concept section** — foundational knowledge with light visuals (no more than two per module)
6. **Four scenarios** — realistic KeyInvest situations with multi-choice responses and detailed feedback
7. **Completion screen** — score, key takeaways, declaration, SCORM reporting

---

## Evidence capture

Each module captures a completion record containing:

- Staff member's full name
- Team / role
- Date and time of completion (Australia/Adelaide time)
- Quiz score (out of 4)
- Unique reference code (`KI-RMFn-YYYYMMDD-XXXXX`)
- Pass / fail status (pass mark: 3/4)

Records are transmitted to the LMS via SCORM 1.2 (`cmi.core.score.raw`, `cmi.core.lesson_status`, `cmi.suspend_data`). When run outside an LMS, the completion declaration is displayed on-screen for staff to screenshot or print.

---

## Hosting

The portal is designed to be hosted from:

- **GitHub Pages** — simplest option, free, supports the `/risk-learning/` path
- **SharePoint Online** — drop the entire folder into a document library
- **An LMS supporting SCORM 1.2** — package each module folder as a SCORM ZIP

All modules use relative paths and require no server-side processing.

---

## Maintenance

- **Owner:** Risk & Compliance Team
- **Review cycle:** annually, or after material change to any anchor policy
- **Content updates:** triggered by policy amendments, regulatory changes (CPS updates), or learning insights from completion data

Each module references KeyInvest policies by name only (not by version number or specific clause references) and uses softened policy-timeframe language (e.g. *"promptly and within required policy timeframes — typically within 24 hours of discovery"*) to remain stable across minor policy updates.

---

## Regulatory alignment

This learning programme has been designed with the following standards and frameworks in mind:

- **APRA CPS 220** — Risk Management
- **APRA CPS 230** — Operational Risk Management
- **APRA CPS 234** — Information Security
- **Corporations Act s912** — significant breach reporting
- **Privacy Act 1988** — eligible data breach assessment
- **AML/CTF Act 2006** — AUSTRAC reporting obligations

See `/evidence/module-policy-mapping.xlsx` for the detailed mapping between learning outcomes, KeyInvest policies, and CPS requirements.

---

## Contact

For content questions: Risk & Compliance Team
For technical / hosting questions: L&D Team

---

*Last updated: November 2025*
