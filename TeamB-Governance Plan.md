# Governance Plan — PSP Beauty & Wellness Ecosystem Platform

Team: Nana Danelia, Daviti Mtchedlishvili, Davit Kulua, Mariam Berekashvili  
Industry context: Digital Healthcare, Pharmacy Retail, AI-Powered Wellness Ecosystem  
Version: Final v1  
Date: June 2026

---

# Section 1: AI Use Case Risk Classification

| AI use case | EU AI Act risk tier | Rationale for classification | Georgian law obligation |
|---|---|---|---|
| AI skincare product recommendation engine | Limited risk | The system provides personalized recommendations but does not independently make legally binding medical decisions | Must inform users that recommendations are AI-generated; comply with Georgian personal data protection law |
| AI-driven customer segmentation and loyalty targeting | Limited risk | AI analyzes behavioral and purchase data to personalize campaigns and offers | Customer consent and lawful processing of behavioral data required |
| AI-powered cross-sell and basket recommendation system | Minimal risk | Commercial recommendation functionality with low impact on individual rights | General consumer protection and data processing compliance |
| AI chatbot / onboarding assistant | Limited risk | Users interact directly with AI-generated responses and onboarding flows | Transparency obligation: users must know they interact with AI |
| AI-assisted skincare advisor appointment matching | Limited risk | AI recommends advisors but final consultation remains human-led | Customer data and scheduling data must be protected |
| AI skin-analysis functionality (future H3 option) | High risk | Potentially influences healthcare-related decisions using biometric/image analysis | Requires human oversight, transparency, documented escalation logic, and stronger data protection controls |
| AI-driven retention and churn prediction model | Limited risk | Used for personalized loyalty and retention campaigns, not legally binding decisions | Consent and behavioral profiling transparency required |

**EU AI Act risk tiers for reference:**
- Unacceptable risk: prohibited, cannot be deployed
- High risk: permitted but requires conformity assessment, human oversight, and transparency to affected individuals
- Limited risk: permitted with transparency obligations
- Minimal risk: permitted with no specific obligations beyond general law

---

# Section 2: Oversight Body

## Name of oversight body

PSP AI Governance & Ecosystem Oversight Committee

## Executive sponsor (C-suite role)

Chief Digital Officer (CDO)

## Membership

| Function | Role title | Decision authority |
|---|---|---|
| Digital & Technology | Chief Digital Officer | Final authority on AI deployment approval |
| Legal & Compliance | Head of Legal / Compliance Officer | Regulatory and data protection approval |
| Medical Partnerships | Medical Partnerships Manager | Approval for medical-related AI workflows |
| CRM & Customer Data | CRM/Loyalty Director | Customer-data governance approval |
| IT & Data | Head of Data & AI | Technical model governance and monitoring |
| Marketing & Partnerships | Marketing Director | Creator ecosystem and customer engagement oversight |
| Executive Management | CEO or Executive Sponsor | Final escalation authority |

---

## Decision rights

| Decision type | Approval required before | Quorum required |
|---|---|---|
| Deployment of any high-risk AI use case | Public release or customer activation | CDO + Legal + Medical + Data representatives |
| Changes to model thresholds affecting customer recommendations | Production deployment | Minimum 4 committee members |
| Response to a model failure or adverse outcome | Public response or system reactivation | Executive sponsor + Legal + Data lead |
| Deployment of AI skin-analysis functionality | Any pilot or launch activity | Full committee approval |

---

## Review cadence

| Review type | Frequency | Trigger |
|---|---|---|
| Routine governance review | Quarterly | Scheduled governance cycle |
| Adverse outcome review | Within 48 hours | Customer complaint, model failure, or incorrect recommendation escalation |
| Regulatory enquiry response | Immediate | Regulatory request or legal investigation |
| AI model performance review | Monthly | KPI and recommendation monitoring |

---

# Section 3: Human Override Protocol

## Use case 1: AI Skin-Analysis Functionality

| Element | Detail |
|---|---|
| Trigger threshold | AI identifies possible severe skin condition, allergic reaction, or prescription-linked recommendation |
| Override authority | Licensed dermatologist partner |
| Documentation requirement | Full recommendation log, image analysis record, escalation decision documentation |
| Maximum review time | 24 hours |
| Default action if review time exceeded | Recommendation blocked until human review completed |

---

## Use case 2: AI Recommendation Engine

| Element | Detail |
|---|---|
| Trigger threshold | Customer complaint regarding incorrect or harmful skincare recommendation |
| Override authority | Medical Partnerships Manager |
| Documentation requirement | Customer interaction log, recommendation history, escalation report |
| Maximum review time | 48 hours |
| Default action if review time exceeded | Recommendation category temporarily disabled for affected customer segment |

---

## Use case 3: AI Retention & Segmentation Campaigns

| Element | Detail |
|---|---|
| Trigger threshold | Customer requests explanation or removal from AI-driven profiling |
| Override authority | CRM/Loyalty Director |
| Documentation requirement | Customer consent and profiling audit trail |
| Maximum review time | 72 hours |
| Default action if review time exceeded | Customer removed from AI-personalized targeting campaigns |

---

# Section 4: Change Management Workstream

## Change management budget

GEL 90,000

## Total transformation cost from ROI model

GEL 370,000

## Percentage allocated to change management

24%

## Owner function

HR / Transformation Office / Chief Digital Officer

---

## Timeline

| Phase | Months | Key activities |
|---|---|---|
| Phase 1: Stakeholder analysis and communication | Months 1–3 | Executive alignment, governance communication, internal awareness campaigns |
| Phase 2: Training and capability building | Months 3–6 | AI literacy training, CRM and ecosystem workflow training, governance workshops |
| Phase 3: Pilot adoption and feedback | Months 6–12 | MVP rollout support, adoption monitoring, employee feedback collection |
| Phase 4: Scale and embedding | Months 12–18 | Governance integration into routine operations, KPI-based performance monitoring |

---

# Section 5: Governance Roadmap Connection

| Governance initiative | Roadmap month (start) | Roadmap month (end) | Owner function |
|---|---|---|---|
| Data governance framework | Month 1 | Month 3 | IT / Data / CRM |
| Oversight body established | Month 1 | Month 2 | Executive Management |
| Human override protocols documented | Month 2 | Month 4 | Legal / Medical Partnerships / Data Team |
| Human override protocols tested | Month 4 | Month 6 | IT / Medical Partnerships |
| First quarterly governance review | Month 6 | Month 6 | AI Governance Committee |
| Second quarterly governance review | Month 9 | Month 9 | AI Governance Committee |
| AI governance KPI dashboard integration | Month 12 | Month 18 | Data / Finance / Digital Product |

---

# Section 6: Escalation Path

## When the oversight body cannot reach a decision

### Step 1

Issue escalated to Executive Sponsor (Chief Digital Officer)

### Step 2

Joint review conducted with Legal/Compliance and Executive Management

### Step 3 (final escalation)

Final decision made by CEO / Executive Committee

## Maximum time from escalation trigger to resolution

7 business days

---

# Quality checklist

- [x] Every AI use case from the roadmap is classified by EU AI Act tier with rationale
- [x] Oversight body has defined membership and decision rights
- [x] Human override protocols exist for high-risk use cases
- [x] Georgian data protection obligations referenced
- [x] Governance initiatives appear in roadmap before AI deployment
- [x] Change management budget equals 20–30 percent of total transformation cost
- [x] Escalation path defined and specific

---

*Deliverable: governance_plan_v1.md*  
*Prepared for PSP Beauty & Wellness Ecosystem Platform Final Project*
