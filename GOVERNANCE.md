# Project Basalt — Governance

This document defines how decisions are made, by whom, and what happens when the system fails. It is the operating system of the community. It is binding on all members and amendable through the process described in §7.

## 1. Governance Model: Sociocracy

Project Basalt is governed by **Sociocracy** (also known as Dynamic Governance). The model has three load-bearing properties:

1. **Distributed authority.** Decisions are made in the smallest competent unit — a *Circle* — not by a central council or founder.
2. **Consent-based decisions.** A proposal passes when no member of the relevant Circle has a *reasoned, paramount objection*. It does not require enthusiasm from all; it requires the absence of substantive harm.
3. **Double-linking.** Every Circle is connected to its parent body by two members (a Lead and a Delegate), so information and decisions flow in both directions.

This model is chosen over majority voting because majority voting produces durable minorities, and over consensus because consensus is hostage to any single dissenter.

## 2. Initial Circles

Project Basalt begins with three operational Circles plus a coordinating General Circle. Circles can be created, merged, or dissolved by the General Circle by consent.

### 2.1 Infrastructure Circle
**Domain:** Power, water, sanitation, shelter, connectivity, tools, vehicles, on-site safety.
**Authority:** Spends within an approved infrastructure budget. Sets technical standards. Maintains the infrastructure ledger.
**Outputs:** Quarterly autonomy report (grid dependency %, water self-sufficiency %, uptime).

### 2.2 Finance & Legal Circle
**Domain:** Community LLC (or equivalent entity), accounting, tax compliance, contracts, treasury, sweat-equity ledger, share register, insurance.
**Authority:** Signs contracts within an approved spending limit. Maintains the cap table. Files statutory paperwork.
**Outputs:** Monthly financial statement. Annual audit (third-party once treasury exceeds €50,000).

### 2.3 Community Circle
**Domain:** Membership applications and vetting, onboarding, conflict resolution, member welfare, cultural norms, communication channels.
**Authority:** Recommends new members to the General Circle. Mediates conflicts. Initiates the Censure & Removal process (§5).
**Outputs:** Vetting decisions with rationale. Conflict-resolution log (anonymized).

### 2.4 General Circle
**Composition:** Lead + Delegate from each operational Circle.
**Domain:** Cross-Circle decisions, strategy, phase transitions, amendments to this document and the Manifesto and Economics docs.
**Authority:** All decisions not explicitly delegated to an operational Circle.

## 3. Roles Within Each Circle

Every Circle elects, by consent, four roles for fixed terms (default 6 months):

- **Lead** — convenes meetings, holds the agenda, represents the Circle to the General Circle.
- **Delegate** — second link to the General Circle; ensures the parent body hears the Circle's perspective.
- **Facilitator** — runs meetings; not the same as the Lead.
- **Secretary** — records decisions, maintains the Circle's section of the public log.

A single member may not hold more than two of these roles in the same Circle, and may not be Lead of more than one Circle simultaneously.

## 4. Decision Process: Consent vs. Consensus

| | Consensus | **Consent (used here)** |
|---|---|---|
| Question asked | "Do you agree?" | "Do you have a paramount objection?" |
| Threshold | All must approve | None must object on substantive grounds |
| Default | Block on disagreement | Proceed unless harm is shown |
| Failure mode | Tyranny of the most stubborn | Decisions move; preferences yield to objections |

### 4.1 The Consent Round

For any proposal in scope of a Circle:

1. **Present** — Proposer states the proposal and the problem it addresses.
2. **Clarify** — Members ask questions for understanding only. No reactions yet.
3. **React** — Members give brief reactions in turn. No debate.
4. **Amend** — Proposer may revise the proposal in light of reactions.
5. **Consent round** — Each member states one of: *Consent*, *Consent with concern* (recorded but not blocking), or *Objection*.
6. **Resolve objections** — An objection must be reasoned and paramount: it must articulate a concrete harm to the Circle's domain. The proposer and objector work together to integrate the objection. If unresolvable, the proposal is amended, withdrawn, or escalated to the General Circle.

### 4.2 What is *not* a valid objection
- "I don't like it."
- "I would do it differently."
- "I'm not sure."

These become *concerns* — recorded, revisited at the next review, but non-blocking.

### 4.3 Defaults & Time Limits
- Proposals not decided within two meetings are escalated to the General Circle.
- Any decision is reviewed at a pre-set date (default: 6 months). Decisions are presumed temporary; nothing is permanent without renewal.

## 5. Membership Lifecycle

### 5.1 Admission
1. **Application** — Submitted via GitHub issue or designated form.
2. **Screening** — Community Circle reviews against published criteria (skills, capital readiness, references, governance literacy).
3. **Trial period** — Minimum 90 days of active participation in the Digital Cohort or Pilot before Full Member status.
4. **Consent** — Full Member status requires consent of the General Circle.

### 5.2 Member Classes
- **Applicant** — In screening; no voting rights.
- **Trial Member** — Participates in one Circle; consents within that Circle only.
- **Full Member** — Holds shares in the Community LLC; participates in any Circle; consents in the General Circle.
- **Founding Member** — Full Member who joined during Phase 0 or Phase 1; identical rights, distinguished only on the cap table.

### 5.3 Censure & Removal
A member may be removed for:
- Material breach of governance (e.g., spending outside authority, falsifying labor logs).
- Conduct that endangers other members or the project (defined by the Community Circle's published code of conduct).
- Sustained non-participation (default threshold: zero contribution for 90 consecutive days without an approved leave of absence).

Removal procedure:
1. Community Circle issues a written notice with specific facts.
2. Member has 14 days to respond and 30 days to remedy if remediable.
3. If unresolved, the General Circle decides by consent (the affected member does not have a vote in their own removal but is heard).
4. Exit follows the Exit Clause in [ECONOMICS.md](ECONOMICS.md). Removal does not forfeit shares; it triggers buyout.

## 6. Override Protocol (Emergencies)

Sociocracy is slow by design. Some events cannot wait for a Consent Round.

### 6.1 What qualifies as an emergency
- **Life-safety** — injury, fire, structural failure, weather event.
- **Imminent asset loss** — flooding, theft in progress, critical system failure (water, heat in winter).
- **Time-critical legal exposure** — regulatory deadline within 24 hours, lawsuit served.

### 6.2 Authority during an emergency
The **Override Holder** for a given domain is, in order:
1. The Lead of the relevant Circle, if reachable.
2. Any Full Member physically on-site, if the Lead is not reachable within 15 minutes.
3. The General Circle Lead, if no on-site member is qualified.

The Override Holder may take any action and spend up to **€1,000** (Phase 1–2) or **0.5% of treasury** (Phase 3+), whichever is greater, without prior consent.

### 6.3 Post-emergency review (mandatory)
Within 72 hours of resolving an emergency, the Override Holder files a report covering:
- The triggering facts and time of decision.
- The action taken and funds spent.
- The expected vs. actual outcome.
- A recommendation: ratify, ratify-with-conditions, or rescind (where possible).

The relevant Circle reviews the report and decides by consent. **The Override Protocol cannot be used twice for the same category of event without an intervening governance review** — recurring "emergencies" indicate a missing system, not a need for permanent override authority.

### 6.4 Abuse of override
A finding that an Override Holder invoked the protocol in bad faith is automatic grounds for Censure under §5.3.

## 7. Amending This Document

This document, the Manifesto, and the Economics document are amended by consent of the General Circle, with the following constraints:

- **Notice:** Proposed changes are posted as a pull request at least 14 days before the decision meeting.
- **Quorum:** At least two-thirds of Full Members must be represented (in person or by recorded proxy) in the General Circle decision.
- **Supermajority floor for Economics changes:** Amendments to share allocation, exit clause, or sweat-equity rates require consent **and** affirmative concurrence from members holding at least 75% of outstanding shares. This protects minority capital.
- **Versioning:** All changes are tracked in git. The current version is whatever is on `main`.

## 8. Public Log

Every Circle maintains a public log in this repository (`/log/<circle>/<yyyy-mm>.md`) recording:
- Date and attendees.
- Decisions made (with the proposal text, objections raised, resolution).
- Action items and owners.
- Scheduled review dates.

Decisions not in the log are not decisions.

---

*See also: [MANIFESTO.md](MANIFESTO.md), [ECONOMICS.md](ECONOMICS.md).*
