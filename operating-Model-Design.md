# Operating Model v1 — PSP Beauty & Wellness Ecosystem Platform
**Section 5 of Final Project Report**
Team: Nana Danelia, Daviti Mtchedlishvili, Davit Kulua, Mariam Berekashvili
Recommended Strategic Option: AI-Enabled Personalized Digital Wellness Ecosystem

---

## Part 1. Process Redesign

### Selected Process: Skincare Recommendation-to-Purchase Journey

This is the process most transformed by the ecosystem strategy. Currently it is fragmented across offline store staff, social media discovery, and unconnected loyalty data. The ecosystem strategy fuses recommendation, personalization, and fulfillment into a single AI-mediated journey.

---

### Current State: The Process as It Operates Today

**Process name:** Customer skincare product recommendation and purchase

| Decision point | Who decides | Information used | Failure mode |
|---|---|---|---|
| 1. Product discovery | Customer (self-directed) or in-store pharmacist | Personal knowledge, shelf placement, marketing materials | Customer picks wrong product category; no personalization; high return/dissatisfaction rate |
| 2. Recommendation relevance | In-store skincare advisor or pharmacist | Visual skin assessment, verbal customer input, brand training | Advice is inconsistent across staff; no record of prior purchases or skin history |
| 3. Cross-sell / upsell | Cashier or store manager | Real-time basket contents only | Missed revenue; no linkage to loyalty data or AI-driven affinity scoring |
| 4. Loyalty reward application | CRM/Loyalty system (automated) + cashier | Loyalty card scan, purchase total | Loyalty points applied but not used to drive personalized re-engagement; no behavioral segmentation |

**Current process performance:**
- Average time from discovery to purchase decision: 15–25 minutes in-store; no structured digital journey exists
- Error rate / rework rate: High mismatch between purchased products and skin needs (estimated from industry benchmarks at 25–35% of first-time skincare buyers)
- Customer impact of current failure modes: Low repeat purchase rate in skincare/wellness category; customer exits ecosystem after single transaction; no data capture for future personalization

---

### Target State: The Redesigned Process

| Decision point | AI handles | Human handles | Escalation threshold |
|---|---|---|---|
| 1. Product discovery | AI surfaces personalized product sets based on skin profile, purchase history, and influencer/dermatologist content engagement | Influencer or dermatologist creates discovery content that feeds the AI training layer | Customer has zero prior data (first-time user with no profile): human skincare advisor completes onboarding intake via app chat |
| 2. Recommendation relevance | AI recommendation engine scores product-skin profile match using behavioral data, purchase history, and advisor input | Dermatologist partner reviews and approves AI recommendation logic for medical-grade skincare sub-categories | Customer query involves a prescription-linked product, a reported allergic reaction, or a condition flagged as requiring medical review (e.g. rosacea, eczema, post-procedure care) |
| 3. Cross-sell / upsell | AI generates basket expansion suggestions at checkout based on affinity model and category uplift logic | None required for standard cross-sell | Customer basket value exceeds GEL 200 and includes two or more new product categories simultaneously: loyalty manager reviews for retention campaign trigger |
| 4. Loyalty reward application | AI triggers personalized re-engagement campaigns based on purchase recency, frequency, and category affinity score | CRM team reviews campaign performance weekly and adjusts segmentation thresholds | Customer has not purchased in 60 days and was previously a top-quartile spender: manual outreach from loyalty team with bespoke offer |

**Target process performance:**
- Expected time from discovery to purchase decision: 3–7 minutes via app (digital journey); same-day for in-store with AI-assisted advisor tablet
- Expected error rate: Product-skin mismatch reduced to 8–12% (AI recommendation systems in comparable beauty platforms show 65–75% reduction in return rates — McKinsey personalization benchmark)
- Basis for estimates: McKinsey personalization benchmark (+8% repeat purchase, conservative calibration); AI recommendation engine basket uplift (+5%) as stated in team financial model (Slide 18)

---

### Automation Trap Check

| Check | Answer |
|---|---|
| Did we start from the desired outcome (right product, right customer, right moment) and work backwards? | Yes — the journey is designed around customer retention and repeat purchase, not around digitizing the current checkout flow |
| Did we eliminate steps that existed only because humans needed them? (e.g. manual cross-sell at cashier, inconsistent in-store advice) | Yes — cashier cross-sell and unstructured in-store advice are replaced by AI; only medically complex cases retain human judgment |
| Is the escalation threshold specific and named? | Yes — three thresholds named: (1) zero prior data triggers human onboarding, (2) prescription-linked or allergic-reaction queries trigger dermatologist review, (3) 60-day lapse for top-quartile spenders triggers manual outreach |

---

## Part 2. Team Structure

### Team Design

| Team name | Mandate (one sentence) | Dataset owned | Agile level | Reporting line |
|---|---|---|---|---|
| Digital Platform & AI Team | Build, maintain, and continuously improve the AI recommendation engine, customer data infrastructure, and app experience | Customer behavioral data, skin profile data, purchase history, recommendation accuracy logs | Full agile (2-week sprints, product owner embedded) | IT & Digital Director → Executive Management |
| Influencer & Advisor Partnerships Team | Recruit, manage, and activate dermatologist and influencer relationships to feed discovery content into the ecosystem | Creator engagement data, content performance data, referral attribution data | Kanban (campaign-driven, not sprint-based) | Marketing Director → Executive Management |
| Loyalty & CRM Team | Convert platform engagement into retention by managing personalized campaigns, loyalty tier logic, and churn prevention | Loyalty transaction data, recency-frequency-monetary scores, campaign response data | Hybrid (quarterly planning, weekly execution cycles) | CRM/Loyalty Director → Executive Management |
| Healthcare & Professional Partnerships Team | Ensure ecosystem credibility by onboarding and governing dermatologist contributors and managing medical-grade product recommendations | Dermatologist roster, prescription-adjacent product flags, medical content review logs | Project-based (not sprint-based) | Medical Partnerships Manager → Executive Management |
| Ecosystem Strategy & Governance Team | Own transformation roadmap, cross-functional coordination, investment decisions, and KPI accountability for ecosystem outcomes | Aggregated ecosystem performance dashboard, budget allocation data, initiative status | Quarterly OKR cadence | Executive Management (CEO/CDO level) |

---

### Single Most Important Structural Change

**Change:** PSP must appoint a dedicated Chief Digital Officer (CDO) or Head of Ecosystem with cross-functional authority over Digital, Marketing, CRM, and Partnerships — before AI deployment scales beyond the pilot phase.

**Reason it is a prerequisite:** The current governance structure (Slide 23) assigns ecosystem responsibilities to five separate functional owners with no single integrating authority. AI personalization requires real-time data sharing across all five functions. Without a single owner with authority to enforce data standards, integration timelines, and cross-team escalation decisions, the AI recommendation engine will be built on siloed datasets and the escalation thresholds defined in Part 1 will not be actioned consistently.

**H1 or H2 timeline:** H1 — must be in place before the pilot launch, not after.

**Estimated cost order of magnitude:** GEL 80,000–120,000 per year (senior hire or internal promotion with restructuring cost); non-capital, operating expenditure.

---

### Incentive Alignment

| Team | Current primary metric | New primary metric | Secondary metric added |
|---|---|---|---|
| Digital Platform & AI Team | Feature delivery velocity / system uptime | Recommendation acceptance rate (% of AI suggestions leading to purchase) | Skin profile completion rate (% of active users with full profile) |
| Influencer & Advisor Partnerships Team | Number of posts / reach / impressions | Referral-to-purchase conversion rate from creator-driven content | Dermatologist content engagement rate |
| Loyalty & CRM Team | Loyalty card enrollment count | 90-day repeat purchase rate among loyalty members | Churn rate reduction in top-quartile customer segment |
| Healthcare & Professional Partnerships Team | Number of dermatologist partners signed | Medical-grade recommendation approval turnaround time (target: under 48 hours) | Customer trust score (NPS for medically-recommended product purchases) |
| Ecosystem Strategy & Governance Team | Budget adherence / project on-time delivery | Ecosystem revenue contribution (% of total PSP revenue) | Customer lifetime value growth rate |

---

## Part 3. Roadmap Connection

| Operating model item | Horizon tag | Roadmap initiative it enables | Dependency relationship |
|---|---|---|---|
| Appoint CDO / Head of Ecosystem with cross-functional authority | H1 | All Phase 1 Foundation initiatives (Slide 16): digital platform strengthening, partnership expansion, loyalty capability improvement | Must precede all other items; no cross-functional AI integration can be governed without this role |
| Deploy customer skin profile onboarding flow in app (human-assisted for zero-data users) | H1 | Phase 1 — pilot ecosystem launch in skincare and wellness categories | Must precede AI recommendation engine deployment; AI needs minimum viable profile data to produce non-generic recommendations |
| Integrate loyalty transaction data with behavioral data layer (single customer view) | H1 | Phase 1 — improve recommendation and loyalty capabilities; Phase 2 — customer profiles and behavioral analytics | Must precede personalized re-engagement campaigns and AI churn prediction model |
| Activate dermatologist content review workflow and escalation protocol for prescription-adjacent products | H1 | Phase 1 — expand influencer and dermatologist partnerships; medical credibility for ecosystem | Must precede public-facing AI recommendations in medical-grade skincare subcategories |
| Deploy AI recommendation engine (product-skin profile matching, cross-sell logic) | H2 | Phase 2 — AI-powered recommendation systems; basket size uplift (+5%), repeat purchase uplift (+8%) per financial model | Requires H1 skin profile data, H1 single customer view, and H1 dermatologist review workflow to be operational |
| Launch personalized loyalty re-engagement campaigns (60-day lapse trigger, top-quartile segment) | H2 | Phase 2 — personalized skincare and wellness experiences; churn reduction (-10%) per financial model | Requires H1 single customer view and H2 AI recommendation engine to generate personalized offer logic |
| Introduce AI skin analysis (image-based) and advanced personalization | H2 | Phase 3 — AI skin analysis and advanced personalization; platform network effects | Requires H2 AI recommendation engine to be validated; requires sufficient skin profile dataset (minimum 12 months of H1/H2 data accumulation) |
| Expand ecosystem monetization (sponsored placements, creator-commerce revenue stream) | H2 | Phase 3 — expand ecosystem services and monetization; sponsored ecosystem revenue (+15%) per financial model | Requires H2 platform network effects to be demonstrable to brand partners; cannot be credibly sold without engagement metrics from H1–H2 phases |

---

## Quality Check

| Criterion | Status |
|---|---|
| Both current state and target state are documented for the process, not only the target | ✅ Current state table, performance metrics, and failure modes documented in full |
| Every team has a named mandate, a named dataset, and a named agile level | ✅ Five teams documented with all three fields |
| The single most important structural change is named and connected to a roadmap initiative | ✅ CDO appointment named, costed, tagged H1, and linked to all Phase 1 initiatives |
| Every metric change names the old metric and the new metric | ✅ Five teams, three metric columns each |
| Every operating model item is tagged H1 or H2 | ✅ Four H1 items, four H2 items, all linked to named roadmap initiatives |
| The escalation threshold is specific and named, not a category | ✅ Three thresholds named with specific conditions (zero data, prescription-linked/allergic reaction, 60-day lapse for top-quartile spenders) |

---

*Deliverable: operating_model_v1.md — prepared for Section 5 of the PSP Final Project Report*
*Source: PSP Beauty & Wellness Ecosystem Platform midterm deck (PSP_Wellness_4.pptx)*
