# Project Basalt — Economics

This document defines how value enters, accumulates within, and exits the community. It is binding on all members and amendable per §7 of [GOVERNANCE.md](GOVERNANCE.md). Where this document conflicts with the operating agreement of the Community LLC (or its jurisdictional equivalent), the legal entity governs and this document is updated to match.

## 1. Legal Container: The Community LLC

Project Basalt's land, infrastructure, and treasury are held by a single legal entity — referred to here as the **Community LLC**. The actual form depends on jurisdiction:

- **Bosnia and Herzegovina (Alpha Site, Drinić):** d.o.o. (limited liability company) is the working assumption. A *zadruga* (cooperative) is being evaluated for Phase 2 once member count justifies the overhead.
- **Future sites:** Each site is held by a local subsidiary owned by the parent Community LLC, to contain liability and comply with local land-ownership rules.

Members do not own the land directly. Members own **shares in the Community LLC**, and the LLC owns the land and assets. This is what makes membership portable: shares can be valued, transferred, or bought back without partitioning physical property.

## 2. Two Sources of Ownership: Capital and Sweat

Shares in the Community LLC are issued against two contribution types, tracked on a single cap table:

| Contribution | Issued Against | Tracked By |
|---|---|---|
| **Capital Stake** | Cash contributed to the treasury or earmarked for assets | Bank-verified deposits |
| **Sweat Equity** | Verified labor hours on community work | Sweat-equity ledger |

A member can be all-cash, all-sweat, or any mix. The cap table records both contribution histories per member, and the resulting share count.

### 2.1 Initial valuation (Phase 0–1)
- **Cash:** €1 contributed = 1 unit of share-value.
- **Sweat:** 1 verified hour of community labor = €15 of share-value (Phase 0–1 rate).

The sweat rate is a *governance variable*, not a market wage. It is set low relative to skilled remote-work rates because it represents ownership accrual, not compensation. Members are expected to earn living costs from external work.

### 2.2 Rate review
The sweat rate is reviewed annually by the Finance & Legal Circle and adjusted by consent of the General Circle. Adjustments are not retroactive — past hours are valued at the rate in force when they were logged.

### 2.3 Skill differentials
The base rate applies to all hours, regardless of task. Skilled work (electrical, plumbing, structural, legal drafting, accounting) earns a **1.5× multiplier** *only when the task requires a certified or demonstrably qualified contributor* and the work would otherwise need to be hired out. The multiplier is approved by the relevant Circle Lead before the work begins, not after. We pay the multiplier for scarcity, not for credentials in the abstract.

## 3. The Sweat-Equity Ledger

### 3.1 Logging
Every member logs hours within 7 days of the work. Each entry contains:
- Date, start time, duration.
- Circle and project.
- Task description (one or two sentences).
- Witness or output reference (a photo, a commit hash, a signed-off task ID).

Late entries (>7 days) are accepted only with Circle Lead approval and at 0.75× rate, to disincentivize backlog gaming.

### 3.2 Verification
Hours are verified at the end of each month by the Circle Lead (not the contributor). Disputes go to the General Circle. The verified ledger is committed to this repository under `/ledger/sweat/<yyyy-mm>.md`.

### 3.3 Conversion to shares
Shares are issued quarterly based on the verified ledger and verified cash contributions. Issuance is a Finance & Legal Circle decision recorded in the public log.

### 3.4 Caps
- **Maximum hours/week eligible for share issuance:** 40. Hours beyond this are recognized in the log but do not generate additional shares. This prevents burn-out arbitrage.
- **No member may hold more than 25% of outstanding shares** through Phase 2. This protects against founder dominance. The cap is reviewed at each phase transition.

## 4. The Shared Stake

A "share" in the Community LLC entitles the holder to:

1. **Governance participation** — per [GOVERNANCE.md](GOVERNANCE.md). Note that governance authority does *not* scale linearly with shareholding; consent is one-member-one-voice within Circles. Shares matter for Economics-class amendments (75% concurrence, §7 of governance) and for buyout valuation, not for day-to-day decisions.
2. **Pro-rata share of net assets on dissolution** of the LLC.
3. **Right to use community infrastructure** at member rates (defined per phase).
4. **Buyout right on exit**, per §5.

A share does **not** entitle the holder to:

- Exclusive use of any specific physical asset.
- Sale or transfer of shares to non-members without Community Circle vetting and General Circle consent.
- Profit distributions from operating surplus during Phases 0–2 (surplus is reinvested; see §6).

## 5. The Exit Clause (Social Pre-Nup)

The community is built on the assumption that **leaving is normal**. A member may exit voluntarily at any time, or be exited involuntarily under §5.3 of [GOVERNANCE.md](GOVERNANCE.md). The exit mechanics are identical in either case; only the trigger differs.

### 5.1 What the exiting member is entitled to

**(a) Buyout of shares** at the share's *book value* on the exit date.

Book value = (Net assets of Community LLC) ÷ (Outstanding shares).

Net assets are computed from the most recent quarterly statement, adjusted for known material events. The Finance & Legal Circle prepares the calculation; the exiting member may, at their own cost, retain an independent accountant to review.

**(b) Recovery of physical improvements** that are personal property.

Improvements made to a member's *private dwelling* (e.g., interior fittings they paid for) are personal property and may be removed if removal does not damage the structure, or sold to the community at depreciated cost. Improvements made to *common infrastructure* are not removable; they were contributed to the LLC and are already reflected in book value.

### 5.2 What protects the community's liquidity

A naive buyout right would allow a 25% shareholder to drain the treasury overnight. The following constraints apply:

**Payout cap per quarter.** Total exit payouts in any quarter cannot exceed **10% of the treasury's liquid balance** (cash and cash equivalents) at the start of that quarter. If multiple exits occur, payouts are pro-rated.

**Holdback for sweat-heavy exits.** If more than 50% of the exiting member's stake came from sweat equity, **30% of the buyout is held back for 12 months** as a quality-assurance reserve. The holdback is released in full unless the Infrastructure or Community Circle, by consent, identifies remediable defects in the member's work; in that case the holdback funds the remediation, with any balance returned.

**Installment option.** Where a lump-sum payout would breach the quarterly cap, the LLC pays in equal quarterly installments over up to 8 quarters, with simple interest at the higher of (i) the host-jurisdiction policy rate or (ii) 3%, accruing on the unpaid balance.

**No payout in distress.** If the LLC's liquid treasury falls below 90 days of operating expenses (as projected in the most recent budget), all exit payouts pause until the threshold is restored. Members exiting during distress are placed in a queue, paid in order of exit date as the threshold is recovered.

### 5.3 What protects the exiting member

**No clawback of past contributions.** The community cannot retroactively reduce the share count of an exiting member. Past contributions are crystallized at issuance.

**Right to inspection.** Within 30 days of notice, the exiting member receives a full accounting of how their buyout was calculated, with line-item access to the relevant ledgers.

**Independent valuation on dispute.** If the exiting member disputes the book-value calculation, an independent accountant (mutually selected, cost split 50/50) prepares a binding valuation.

**Reputational neutrality.** The community does not publish or share the reason for any voluntary exit. Involuntary exits under §5.3 of governance are noted in the public log with the *facts of the decision*, not commentary on the member.

### 5.4 Notice
- **Voluntary exit:** 60 days written notice. Member retains member rights and obligations during the notice period.
- **Involuntary exit:** Notice per §5.3 of governance.
- **Death or incapacity:** Buyout proceeds to the member's designated beneficiary or estate. Each member files a beneficiary designation on admission and may update it at any time.

## 6. Treasury & Surplus Policy

### 6.1 Sources of community income
- Member contributions (cash and sweat, per §2).
- Operating surplus from any community-run revenue activity (e.g., a guesthouse, agricultural sales, services to outside parties).
- Grants and donations (Finance & Legal Circle accepts or declines per a published policy on conflicts and strings-attached funding).

### 6.2 Reserves
The treasury maintains:
- **Operating reserve:** ≥ 6 months of projected operating expenses, in liquid form.
- **Capital reserve:** earmarked funds for the next phase's MVI projects.
- **Exit reserve:** ≥ the larger of (i) one expected annual exit's payout, or (ii) 5% of total share book value.

### 6.3 No distributions through Phase 2
No profit distributions to shareholders during Phases 0–2. Surplus is reinvested in infrastructure or added to reserves. This is non-negotiable through MVI; member income comes from external work, not from the LLC.

### 6.4 Phase 3 distributions
Once the autonomy phase begins and an internal economy operates, distributions become possible. Distribution policy is drafted by the Finance & Legal Circle and adopted by consent of the General Circle, subject to the 75% concurrence rule for Economics-class amendments.

## 7. Phase Roadmap

The phase roadmap is the project's resource plan. Each phase has gating criteria; we do not advance until they are met.

### Phase 0 — Digital Cohort
**Substrate:** Discord, GitHub, video calls.
**Goal:** Assemble the founding cohort (target 8–15 members), ratify v1.0 of the OS (this repo), open the Community LLC, fund the initial €2,000 treasury.
**Activities:** Vetting, OS authorship, fundraising plan for Phase 1, site reconnaissance.
**Gating to Phase 1:**
- LLC formed with at least 5 members on the cap table.
- Treasury ≥ €2,000.
- This OS ratified by initial General Circle.
- Pilot site under lease or hosting agreement.

### Phase 1 — The Pilot
**Substrate:** Drinić Alpha Site (or an alternate). Temporary residence: leased or hosted housing, generators or grid power, Starlink, hand tools.
**Goal:** Verify that the OS works under physical conditions. Bring 4–8 members on-site for a continuous test of governance, labor logging, and conflict resolution.
**Activities:** Onboarding the first physical cohort, running every Circle through real decisions, logging real sweat hours, drafting MVI specifications.
**Gating to Phase 2:**
- ≥ 90 continuous days of on-site operation.
- All three operational Circles have run at least one completed decision cycle each month.
- MVI plan approved with budget and timeline.
- Capital secured for at least 60% of MVI budget.

### Phase 2 — Minimum Viable Infrastructure (MVI)
**Substrate:** Owned shelter (modest, weather-tight, 4-season), owned power (PV + storage + backup), owned water (well or spring + storage + treatment), owned connectivity (Starlink redundancy), owned sanitation.
**Goal:** Member can live full-time on-site without relying on external utilities for survival, only for convenience or surge capacity.
**Activities:** Construction, certification, transition off rentals, expansion of cohort to 10–20 full-time members.
**Gating to Phase 3:**
- ≥ 80% of full-time members housed in community-owned shelter.
- Energy autonomy ≥ 60% on annual basis.
- Water autonomy ≥ 80% on annual basis.
- Operating reserve ≥ 12 months.
- A demonstrated internal-services market (members trading time on-platform).

### Phase 3 — Autonomy
**Substrate:** Off-grid power baseline, food production at meaningful scale, internal labor and credit market, optional internal unit of account.
**Goal:** External income becomes optional rather than necessary for sustenance. Members can choose to work externally, internally, or on the commons.
**Activities:** Food systems, light manufacturing or trades, internal currency or credit ledger, second-site planning.
**No gating beyond.** Phase 3 is open-ended; the project's purpose is to operate well in this state, not to advance to a Phase 4.

---

## 8. Auditability

The Finance & Legal Circle maintains, in this repository:

- `/ledger/cap-table.md` — current share holdings.
- `/ledger/treasury/<yyyy-mm>.md` — monthly statement.
- `/ledger/sweat/<yyyy-mm>.md` — verified sweat hours.
- `/ledger/exits/<yyyy>.md` — exit records, redacted as required.

Once the treasury exceeds €50,000 in any 12-month period, an annual third-party audit is mandatory and is published to members.

---

*See also: [MANIFESTO.md](MANIFESTO.md), [GOVERNANCE.md](GOVERNANCE.md).*
