# Site Evaluation Rubric

This rubric converts a candidate Alpha Site from a feeling into a number. Every site Project Basalt seriously considers is scored on the same instrument, by at least two reviewers independently, and the resulting score plus narrative becomes the decision artifact recorded in the public log.

The rubric exists for three reasons:

1. **To make decisions defensible.** "We picked Drinić because it scored 71/100 vs. site B's 64" is a much stronger answer to a Trial Member's question than "we liked Drinić."
2. **To prevent home-team bias.** A parcel a founder owns or grew up near gets favorable treatment from the founder. The rubric is a small but real counterweight.
3. **To make pivots survivable.** If the Drinić visit produces a low score, Phase 0 doesn't collapse — the next-highest-scoring site becomes the candidate and the project continues.

## How to use

1. **Pre-fill from desk research** (cadastral records, satellite imagery, climate data, statute scans). Mark each line "(desk)" or "(visit)" depending on confidence.
2. **Two reviewers score independently** to a copy of the scoresheet. No conferring during scoring.
3. **Compare and reconcile.** Where reviewers disagree by ≥2 points on any criterion, discuss until consensus or document the disagreement.
4. **Apply dealbreakers.** Any criterion marked **D** (dealbreaker) at score 1 disqualifies the site regardless of total. This is intentional — some failures cannot be compensated by other strengths.
5. **Compute weighted total** (max 100). Record the score, the narrative summary, and the recommendation in `site/<site-name>-evaluation.md` in the repo.
6. **Compare across sites** in a single table once two or more sites have been scored.

A score above 70 is "proceed." 55–70 is "proceed with conditions" (the conditions are the criteria that scored 1–2). Below 55 is "look elsewhere."

These thresholds are calibrated, not absolute — re-baseline after the first three sites are scored.

---

## Categories and Weights

| Category | Weight | Notes |
|---|---|---|
| 1. Legal feasibility | **20** | If you can't legally own or build, nothing else matters. |
| 2. Physical site | **18** | The land itself: terrain, area, water, soil. |
| 3. Climate | **12** | Drives heating cost, growing season, infrastructure spec. |
| 4. Connectivity & utilities | **10** | Internet, grid proximity, mobile signal. |
| 5. Access & logistics | **12** | Roads, airports, hospitals, supply chain. |
| 6. Cost | **12** | Land, construction, cost of living. |
| 7. Community & social | **8** | Local fabric, language, receptiveness. |
| 8. Strategic fit | **8** | Visa, banking, EU adjacency, recruitment proximity. |
| **Total** | **100** | |

Within each category, each criterion is scored 1–5. The category score is the average of its criteria, multiplied by the category weight, then divided by 5.

---

## 1. Legal Feasibility (weight: 20)

### 1.1 Foreign ownership pathway **(D)**
Can a member who is a non-citizen of the host country acquire ownership (directly or via a domestic legal entity) without arbitrary administrative discretion?

| Score | Anchor |
|---|---|
| **1** | No pathway exists, or a pathway exists only at the discretion of a minister with no published criteria. **Dealbreaker.** |
| 2 | Pathway exists but requires reciprocity that excludes ≥2 of the cohort's likely recruitment markets. |
| 3 | Pathway exists for most EU citizens; non-EU members face the domestic-entity workaround. |
| 4 | Domestic-entity workaround is the standard, well-documented practice; lawyer confidence is high. |
| 5 | Direct foreign ownership permitted with no reciprocity test; or pathway is constitutionally guaranteed. |

### 1.2 Construction permittability **(D)**
Can a year-round residence be legally built on the parcel under current zoning, or via reclassification within 24 months?

| Score | Anchor |
|---|---|
| **1** | Site is in a no-build zone (protected, military, etc.) with no reclassification path. **Dealbreaker.** |
| 2 | Agricultural or forest land; reclassification requires >24 months and uncertain outcome. |
| 3 | Agricultural land; reclassification possible in 12–24 months with municipal cooperation. |
| 4 | Already construction-permitted or has farmstead exemption for the planned scale. |
| 5 | Construction land with active spatial plan supporting the project's intended use. |

### 1.3 Title clarity **(D)**
Are the cadastre and land-book records consistent and free of encumbrance, with no active disputes?

| Score | Anchor |
|---|---|
| **1** | Active title dispute, contested ownership, or unresolved restitution claim. **Dealbreaker.** |
| 2 | Significant inconsistencies between cadastre and land book; multiple recorded encumbrances. |
| 3 | Minor inconsistencies; one or two routine encumbrances (utility easements). |
| 4 | Records consistent; no encumbrances beyond standard. |
| 5 | Clean records, single registered owner (or known co-owners), no encumbrances. |

### 1.4 Permit pathway clarity
How predictable is the construction permit process — fees, timeline, document set?

| Score | Anchor |
|---|---|
| 1 | Process undefined or requires informal payments to progress. |
| 2 | Process defined but timeline highly variable (>24 months realistic). |
| 3 | Process defined; 12–18 month timeline; municipal officer responsive. |
| 4 | Process defined; 6–12 month timeline; documented fee schedule. |
| 5 | Standardized one-counter procedure; <6 months for small residence; published e-government track. |

### 1.5 Jurisdictional stability
How stable is the legal and political regime governing the parcel over a 10+ year horizon?

| Score | Anchor |
|---|---|
| **1** | Active conflict, secessionist movement with credible probability of constitutional change, or sanctions exposure. (Score 1 here is **D** if combined with score ≤2 on 1.1.) |
| 2 | Periodic constitutional or boundary tensions; foreign investor protections in flux. |
| 3 | Stable regime, occasional populist-policy turbulence affecting investors. |
| 4 | EU candidate or stable democracy; mature property law; treaty-protected investments. |
| 5 | EU member or equivalent; predictable enforcement; no foreseeable regime change. |

---

## 2. Physical Site (weight: 18)

### 2.1 Year-round vehicular access **(D)**
| Score | Anchor |
|---|---|
| **1** | No road; foot/animal access only; or seasonal blockage >2 months/year. **Dealbreaker.** |
| 2 | Track frequently impassable in winter or wet seasons. |
| 3 | Gravel road, occasionally requires 4×4 in winter or wet. |
| 4 | Gravel or paved road, passable in standard vehicle ≥95% of days. |
| 5 | Paved road to or near the parcel, no historical blockages. |

### 2.2 Water availability **(D)**
| Score | Anchor |
|---|---|
| **1** | No realistic water source on or near parcel; trucking water is the only option. **Dealbreaker.** |
| 2 | Drilling required at depth that exceeds plausible Phase-2 budget; no surface alternative. |
| 3 | Well drilling feasible at moderate depth; outcome uncertain (karst geology). |
| 4 | Spring on or adjacent to parcel; or municipal water available at reasonable connection cost. |
| 5 | Existing well in use; or year-round spring with proven flow rate. |

### 2.3 Acreage sufficient for Phase 2 build-out
| Score | Anchor |
|---|---|
| 1 | <0.5 ha; cannot accommodate planned 5-dwelling MVI plus shared infrastructure. |
| 2 | 0.5–1 ha; tight; constrains future growth. |
| 3 | 1–3 ha; sufficient for MVI plus modest shared and gardens. |
| 4 | 3–10 ha; ample for MVI plus food production at meaningful scale. |
| 5 | >10 ha; supports Phase 3 autonomy ambitions; potential second cluster. |

### 2.4 Solar exposure (annual)
| Score | Anchor |
|---|---|
| 1 | Heavily shaded or north-facing on steep slope; <2.5 kWh/m²/day annual mean. |
| 2 | Mixed exposure; 2.5–3.5 kWh/m²/day. |
| 3 | Reasonable south-facing exposure; 3.5–4.0 kWh/m²/day. |
| 4 | Strong south-facing exposure; 4.0–4.5 kWh/m²/day. |
| 5 | Excellent south or south-east exposure on open terrain; >4.5 kWh/m²/day. |

### 2.5 Soil and drainage
| Score | Anchor |
|---|---|
| 1 | Bedrock at surface, severely compromised drainage, or active erosion. |
| 2 | Thin soil over rock; foundation work expensive; drainage problems likely. |
| 3 | Mixed; foundation work routine; drainage adequate. |
| 4 | Good loam or clay-loam; drainage reliable; gardening feasible. |
| 5 | Deep, fertile soil; excellent drainage; visible plant productivity. |

### 2.6 Hazard exposure
Compound score for flood, landslide, wildfire, and severe-weather risk.

| Score | Anchor |
|---|---|
| **1** | Severe risk in at least one category (e.g., active landslide zone, frequent flooding). **Dealbreaker if uncorrectable.** |
| 2 | Notable risk in one category requiring expensive mitigation. |
| 3 | Moderate risk in one category, mitigatable through siting and design. |
| 4 | Low risk across categories; standard precautions suffice. |
| 5 | Minimal risk across all categories. |

---

## 3. Climate (weight: 12)

### 3.1 Winter severity (heating load)
| Score | Anchor |
|---|---|
| 1 | Mean January min < −15 °C; heating-degree-days >5,000 annually; 4+ months of snow cover. |
| 2 | Mean January min −10 to −15 °C; HDD 4,000–5,000; 3 months snow cover. |
| 3 | Mean January min −5 to −10 °C; HDD 3,000–4,000; 1–2 months snow cover. |
| 4 | Mean January min 0 to −5 °C; HDD 2,000–3,000; intermittent snow. |
| 5 | Mild winters; HDD <2,000; rare snow. |

### 3.2 Growing season
| Score | Anchor |
|---|---|
| 1 | <120 frost-free days; severely limits food production. |
| 2 | 120–150 frost-free days. |
| 3 | 150–180 frost-free days. |
| 4 | 180–210 frost-free days; supports diverse production. |
| 5 | >210 frost-free days; year-round production with cold-frame extension. |

### 3.3 Extreme weather frequency
| Score | Anchor |
|---|---|
| 1 | Multiple extreme events per year (flooding, ice storms, severe heat). |
| 2 | One extreme event most years. |
| 3 | Extreme events occasional (1 in 3–5 years). |
| 4 | Rare extreme events. |
| 5 | Climate notably benign; very rare extremes. |

### 3.4 Climate trend (10–30 year horizon)
| Score | Anchor |
|---|---|
| 1 | Region projected to become significantly less habitable (severe drought, wildfire) by 2050. |
| 2 | Notable adverse trend (drought stress, water scarcity). |
| 3 | Mild adverse trend but manageable with adaptation. |
| 4 | Stable or mildly favorable trend. |
| 5 | Region projected to become more habitable (longer growing season, ample water). |

---

## 4. Connectivity & Utilities (weight: 10)

### 4.1 Starlink / satellite connectivity feasibility
| Score | Anchor |
|---|---|
| 1 | Region not in Starlink coverage; no equivalent satellite option. |
| 2 | Coverage exists but obstructed view to sky from parcel; mitigation expensive. |
| 3 | Coverage exists; partial obstructions manageable. |
| 4 | Coverage exists; clear sky view from at least one good antenna location. |
| 5 | Coverage exists; multiple unobstructed antenna locations; redundant satellite options. |

### 4.2 Mobile signal / fallback
| Score | Anchor |
|---|---|
| 1 | No mobile signal at parcel from any operator. |
| 2 | Weak signal from one operator; voice-only. |
| 3 | Workable signal from one operator; data possible. |
| 4 | Multiple operators with workable signal; 4G data. |
| 5 | Strong 4G/5G from multiple operators. |

### 4.3 Grid power proximity
| Score | Anchor |
|---|---|
| 1 | Grid >2 km away; connection cost prohibitive; pure off-grid only. |
| 2 | Grid 500 m – 2 km; connection costs high (≥€10k). |
| 3 | Grid at parcel edge; connection straightforward but costly (€2–10k). |
| 4 | Grid available at low connection cost. |
| 5 | Grid already connected to existing structure on parcel. |

(*Note: A score of 1 here is not a dealbreaker — pure off-grid is on the project's stated trajectory. It increases Phase 1 capital cost.*)

### 4.4 Municipal water availability
| Score | Anchor |
|---|---|
| 1 | No municipal water within 1 km. |
| 2 | Available within 500 m – 1 km; high connection cost. |
| 3 | Available at parcel edge; routine connection cost. |
| 4 | Existing connection present and active. |
| 5 | Existing connection plus reliable Phase-1 backup option (well, spring). |

(*Same note as 4.3 — fully off-grid water is consistent with project goals; this metric measures *optionality*, not necessity.*)

---

## 5. Access & Logistics (weight: 12)

### 5.1 Distance to international airport
| Score | Anchor |
|---|---|
| 1 | >5 hours by road. |
| 2 | 3–5 hours. |
| 3 | 2–3 hours. |
| 4 | 1–2 hours. |
| 5 | <1 hour. |

### 5.2 Distance to a real town (groceries, hardware, fuel)
| Score | Anchor |
|---|---|
| 1 | >45 minutes by road. |
| 2 | 30–45 minutes. |
| 3 | 15–30 minutes. |
| 4 | 5–15 minutes. |
| 5 | Within 5 minutes. |

### 5.3 Distance to nearest hospital / emergency care
| Score | Anchor |
|---|---|
| **1** | >90 minutes; routine emergency response infeasible. (Mark **D** if combined with high hazard score.) |
| 2 | 60–90 minutes. |
| 3 | 30–60 minutes. |
| 4 | 15–30 minutes. |
| 5 | <15 minutes. |

### 5.4 Local construction labor and materials
| Score | Anchor |
|---|---|
| 1 | No local trades; all labor and materials must be imported from far away. |
| 2 | Limited local trades; materials sourced at moderate distance. |
| 3 | Working trades available; main materials within 30–60 minutes. |
| 4 | Strong local construction ecosystem; materials within 30 minutes. |
| 5 | Full ecosystem; specialized trades available; competitive pricing. |

---

## 6. Cost (weight: 12)

### 6.1 Land cost (per ha equivalent, if acquisition required)
Score against the cohort's realistic capital pool from [BUDGET.md](../BUDGET.md).

| Score | Anchor |
|---|---|
| 1 | Land cost would consume >50% of cohort's projected 5-year treasury. |
| 2 | 25–50%. |
| 3 | 10–25%. |
| 4 | <10%. |
| 5 | Land already owned by founders or leased indefinitely at nominal cost. |

### 6.2 Cost of living locally (monthly per member, food + housing baseline)
| Score | Anchor |
|---|---|
| 1 | >€1,500/month (Western European baseline). |
| 2 | €1,000–1,500. |
| 3 | €700–1,000. |
| 4 | €400–700. |
| 5 | <€400 (rural Eastern European baseline). |

### 6.3 Construction cost (€/m² for habitable build, local trades)
| Score | Anchor |
|---|---|
| 1 | >€2,000/m². |
| 2 | €1,500–2,000. |
| 3 | €1,000–1,500. |
| 4 | €600–1,000. |
| 5 | <€600 (DIY plus rural local labor in low-cost markets). |

### 6.4 Permit and statutory fees
| Score | Anchor |
|---|---|
| 1 | Cumulative formation + permit fees >€10,000. |
| 2 | €5,000–10,000. |
| 3 | €2,000–5,000. |
| 4 | €500–2,000. |
| 5 | <€500. |

---

## 7. Community & Social (weight: 8)

### 7.1 Local receptiveness to outsiders
| Score | Anchor |
|---|---|
| 1 | Active hostility to foreigners or non-locals; documented incidents. |
| 2 | Cool reception; closed social fabric; suspicion. |
| 3 | Neutral; outsiders tolerated, not embraced. |
| 4 | Welcoming; existing successful integration of non-locals nearby. |
| 5 | Culturally open; multiple expat or returnee households nearby; strong civic life. |

### 7.2 Existing village fabric
| Score | Anchor |
|---|---|
| 1 | Fully abandoned; zero year-round residents within 2 km. |
| 2 | Mostly seasonal; <5 year-round households within 2 km. |
| 3 | Mixed; 5–15 year-round households; basic services nearby. |
| 4 | Active small village; 15–50 households; school or shop locally. |
| 5 | Vibrant village or town; 50+ households; full local services. |

### 7.3 Language barrier for the cohort
| Score | Anchor |
|---|---|
| 1 | Local language has no relationship to languages the cohort speaks; English near-zero. |
| 2 | Difficult language; English limited to younger residents. |
| 3 | Manageable with effort; English in town center, not in hamlets. |
| 4 | One founder is native; English understood by most under 50. |
| 5 | Local language is one founder's native; English widely spoken. |

### 7.4 Proximity to peer projects
| Score | Anchor |
|---|---|
| 1 | No comparable intentional / digital community within 500 km. |
| 2 | One peer within 200–500 km. |
| 3 | One peer within 100–200 km. |
| 4 | Multiple peers within 100–200 km. |
| 5 | Active regional cluster of peer projects within 100 km. |

---

## 8. Strategic Fit (weight: 8)

### 8.1 Visa / residency pathway for foreign members
| Score | Anchor |
|---|---|
| 1 | No long-stay pathway; 90/180 Schengen-style limit applies and cannot be extended. |
| 2 | Long-stay pathway exists but is expensive or discretionary. |
| 3 | Standard residence permit available with predictable criteria; modest cost. |
| 4 | Multiple pathways including digital-nomad or investor visa; routine approval. |
| 5 | EU freedom-of-movement applies; or visa-free long-stay for most cohort markets. |

### 8.2 Banking access for foreign-owned entity
| Score | Anchor |
|---|---|
| 1 | Foreign-owned entities routinely refused or charged punitive fees by local banks. |
| 2 | One or two banks accept foreign-owned entities after long onboarding. |
| 3 | Several banks accept; onboarding routine but slow (4–8 weeks). |
| 4 | Many options; onboarding within 2–4 weeks. |
| 5 | Full SEPA-equivalent access; multiple competitive providers; instant onboarding paths. |

### 8.3 Distance from major remote-work hubs (recruitment proximity)
| Score | Anchor |
|---|---|
| 1 | >12 hours travel from any major remote-work concentration (Berlin, Lisbon, etc.). |
| 2 | 8–12 hours. |
| 3 | 4–8 hours. |
| 4 | 2–4 hours. |
| 5 | <2 hours; site is a credible weekend visit from a major hub. |

### 8.4 Multi-site fork potential
Does the OS make sense to fork to a *second* site of this type?

| Score | Anchor |
|---|---|
| 1 | Site is unique to founders' situation; no fork potential. |
| 2 | Some fork potential, but requires entirely different legal regime. |
| 3 | Fork plausible within same legal family. |
| 4 | Multiple comparable sites identifiable in the same region. |
| 5 | Region has dozens of plausible fork sites; OS is highly portable. |

---

## Decision Rules

After scoring:

1. **Apply dealbreakers.** Any criterion marked **(D)** scoring 1 disqualifies the site, regardless of total. Document the dealbreaker explicitly.
2. **Compute weighted total.** Each category score = (sum of criterion scores ÷ 5 × number of criteria) × (category weight ÷ category criterion count). Or simpler: average each category's criteria, multiply by weight, sum.
3. **Recommendation:**
   - Total ≥ 70 and no dealbreakers: **Proceed.**
   - Total 55–70 and no dealbreakers: **Proceed with conditions.** The conditions are the criteria scoring 1–2; each must have an explicit mitigation plan or budget allocation before the site is committed to.
   - Total < 55, or any dealbreaker: **Look elsewhere.** This is not "the site is bad" — it is "the site does not earn the cohort's commitment relative to plausible alternatives."

A site is *not* committed by the rubric alone. The rubric is an input to the General Circle's consent decision per [GOVERNANCE.md](../GOVERNANCE.md). It removes the worst forms of motivated reasoning; it does not replace judgment.

---

## Scoresheet Template

Duplicate the block below to `site/<site-name>-evaluation.md` for each candidate site. Two reviewers each fill a copy; reconcile in a third merged copy.

```
# Site Evaluation — <Site Name>

Reviewer: ____________
Date: ____________
Source mix: __% desk research, __% site visit
Confidence: low / medium / high

## 1. Legal Feasibility (weight 20)
1.1 Foreign ownership pathway (D): __ / 5 — [note]
1.2 Construction permittability (D): __ / 5 — [note]
1.3 Title clarity (D): __ / 5 — [note]
1.4 Permit pathway clarity: __ / 5 — [note]
1.5 Jurisdictional stability: __ / 5 — [note]
Category average: __ / 5  →  weighted: __ / 20

## 2. Physical Site (weight 18)
2.1 Year-round vehicular access (D): __ / 5
2.2 Water availability (D): __ / 5
2.3 Acreage sufficient: __ / 5
2.4 Solar exposure: __ / 5
2.5 Soil and drainage: __ / 5
2.6 Hazard exposure: __ / 5
Category average: __ / 5  →  weighted: __ / 18

## 3. Climate (weight 12)
3.1 Winter severity: __ / 5
3.2 Growing season: __ / 5
3.3 Extreme weather frequency: __ / 5
3.4 Climate trend: __ / 5
Category average: __ / 5  →  weighted: __ / 12

## 4. Connectivity & Utilities (weight 10)
4.1 Satellite connectivity: __ / 5
4.2 Mobile signal: __ / 5
4.3 Grid power proximity: __ / 5
4.4 Municipal water: __ / 5
Category average: __ / 5  →  weighted: __ / 10

## 5. Access & Logistics (weight 12)
5.1 International airport: __ / 5
5.2 Real town: __ / 5
5.3 Hospital: __ / 5
5.4 Local trades and materials: __ / 5
Category average: __ / 5  →  weighted: __ / 12

## 6. Cost (weight 12)
6.1 Land cost: __ / 5
6.2 Cost of living: __ / 5
6.3 Construction cost: __ / 5
6.4 Permit and statutory fees: __ / 5
Category average: __ / 5  →  weighted: __ / 12

## 7. Community & Social (weight 8)
7.1 Local receptiveness: __ / 5
7.2 Existing village fabric: __ / 5
7.3 Language barrier: __ / 5
7.4 Peer projects: __ / 5
Category average: __ / 5  →  weighted: __ / 8

## 8. Strategic Fit (weight 8)
8.1 Visa / residency: __ / 5
8.2 Banking access: __ / 5
8.3 Distance from remote-work hubs: __ / 5
8.4 Multi-site fork potential: __ / 5
Category average: __ / 5  →  weighted: __ / 8

## Total: __ / 100

Dealbreakers triggered: ____________
Lowest-scoring criteria (1–2): ____________
Mitigation feasibility for each: ____________

## Reviewer narrative (3–6 sentences)
What stood out positive:
What stood out negative:
Confidence interval on the total:

## Recommendation
☐ Proceed
☐ Proceed with conditions: ____________
☐ Look elsewhere
```

---

*See also: [site/drinic-dossier-template.md](drinic-dossier-template.md), [BUDGET.md](../BUDGET.md), [GOVERNANCE.md](../GOVERNANCE.md).*
