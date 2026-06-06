# Governance and Change Management Plan — PSP Beauty & Wellness Ecosystem Platform

**Version:** Final v2
**Team:** Nana Danelia, Daviti Mtchedlishvili, Davit Kulua, Mariam Berekashvili
**Industry context:** Digital Healthcare, Pharmacy Retail, AI-Powered Wellness Ecosystem
**Date:** June 2026

---

## Section 1: AI Use Case Risk Classification

| AI use case | EU AI Act risk tier | Rationale | Georgian law obligation |
|---|---|---|---|
| AI skincare product recommendation engine | Limited risk | Provides personalized recommendations but does not make legally binding medical decisions | Must inform users that recommendations are AI-generated; comply with Georgian Personal Data Protection Law |
| AI-driven customer segmentation and loyalty targeting | Limited risk | Analyzes behavioral and purchase data to personalize campaigns and offers | Customer consent and lawful processing of behavioral data required |
| AI-powered cross-sell and basket recommendation system | Minimal risk | Commercial recommendation functionality with low impact on individual rights | General consumer protection and data processing compliance |
| AI chatbot and onboarding assistant | Limited risk | Users interact directly with AI-generated responses and onboarding flows | Transparency obligation: users must know they interact with AI |
| AI-assisted skincare advisor appointment matching | Limited risk | AI recommends advisors but final consultation remains human-led | Customer and scheduling data must be protected |
| AI skin-analysis functionality (H3 option) | High risk | Potentially influences healthcare decisions using biometric and image analysis | Requires human oversight, transparency, documented escalation logic, and stronger data protection controls |
| AI-driven retention and churn prediction model | Limited risk | Used for loyalty and retention campaigns; not legally binding decisions | Consent and behavioral profiling transparency required |

**EU AI Act risk tiers for reference:**
- Unacceptable risk: prohibited, cannot be deployed
- High risk: permitted but requires conformity assessment, human oversight, and transparency to affected individuals
- Limited risk: permitted with transparency obligations
- Minimal risk: permitted with no specific obligations beyond general law

---

## Section 2: Oversight Body

**Name:** PSP AI Governance and Ecosystem Oversight Committee
**Executive sponsor:** Chief Digital Officer (CDO)

### Membership

| Function | Role title | Decision authority |
|---|---|---|
| Digital and Technology | Chief Digital Officer | Final authority on AI deployment approval |
| Legal and Compliance | Head of Legal / Compliance Officer | Regulatory and data protection approval |
| Medical Partnerships | Medical Partnerships Manager | Approval for medical-related AI workflows |
| CRM and Customer Data | CRM/Loyalty Director | Customer data governance approval |
| IT and Data | Head of Data and AI | Technical model governance and monitoring |
| Marketing and Partnerships | Marketing Director | Creator ecosystem and customer engagement oversight |
| Executive Management | CEO or Executive Sponsor | Final escalation authority |

### Decision Rights

| Decision type | Approval required before | Quorum required |
|---|---|---|
| Deployment of any high-risk AI use case | Public release or customer activation | CDO + Legal + Medical + Data representatives |
| Changes to model thresholds affecting customer recommendations | Production deployment | Minimum 4 committee members |
| Response to a model failure or adverse outcome | Public response or system reactivation | Executive Sponsor + Legal + Data lead |
| Deployment of AI skin-analysis functionality | Any pilot or launch activity | Full committee approval |

### Review Cadence

| Review type | Frequency | Trigger |
|---|---|---|
| Routine governance review | Quarterly | Scheduled governance cycle |
| Adverse outcome review | Within 48 hours | Customer complaint, model failure, or incorrect recommendation escalation |
| Regulatory enquiry response | Immediate | Regulatory request or legal investigation |
| AI model performance review | Monthly | KPI and recommendation monitoring |

---

## Section 3: Human Override Protocols

### Use Case 1 — AI Skin-Analysis Functionality (H3)

| Element | Detail |
|---|---|
| Trigger threshold | AI identifies possible severe skin condition, allergic reaction, or prescription-linked recommendation |
| Override authority | Licensed dermatologist partner |
| Documentation requirement | Full recommendation log, image analysis record, escalation decision documentation |
| Maximum review time | 24 hours |
| Default action if review time exceeded | Recommendation blocked until human review completed |

### Use Case 2 — AI Recommendation Engine

| Element | Detail |
|---|---|
| Trigger threshold | Customer complaint regarding incorrect or harmful skincare recommendation |
| Override authority | Medical Partnerships Manager |
| Documentation requirement | Customer interaction log, recommendation history, escalation report |
| Maximum review time | 48 hours |
| Default action if review time exceeded | Recommendation category temporarily disabled for affected customer segment |

### Use Case 3 — AI Retention and Segmentation Campaigns

| Element | Detail |
|---|---|
| Trigger threshold | Customer requests explanation or removal from AI-driven profiling |
| Override authority | CRM/Loyalty Director |
| Documentation requirement | Customer consent and profiling audit trail |
| Maximum review time | 72 hours |
| Default action if review time exceeded | Customer removed from AI-personalized targeting campaigns |

---

## Section 4: Change Management Workstream

**Budget:** GEL 40,000
**Total one-time transformation cost:** GEL 506,000
**Percentage allocated to change management:** 7.9%
**Industry benchmark:** 15–20% of project cost. Budget is below benchmark and justified by moderate scope — no retrenchments, no restructuring, primarily upskilling existing staff and establishing new digital workflows. If organizational resistance proves higher than anticipated, budget should be increased to GEL 75,000–100,000.
**Owner function:** HR / Transformation Office / Chief Digital Officer
**Timeline:** Months 1–18

### Phased Budget Breakdown

| CM activity | Description | Phase | Months | Owner | Budget (GEL) |
|---|---|---|---|---|---|
| Stakeholder analysis and alignment | Executive buy-in, governance communications, internal awareness campaigns | Phase 1 | M1–3 | CDO / HR | 8,000 |
| AI literacy training | Basic AI concepts for all staff; ecosystem tool training | Phase 2 | M3–6 | HR / Training | 12,000 |
| CRM and ecosystem workflow training | CRM system, loyalty dashboard, advisor tools | Phase 2 | M3–6 | CRM / IT | 8,000 |
| Governance workshops | AI oversight, data protocols, human override procedures | Phase 2 | M4–6 | Legal / CDO | 4,000 |
| Pilot adoption support | MVP rollout support, adoption monitoring, employee feedback collection | Phase 3 | M6–12 | Digital / HR | 5,000 |
| Scale and embedding | Governance integration into routine operations, KPI-based performance monitoring | Phase 4 | M12–18 | CDO / Governance | 3,000 |
| **Total** | | | **M1–18** | | **40,000** |

**Success metric:** Internal teams trained; operating responsibilities assigned; monthly governance meetings active; adoption barriers tracked and resolved within 30 days of identification.

---

## Section 5: Governance Roadmap Connection

| Governance initiative | Start month | End month | Owner function |
|---|---|---|---|
| Data governance framework | Month 1 | Month 3 | IT / Data / CRM |
| Oversight body established | Month 1 | Month 2 | Executive Management |
| Human override protocols documented | Month 2 | Month 4 | Legal / Medical Partnerships / Data Team |
| Human override protocols tested | Month 4 | Month 6 | IT / Medical Partnerships |
| First quarterly governance review | Month 6 | Month 6 | AI Governance Committee |
| Second quarterly governance review | Month 9 | Month 9 | AI Governance Committee |
| AI governance KPI dashboard integration | Month 12 | Month 18 | Data / Finance / Digital Product |

---

## Section 6: Escalation Path

**Step 1:** Issue escalated to Executive Sponsor (Chief Digital Officer).
**Step 2:** Joint review conducted with Legal/Compliance and Executive Management.
**Step 3 (final escalation):** Final decision made by CEO / Executive Committee.
**Maximum time from escalation trigger to resolution:** 7 business days.

---

## Section 7: Georgian Data Protection Law Obligations

All AI use cases processing personal, behavioral, or health-related customer data must comply with Georgian Personal Data Protection Law. Specific obligations:

1. Informed consent must be obtained before any personal data is collected for AI training or personalization purposes.
2. Users must be informed when they are interacting with an AI system rather than a human advisor.
3. Customers have the right to request erasure of their data from AI training datasets and personalization profiles.
4. Data minimization principle applies: only data necessary for the stated purpose may be collected and retained.
5. A data protection responsible person must be appointed within PSP before any AI system goes live.
6. Any data breach must be reported to the Personal Data Protection Service of Georgia within 72 hours.

---

## Quality Checklist

- [x] Every AI use case from the roadmap is classified by EU AI Act tier with rationale
- [x] Oversight body has defined membership and decision rights
- [x] Human override protocols exist for high-risk use cases with specific trigger thresholds
- [x] Georgian data protection obligations referenced with specific requirements
- [x] Governance initiatives appear in roadmap before AI deployment
- [x] Change management budget stated with percentage of total transformation cost
- [x] Change management phased breakdown provided with owner and budget per phase
- [x] Escalation path defined with specific steps and maximum resolution time
