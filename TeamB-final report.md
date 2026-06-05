# Final Report — PSP Beauty & Wellness Ecosystem Platform

**Team:** Nana Danelia, Daviti Mtchedlishvili, Davit Kulua, Mariam Berekashvili
**Industry context:** Digital Healthcare, Pharmacy Retail, AI-Powered Wellness Ecosystem
**Date submitted:** Sunday 7 June 2026 at 23:59
**Submission file:** final_report.pdf

---

## Executive Summary

PSP operates Georgia's largest pharmacy network with GEL 745M in verified 2021 revenue, 1.9 million loyalty cardholders, and 288 pharmacy locations. Despite this scale, traditional pharmacy retail is losing differentiation as digital platforms, wellness influencers, and delivery ecosystems reshape customer expectations and competitive boundaries. PSP's existing customer base, brand trust, and digital infrastructure create a realistic foundation for ecosystem transformation — but only if the company acts before competitors replicate its loyalty and partnership advantages.

**Three conclusions the board must act on:**

1. The personalized digital wellness ecosystem strategy is the only option that creates durable competitive differentiation. Traditional pharmacy optimization and aggregator-led expansion both fail to generate proprietary customer data or switching costs.

2. The financial case is robust across all three scenarios. Total 5-year cost of ownership is GEL 3.37M. Total 5-year incremental revenue in the base case is GEL 35.25M, producing a 5-year NPV of GEL 21.8M at a 10% discount rate and a payback period of approximately 16 months.

3. Data governance must begin in Month 1. No AI personalization, customer segmentation, or recommendation engine can be deployed without clean customer data, consent logic, and defined data ownership. This is the single most critical dependency in the entire roadmap.

**Recommendation in one sentence:** PSP should launch a phased AI-enabled personalized wellness ecosystem built on its existing loyalty infrastructure, dermatologist and influencer partnerships, and pharmacy credibility, beginning with a GEL 506K MVP deployment in Months 1–6.

**ROI headline:** Payback period ~16 months (base case) | 5-year NPV GEL 21.8M at 10% discount rate | IRR ~320% base case | Downside NPV GEL 5.8M — positive in all three scenarios.

---

## 1. Industry and Competitive Analysis

### 1.1 Rogers Five Domains

| Domain | Current state | Disruption force | Strategic consequence |
|---|---|---|---|
| Customers | Customers transact at pharmacy for products and prescriptions; limited digital engagement beyond basic app use | Customers increasingly expect personalized wellness journeys, influencer-guided discovery, and integrated digital experiences | PSP must increase engagement frequency beyond the transaction or risk losing the customer relationship to digital platforms |
| Competition | Major pharmacy chains — PSP, GPC, Aversi, Pharmadepot — compete on price, convenience, and product range | Competition now includes Wolt, Glovo, beauty marketplaces, influencer commerce, and digital-first wellness startups | PSP competes beyond pharmacy chains; differentiation must come from ecosystem engagement, not product availability |
| Data | Purchase and loyalty transaction data exists but is siloed; limited behavioral or skincare profile data | Behavioral data from app interactions, skincare preferences, and content engagement becomes a strategic asset | Customer data readiness is a prerequisite for AI personalization; PSP must build this infrastructure before H2 |
| Innovation | Innovation cycles are slow; new product introductions follow supplier timelines | AI tools reduce experimentation cost; MVP-first deployment allows rapid testing of personalization features | PSP can deploy AI recommendation capabilities within 6–10 months without building proprietary AI from scratch |
| Value | Value creation is transactional — revenue from product sales and prescription fills | Value is shifting from transactions to retention, lifetime engagement, and ecosystem participation | Ecosystem participation increases customer lifetime value; repeat purchase rate and retention become primary KPIs |

### 1.2 Christensen Disruption Classification

**Classification:** Sustaining and platform-based disruption targeting the customer engagement layer of traditional pharmacy retail.

**Rationale:** The disruption affecting PSP is not a classic low-end attack by a cheaper competitor. It is a platform-based shift in which digital ecosystems — wellness apps, influencer communities, delivery platforms — are capturing the customer relationship without necessarily replacing the pharmacy transaction itself. As these platforms accumulate behavioral data and personalization capability, they reduce PSP's ability to differentiate on customer experience even when PSP retains the physical transaction.

**Strategic consequence:** PSP cannot defend its position through product range or store network alone. The recommended ecosystem strategy is a sustaining innovation for PSP's existing customer base that simultaneously builds the platform capabilities needed to compete against digital-first entrants. Acting now preserves first-mover advantage in customer data accumulation and dermatologist partnership credibility.

### 1.3 Porter Five Forces

| Force | Assessment | Named evidence | Strategic consequence |
|---|---|---|---|
| Threat of new entrants | Medium–High | Digital-first wellness startups require lower infrastructure investment than pharmacy chains; TBC Bank and BOG both operate lifestyle apps that could expand into wellness | PSP must build switching costs through personalization and loyalty integration before well-funded digital entrants establish customer relationships |
| Bargaining power of suppliers | Medium | Major beauty brands including L'Oréal and Estée Lauder are building direct-to-consumer digital channels; skincare influencers command growing negotiating power | PSP must secure dermatologist and influencer partnerships early before competitors lock in key content creators |
| Bargaining power of buyers | High | Customers can compare prices across PSP, GPC, Aversi, Wolt, and Glovo in real time; loyalty card switching cost is low | Personalization, skincare profiling, and expert content must create experiential switching costs that price comparison cannot replicate |
| Threat of substitutes | Increasing | Wolt and Glovo already deliver pharmacy products; beauty marketplaces and social commerce provide product discovery without pharmacy interaction | If PSP does not own the recommendation and discovery layer, third-party platforms will intermediate the customer relationship and commoditize PSP's role |
| Competitive rivalry | High | GPC, Aversi, and Pharmadepot offer comparable product ranges, digital ordering, and delivery services; differentiation is limited | Traditional pharmacy advantages are replicable; ecosystem-based engagement is the only source of durable differentiation |

### 1.4 Key Competitive Dynamics

**Dynamic 1:** Digital platforms are capturing the skincare and wellness discovery journey before the customer reaches the pharmacy. Influencers, dermatologist content creators, and beauty communities on Instagram, TikTok, and YouTube increasingly determine which products customers seek out. This means that PSP must become part of the discovery and recommendation layer — not just the fulfillment layer — or accept a permanently shrinking role in the customer's wellness decision-making process.

**Dynamic 2:** Loyalty programs across Georgian pharmacy retail are structurally similar and provide limited differentiation. PSP, GPC, and Aversi all offer point-based loyalty schemes with comparable redemption mechanics. This means that loyalty must evolve from a transactional reward mechanism into a personalized engagement platform — one that uses behavioral data, skincare profiling, and AI recommendations to create a customer experience that competitors cannot replicate without equivalent data infrastructure.

**Dynamic 3:** Delivery platform partnerships with Wolt and Glovo increase product accessibility but reduce brand differentiation and weaken direct customer relationships. This means that PSP must invest in direct digital engagement channels — including its own app ecosystem — to maintain ownership of the customer relationship and the data it generates.

---

## 2. AI Landscape and Opportunity Analysis

### 2.1 AI Adoption State

AI adoption in beauty, wellness, and pharmacy retail is accelerating globally. L'Oréal deploys AI-powered skin diagnostic tools and personalized product recommendation engines across its digital platforms. Sephora uses AI for virtual try-on, product matching, and loyalty personalization. In pharmacy retail, CVS Health and Boots UK deploy AI for prescription management, health recommendations, and personalized wellness content.

In Georgia, AI adoption in pharmacy retail remains nascent. No Georgian pharmacy chain has publicly deployed a customer-facing AI recommendation or personalization engine. PSP's current app provides basic product browsing and loyalty tracking without behavioral personalization.

**Most AI-advanced comparable organization:** Sephora's AI ecosystem — combining skincare profiling, behavioral recommendation, and loyalty personalization — represents the benchmark. Sephora's recommendation engine drives an estimated 35% uplift in repeat purchase rate among personalized users. PSP's gap relative to this benchmark is approximately 3–4 years of AI capability development, but can be partially closed within 18 months through API-based AI integration rather than proprietary model development.

### 2.2 AI Opportunity Map

| AI use case | Business value | Implementation readiness | Quadrant | Priority |
|---|---|---|---|---|
| Personalized skincare recommendation engine | High | High | Deploy now | 1 |
| AI-driven loyalty and retention campaigns | High | High | Deploy now | 1 |
| AI-powered cross-sell and basket recommendation | High | Medium | Plan and build | 2 |
| AI chatbot and onboarding assistant | Medium | High | Deploy now | 2 |
| AI-assisted advisor appointment matching | Medium | Medium | Plan and build | 3 |
| AI skin-analysis functionality | High | Low | Future option | 4 |
| AI-driven churn prediction model | Medium | Medium | Plan and build | 3 |

### 2.3 Strategic Implications of AI Trajectory

AI personalization in wellness retail creates compounding network effects: more customer interactions generate better behavioral data, which improves recommendation quality, which increases engagement, which generates more data. PSP's 1.9 million loyalty cardholders represent a significant data asset that, once structured and consented, can power a personalization engine that smaller competitors cannot replicate. The window for first-mover advantage in Georgian wellness AI is approximately 18–24 months before better-funded competitors or international platforms enter the market with established AI capabilities.

---

## 3. Platform Strategy Analysis

### 3.1 Platform Competitive Structure

The Georgian healthcare and wellness market is evolving from a linear retail structure toward a multi-sided platform structure. In a platform structure, value is created through interactions between multiple participant groups — consumers, dermatologists, wellness brands, influencers, and pharmacy infrastructure — rather than through one-directional product sales. Platforms that achieve critical mass of participants generate network effects that raise switching costs and reduce competitive vulnerability.

### 3.2 Client Current Position

PSP currently occupies a pipeline position — it sources products from suppliers and sells them to customers in a linear flow. It has the raw ingredients of platform participation: a large customer base, a loyalty ecosystem, existing influencer relationships, and pharmacy credibility. However, it has not yet structured these assets into a multi-sided platform with network effects. Its current position is pre-platform — asset-rich but not yet network-enabled.

### 3.3 Platform Threat Assessment

**Greatest structural threat: Wolt and Glovo expanding into wellness and pharmacy personalization.** Both platforms already intermediate pharmacy product delivery for PSP's customers. If either platform adds skincare profiling, AI recommendation, or dermatologist content, they would own the discovery, recommendation, and fulfillment layers simultaneously, reducing PSP to a warehouse and logistics provider. Wolt's expansion into grocery and pharmacy across multiple markets demonstrates the strategic intent. This threat is 12–24 months away from materialization in the Georgian market based on regional expansion patterns.

---

## 4. Strategic Options

### 4.1 Option Descriptions

**Option 1: Traditional pharmacy optimization**
- Value proposition: Lower prices, broader product range, faster delivery, and improved in-store experience for existing pharmacy customers.
- Revenue model: Product sales margin improvement; incremental volume from better availability and pricing competitiveness.
- Capability requirement: Supply chain optimization, pricing analytics, logistics improvements.
- Investment estimate: GEL 200,000–400,000 over 18 months.

**Option 2: Aggregator-led digital expansion**
- Value proposition: Increased digital accessibility through deeper integration with Wolt, Glovo, and other delivery platforms.
- Revenue model: Volume-driven product sales through third-party platforms; commission-based revenue sharing.
- Capability requirement: API integrations with delivery platforms, inventory management upgrades.
- Investment estimate: GEL 100,000–200,000 over 18 months.

**Option 3: AI-enabled personalized digital wellness ecosystem (recommended)**
- Value proposition: An integrated platform connecting consumers, dermatologists, influencers, and PSP's pharmacy infrastructure through AI-powered skincare recommendations, loyalty personalization, and wellness content.
- Revenue model: Incremental product sales from AI cross-sell; improved retention reducing churn; sponsored brand campaign fees; online advisor appointment revenue; premium subscription services in H3.
- Capability requirement: MVP platform development, AI recommendation engine integration, dermatologist and influencer partnership activation, customer data governance, loyalty personalization.
- Investment estimate: GEL 506,000 one-time + GEL 572,000 annually.

### 4.2 Evaluation Matrix

| Criterion | Option 1: Optimization | Option 2: Aggregator | Option 3: Ecosystem |
|---|---|---|---|
| Strategic fit | Low — does not address platform disruption | Low — strengthens competitors' platform position | High — builds proprietary platform with network effects |
| Financial return | Low — margin improvement only | Low — revenue shared with aggregator; no data ownership | High — GEL 35.25M 5-year incremental revenue; payback 16 months |
| Implementation feasibility | High — uses existing capabilities | High — limited new capability required | Medium — requires new team, governance, and data infrastructure |
| Risk level | High strategic risk — differentiation continues to erode | Very high strategic risk — accelerates disintermediation | Medium — phased approach limits execution risk |

### 4.3 Recommendation

**Recommended option:** Option 3 — AI-Enabled Personalized Digital Wellness Ecosystem.

**Reason 1:** PSP already has the foundational assets — 1.9M loyalty cardholders, existing influencer relationships confirmed willing to participate, and pharmacy credibility — that would take a new entrant years to build. The ecosystem strategy monetizes these existing assets rather than requiring greenfield capability creation.

**Reason 2:** The financial case is robust even in the downside scenario. A 5-year NPV of GEL 5.8M in the downside case and GEL 21.8M in the base case at a 10% discount rate makes this the only option with a quantifiable and defensible return on investment.

**Reason 3:** Options 1 and 2 accelerate PSP's strategic vulnerability. Optimizing traditional pharmacy operations does not address platform disruption. Deepening aggregator partnerships transfers customer relationship ownership to Wolt and Glovo, making PSP structurally dependent on platforms it cannot control.

**Condition that would change the recommendation:** If PSP's data infrastructure audit reveals that customer data quality is insufficient to support personalization within 6 months, the team would recommend deferring the AI recommendation engine to Month 12 and extending the data governance phase, while continuing with the MVP platform, partnership activation, and content engine as planned.

---

## 5. Recommended Business Model

### 5.1 Value Proposition

For PSP's 1.9 million loyalty customers, the ecosystem delivers personalized skincare guidance, trusted dermatologist and influencer content, and seamless recommendation-to-purchase journeys — replacing the generic, transactional pharmacy experience with an ongoing wellness relationship. For dermatologists and influencers, the platform provides a credible, pharmacy-backed channel to reach Georgian consumers with high purchase intent. For skincare and wellness brands, PSP's ecosystem offers a targeted, data-informed advertising and partnership channel with measurable conversion.

### 5.2 Operating Model Changes

| Function | Current state | Target state | Change required |
|---|---|---|---|
| Digital Product | Basic app with product browsing and loyalty tracking | AI-powered skincare profiling, recommendation engine, and advisor booking | Hire Digital Product Manager; integrate API-based recommendation engine in H2 |
| CRM and Loyalty | Point-based loyalty scheme with generic campaigns | Behavioral segmentation, personalized campaigns, AI-triggered re-engagement | Hire CRM/Data Analyst; rebuild campaign logic around behavioral triggers |
| Marketing and Partnerships | Promotional campaigns with influencer product placements | Structured dermatologist and influencer ecosystem with content calendar and performance tracking | Hire Content/Partnerships Coordinator; establish recurring content agreements |
| Data and IT | Siloed transaction and loyalty data | Unified customer profile with skincare data, behavioral data, consent records, and purchase history | Establish data governance framework in Month 1; appoint Head of Data and AI |
| Healthcare Partnerships | Ad hoc medical advisor relationships | Structured dermatologist partnership program with content, appointment, and escalation protocols | Medical Partnerships Manager to govern dermatologist roster and oversight protocols |
| Governance | No AI governance structure | PSP AI Governance and Ecosystem Oversight Committee with defined decision rights and review cadence | Appoint CDO; establish oversight committee by Month 2 |

### 5.3 Revenue Model

The ecosystem generates revenue through five streams:

1. **Basket size uplift from AI cross-sell:** AI recommendation engine increases average skincare basket size by 10–20%. Applied to GEL 51.3M annual skincare revenue base (171,000 wellness buyers × GEL 25/month × 12), this generates GEL 2.7M incremental revenue in Year 2, growing to GEL 6.5M by Year 5.

2. **Retention improvement:** A 5% reduction in churn among the wellness customer segment generates GEL 1.5M in Year 2, growing to GEL 4.5M by Year 5 as personalization quality improves.

3. **Sponsored brand campaigns:** 3–6 skincare and wellness brand partners pay GEL 50,000–100,000 annually for targeted campaigns within the ecosystem. Revenue grows from GEL 200K in Year 2 to GEL 800K by Year 5.

4. **Online advisor appointments:** Dermatologist appointments booked through the platform at GEL 30 per appointment generate GEL 150K in Year 2, growing to GEL 700K by Year 5.

5. **Premium wellness subscriptions (H3):** 2,000–4,000 subscribers at GEL 150 per year generate GEL 300K–600K annually from Year 4 onward.

**Total incremental revenue:** GEL 0 (Year 1) → GEL 4.55M (Year 2) → GEL 7.3M (Year 3) → GEL 10.3M (Year 4) → GEL 13.1M (Year 5).

### 5.4 Data and AI Infrastructure Requirements

Before any AI deployment, PSP must establish: a unified customer profile combining loyalty transaction data, skincare preference data, app behavioral data, and purchase history; a consent management framework compliant with Georgian personal data protection law; defined data ownership and access protocols across Digital, CRM, Marketing, and Legal functions; and an API integration layer capable of connecting the recommendation engine to the existing loyalty and e-commerce infrastructure. This data governance layer is the critical dependency for all H2 AI initiatives and must be operational by Month 3.

---

## 6. 18-Month Transformation Roadmap

| # | Initiative | Horizon | Owner function | Budget (GEL) | Start | End | Dependency | Success metric | Risk |
|---|---|---|---|---|---|---|---|---|---|
| 01 | Data governance and customer data readiness | H1 | IT / Data / CRM | 15,000 | M1 | M3 | None | Unified customer profile, consent framework, and data ownership policy approved | Data quality worse than expected |
| 02 | MVP platform and ecosystem launch | H1 | Digital Product / IT | 60,000 | M1 | M4 | 01 | MVP launched with skincare profile, recommendation flow, and PSP integration | Development delays |
| 03 | Platform launch campaign | H1 | Marketing | 20,000 | M3 | M4 | 02 | Launch campaign executed; initial user acquisition tracked | Low initial uptake |
| 04 | Change management programme | H1 | HR / Transformation Office | 40,000 | M1 | M18 | None | Internal teams trained; governance meetings active; adoption barriers tracked | Internal resistance |
| 05 | Dermatologist and nutritionist partnership activation | H1 | Marketing / Partnerships | 130,000 | M2 | M6 | None | Partnerships launched with recurring content participation | Partner availability |
| 06 | Content production and skincare education engine | H1 | Marketing / Content Team | 60,000 | M2 | M6 | 05 | Monthly content engine active | Content quality inconsistency |
| 07 | Loyalty and engagement incentive pilot | H1 | CRM / Loyalty Team | 100,000 | M3 | M6 | 01, 02 | Loyalty campaigns launched; engagement and repeat usage tracked | Low campaign response |
| 08 | AI recommendation engine integration | H2 | IT / Data / Digital Product | 20,000 | M7 | M10 | 01, 02 | Personalized recommendation engine active | API integration complexity |
| 09 | Online skincare advisor appointment service | H2 | Digital Product / Partnerships | 10,000 | M7 | M12 | 02, 05 | Advisor booking functionality launched | Low advisor uptake |
| 10 | Advanced personalization and customer segmentation | H2 | CRM / Data / Marketing | 15,000 | M9 | M14 | 01, 07, 08 | Personalized customer segmentation active | Insufficient behavioral data |
| 11 | Sponsored brand and partner campaign model | H2 | Marketing / Commercial Partnerships | 10,000 | M10 | M16 | 06, 08, 10 | First sponsored campaigns launched | Brand partner reluctance |
| 12 | Ecosystem performance dashboard | H2 | Data / Finance / Digital Product | 10,000 | M12 | M18 | 07, 08, 10 | KPI dashboard active | Data integration complexity |
| 13 | AI skin-analysis expansion (H3 option) | H3 | Digital Product / IT / Medical | 50,000+ | Post-M18 | — | 08, 10, 12 | Expansion business case prepared | Only if H1+H2 thresholds met |
| 14 | Premium wellness ecosystem services (H3 option) | H3 | Commercial / Strategy | 30,000+ | Post-M18 | — | 09, 11, 12 | Premium service model evaluated | Advisor ecosystem maturity |
| 15 | Broader preventive health expansion (H3 option) | H3 | Strategy / Medical Partnerships | 100,000+ | Post-M18 | — | 12, 13, 14 | Preventive health roadmap prepared | Regulatory complexity |

**H1 one-time total (initiatives 01–07):** GEL 425,000
**H1 full cost including training, legal, contingency:** GEL 506,000
**H2 one-time total (initiatives 08–12):** GEL 65,000
**Annual operating cost (Year 1 onward):** GEL 572,000/year
**H3:** Uncommitted strategic options — not included in 18-month investment commitment
**Total 5-year cost of ownership:** GEL 3,366,000

**Sequencing rationale:** Data governance (01) must precede all AI initiatives. MVP platform (02) must precede loyalty pilot (07) and advisor service (09). Partnership activation (05) must precede content engine (06) and advisor service (09). AI recommendation engine (08) must precede segmentation (10) and sponsored campaigns (11). No H2 initiative begins before Month 7. No H3 initiative is committed until H2 adoption is independently verified.

---

## 7. ROI Model and Financial Case

### 7.1 Investment Summary

| Year | Capital expenditure (GEL) | Operating expenditure (GEL) | Total investment (GEL) |
|---|---|---|---|
| Year 1 | 506,000 | 572,000 | 1,078,000 |
| Year 2 | — | 572,000 | 572,000 |
| Year 3 | — | 572,000 | 572,000 |
| Year 4 | — | 572,000 | 572,000 |
| Year 5 | — | 572,000 | 572,000 |
| **Total** | **506,000** | **2,860,000** | **3,366,000** |

### 7.2 Benefit Realisation

| Year | Benefit category | Annual benefit (GEL) | Cumulative benefit (GEL) |
|---|---|---|---|
| Year 1 | Build phase — no revenue | 0 | 0 |
| Year 2 | Basket uplift 2.7M + Retention 1.5M + Campaigns 200K + Advisor 150K | 4,550,000 | 4,550,000 |
| Year 3 | Basket uplift 4.1M + Retention 2.5M + Campaigns 400K + Advisor 300K | 7,300,000 | 11,850,000 |
| Year 4 | Basket uplift 5.4M + Retention 3.5M + Campaigns 600K + Advisor 500K + Subscriptions 300K | 10,300,000 | 22,150,000 |
| Year 5 | Basket uplift 6.5M + Retention 4.5M + Campaigns 800K + Advisor 700K + Subscriptions 600K | 13,100,000 | 35,250,000 |

### 7.3 Three Scenario Analysis

| Metric | Downside | Base case | Upside |
|---|---|---|---|
| Key differentiating assumption | Ecosystem adoption rate | Ecosystem adoption rate | Ecosystem adoption rate |
| Assumption value | 30% of base projections | 100% of base projections | 150% of base projections |
| Year 1 net cash flow | (GEL 1,078,000) | (GEL 1,078,000) | (GEL 1,078,000) |
| Year 2 net cash flow | GEL 322,000 | GEL 3,978,000 | GEL 5,967,000 |
| Year 3 net cash flow | GEL 1,618,000 | GEL 6,728,000 | GEL 10,092,000 |
| Year 4 net cash flow | GEL 2,518,000 | GEL 9,728,000 | GEL 14,592,000 |
| Year 5 net cash flow | GEL 3,358,000 | GEL 12,528,000 | GEL 18,792,000 |
| Cumulative cash flow Year 5 | GEL 6,758,000 | GEL 31,884,000 | GEL 49,365,000 |
| Payback period | ~Year 3 | ~16 months | ~Year 1 |
| 5-year NPV (10%) | ~GEL 5,800,000 | GEL 21,782,766 | ~GEL 33,500,000 |
| IRR | ~85% | ~320% | ~450%+ |

### 7.4 Assumptions Log

| Assumption | Value used | Basis | Source |
|---|---|---|---|
| A1 — PSP 2021 revenue | GEL 745M | Verified | bm.ge / PSP annual report 2021 |
| A2 — Loyalty cardholders | 1.9M | Verified | bm.ge market report 2021 |
| A3 — Active app user rate | 15% of cardholders = 285,000 | Industry benchmark | McKinsey Digital Loyalty Report |
| A4 — Wellness category penetration | 60% of app users = 171,000 | Internal estimate | — |
| A5 — Monthly skincare spend per customer | GEL 25 | Estimate | Georgian consumer market; Geostat |
| A6 — AI basket uplift rate | 10–20% on GEL 51.3M base | Industry benchmark | McKinsey AI personalization impact studies |
| A7 — Churn reduction from personalization | 5% of wellness segment | Industry benchmark | Bain & Company customer retention research |
| A8 — Sponsored brand partner fee | GEL 50,000–100,000 per partner | Internal estimate | — |
| A9 — Advisor appointment fee | GEL 30 per appointment | Internal estimate | — |
| A10 — Georgian average salary | GEL 2,045/month | Verified | Geostat National Statistics Office 2023 |
| A11 — Digital role salary premium | 1.5–2.2× average | Industry estimate | HR market data |
| A12 — Discount rate | 10% | Standard | Emerging market digital project benchmark |
| A13 — USD/GEL exchange rate | 2.7 | Verified | National Bank of Georgia |

### 7.5 Sensitivity Table

| Assumption tested | Base value | Stressed value | Impact on payback period |
|---|---|---|---|
| Ecosystem adoption rate | 100% | 30% | Payback moves from 16 months to ~Year 3 |
| Monthly skincare spend per customer | GEL 25 | GEL 20 (−20%) | Year 2 revenue falls ~GEL 910K; payback extends ~2 months |
| Annual operating cost | GEL 572,000 | GEL 686,400 (+20%) | Year 2 net falls GEL 114K; payback extends ~1 month |
| AI basket uplift rate | 10–20% | 5% | Year 2 basket revenue halves to GEL 1.35M; payback extends ~3 months |

---

## 8. Risk Register

| Risk | Likelihood | Impact | Mitigation | Residual risk |
|---|---|---|---|---|
| Low ecosystem adoption | Medium | High | Phased rollout; influencer activation from Day 1; A/B testing from Month 3 | Medium |
| Low trust in AI recommendations | Medium | High | AI paired with licensed dermatologist oversight; human override protocols documented and tested | Low–Medium |
| Competitive imitation by GPC or Aversi | High | Medium | First-mover loyalty data advantage; personalization depth; dermatologist partnership exclusivity | Medium |
| Data privacy breach or PDPA non-compliance | Low | Very High | Georgian data protection compliance from Month 1; consent framework before any data collection | Low |
| Partnership failure — dermatologist or influencer withdraws | Low–Medium | Medium | Multiple partner agreements; contractual minimum participation terms | Low |
| Change management failure — internal resistance | Medium | Medium | Phased training programme; governance workshops from Month 4; CDO sponsorship | Low–Medium |
| Data quality insufficient for AI deployment | Medium | High | Data audit in Month 1 before any AI commitment; governance prerequisite enforced | Medium |

---

## 9. Change Management Plan

**Budget:** GEL 40,000 (7.9% of one-time transformation cost of GEL 506,000)
**Industry benchmark:** 15–20% of project cost. Budget is justified by moderate scope — no retrenchments, no restructuring, primarily upskilling existing staff and establishing new digital workflows.
**Owner function:** HR / Transformation Office / Chief Digital Officer
**Timeline:** Months 1–18

| Phase | Months | Key activities |
|---|---|---|
| Phase 1: Stakeholder analysis and communication | Months 1–3 | Executive alignment; governance communication; internal awareness campaigns; CDO appointment announcement |
| Phase 2: Training and capability building | Months 3–6 | AI literacy training for all staff; CRM and ecosystem workflow training; governance workshops; human override protocol training |
| Phase 3: Pilot adoption and feedback | Months 6–12 | MVP rollout support; adoption monitoring; employee feedback collection; adoption barrier resolution within 30 days |
| Phase 4: Scale and embedding | Months 12–18 | Governance integration into routine operations; KPI-based performance monitoring; quarterly governance review activation |

---

## 10. Governance Plan

**Oversight body name:** PSP AI Governance and Ecosystem Oversight Committee
**Executive sponsor:** Chief Digital Officer (CDO)

| Function | Role title | Decision authority |
|---|---|---|
| Digital and Technology | Chief Digital Officer | Final authority on AI deployment approval |
| Legal and Compliance | Head of Legal / Compliance Officer | Regulatory and data protection approval |
| Medical Partnerships | Medical Partnerships Manager | Approval for medical-related AI workflows |
| CRM and Customer Data | CRM/Loyalty Director | Customer data governance approval |
| IT and Data | Head of Data and AI | Technical model governance and monitoring |
| Marketing and Partnerships | Marketing Director | Creator ecosystem and customer engagement oversight |
| Executive Management | CEO or Executive Sponsor | Final escalation authority |

**Decision rights:**

| Decision type | Approval required before | Quorum |
|---|---|---|
| Deployment of any high-risk AI use case | Public release or customer activation | CDO + Legal + Medical + Data |
| Changes to model thresholds affecting recommendations | Production deployment | Minimum 4 committee members |
| Response to model failure or adverse outcome | Public response or system reactivation | Executive Sponsor + Legal + Data lead |
| Deployment of AI skin-analysis functionality | Any pilot or launch activity | Full committee |

**Review cadence:** Quarterly routine | Monthly KPI | Within 48 hours for adverse outcomes | Immediate for regulatory enquiries

**Human override protocols:**

Use case 1 — AI Skin-Analysis (H3): Trigger: AI identifies possible severe skin condition, allergic reaction, or prescription-linked recommendation. Override authority: Licensed dermatologist partner. Maximum review time: 24 hours. Default if exceeded: recommendation blocked.

Use case 2 — AI Recommendation Engine: Trigger: Customer complaint regarding incorrect or harmful skincare recommendation. Override authority: Medical Partnerships Manager. Maximum review time: 48 hours. Default if exceeded: recommendation category temporarily disabled for affected segment.

Use case 3 — AI Retention and Segmentation: Trigger: Customer requests explanation or removal from AI-driven profiling. Override authority: CRM/Loyalty Director. Maximum review time: 72 hours. Default if exceeded: customer removed from AI-personalized targeting campaigns.

**EU AI Act classification summary:**

| AI use case | Risk tier |
|---|---|
| AI skincare recommendation engine | Limited risk |
| AI customer segmentation and loyalty targeting | Limited risk |
| AI cross-sell and basket recommendation | Minimal risk |
| AI chatbot and onboarding assistant | Limited risk |
| AI advisor appointment matching | Limited risk |
| AI skin-analysis functionality (H3) | High risk |
| AI retention and churn prediction | Limited risk |

**Georgian data protection law obligations:** All AI use cases processing personal, behavioral, or health-related data must comply with Georgian Personal Data Protection Law. Obligations: informed consent before data collection; transparency disclosure that recommendations are AI-generated; right of erasure upon request; data minimization principle; appointment of a data protection responsible person before any AI system goes live; breach reporting to Personal Data Protection Service of Georgia within 72 hours.

**Escalation path:** Step 1 — escalate to CDO. Step 2 — joint review with Legal and Executive Management. Step 3 (final) — CEO / Executive Committee. Maximum time to resolution: 7 business days.

---

## 11. Responsible AI Assessment

| Use case | Bias or fairness risk | Transparency obligation | Accountability structure |
|---|---|---|---|
| AI skincare recommendation engine | Recommendation bias toward higher-margin products; underrepresentation of customers with limited purchase history | Users must be informed recommendations are AI-generated; dermatologist review available on request | Medical Partnerships Manager reviews recommendation logic quarterly; CDO approves threshold changes |
| AI-driven loyalty and retention campaigns | Segmentation may disadvantage lower-income customers who interact less with digital channels | Customers must be able to opt out of AI-driven profiling; targeting criteria explanation available on request | CRM/Loyalty Director reviews campaign segmentation monthly; Legal approves consent framework |
| AI chatbot and onboarding assistant | Response quality may vary by language register; Georgian-language accuracy must be tested before deployment | Users must know they are interacting with AI; human escalation path clearly signposted | Digital Product Manager monitors chatbot accuracy weekly; human advisor escalation available at any point |

---

## 12. AI Tool Disclosure Appendix

| Tool used | Sections where used | How outputs were verified |
|---|---|---|
| Claude (Anthropic) | Research synthesis, financial model structuring, slide content drafting, governance framework drafting | All financial figures verified against PSP annual reports (bm.ge), Geostat salary data, and National Bank of Georgia exchange rates. Strategic frameworks verified against Rogers, Christensen, and Porter source texts. All AI-drafted content reviewed and edited by team members before inclusion. |
