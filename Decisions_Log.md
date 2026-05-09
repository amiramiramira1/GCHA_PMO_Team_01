# Decisions Log — GCHA Project

---

## Decision 1: CEO Acceleration Request — AI Model Training (Berlin)

**Date:** April 18, 2026
**Trigger:** CEO requests 1-week compression of Berlin Critical Path task

**Options Considered:**
1. Crashing (Berlin overtime)
2. Fast-Tracking (Bangalore starts at 80% AI completion)

**Decision:** Crashing — Authorize overtime for the existing Berlin team

**Justification:** We chose Crashing over Fast-Tracking because authorizing
overtime for the existing Berlin team avoids the rework risk of starting
Bangalore's UI on an incomplete AI model. Per Brooks's Law, adding new
developers at this stage would increase communication overhead and likely
delay the task further, so only existing team members will work overtime.

---

## Decision 2: Resource Leveling — Bangalore Over-Allocation Fix

**Date:** April 18, 2026
**Trigger:** Team Member C (Lead Planner, Bangalore) was over-allocated with
BAN-001 and BAN-002 overlapping in the same weeks, exceeding 40h/week capacity.

**Options Considered:**
1. Keep original dates and accept over-allocation
2. Apply Resource Leveling by shifting the task with more float

**Decision:** Resource Leveling Applied — Dates adjusted to eliminate over-allocation

**Changes Made:**
- BAN-002 (Mobile UI Integration): moved start date from April 8 → April 22
- BAN-001 (Mobile UI Design): moved start date from April 22 → May 20
- CAI-003 (Final Security Audit): moved start date from May 6 → June 3
  *(because CAI-003 is blocked by BAN-002, which now finishes later)*

**Justification:** BAN-001 and BAN-002 were overlapping, placing Team Member C
over capacity. Resource Leveling was applied by shifting BAN-001 to start after
BAN-002 finishes, eliminating the double 40h workload. CAI-003 was adjusted
accordingly to respect its dependency on BAN-002 completion.

---

## Decision 3: Resource Leveling — Cairo Over-Allocation Fix

**Date:** April 18, 2026
**Trigger:** Team Member B (Risk Officer, Cairo) had CAI-001 starting too early,
creating a potential overlap with other Cairo tasks.

**Options Considered:**
1. Keep original start date (April 8)
2. Shift CAI-001 start date to respect team capacity

**Decision:** Resource Leveling Applied — CAI-001 start date shifted

**Changes Made:**
- CAI-001 (Database Schema Setup): moved start date from April 8 → April 17

**Justification:** Shifting CAI-001 to April 17 removes the over-allocation risk
for Team Member B and aligns the Cairo workload within the 40h/week limit.
The task has sufficient float to absorb this shift without impacting the
Critical Path.

---

## Decision 4: Resource Leveling — Berlin Over-Allocation Fix

**Date:** April 18, 2026
**Trigger:** Team Member A (Site Coordinator, Berlin) had BER-002 and BER-003
overlapping with BER-001, exceeding weekly capacity.

**Options Considered:**
1. Keep original dates and accept over-allocation
2. Apply Resource Leveling by shifting tasks with available float

**Decision:** Resource Leveling Applied — BER-002 and BER-003 dates shifted

**Changes Made:**
- BER-002 (AI Model Validation): moved start date from April 17 → April 24
- BER-003 (AI Training Data): moved start date from April 28 → May 5

**Justification:** BER-002 was overlapping with BER-001, placing Team Member A
over the 40h/week limit. Resource Leveling was applied by moving BER-002 to
start after BER-001 finishes on April 23, and BER-003 was shifted accordingly
to maintain sequential logic. Both tasks had sufficient float to absorb the
shift without affecting the Critical Path delivery date.

---
## Conflict Resolution — Documentation Standard

**Date:** 26 April 2026

**Participants:**
- Berlin Lead (ِAmira Alfred )
- Cairo Lead (Habiba Ashraf)
- Mediator / PM (Enas Osama)

---

### Conflict Description
There was a disagreement between the Berlin and Cairo leads regarding the documentation format.
Berlin preferred a technically detailed format, while Cairo required a more readable format for compliance and audits.

---

### Core Needs
- Berlin Lead: Technical accuracy for developers
- Cairo Lead: Readability for audits

---

### Leadership Style
Facilitator

---

### Final Decision
A hybrid documentation format will be used:
- Technical section (Berlin format)
- Summary section (Cairo format)

---

### Rationale
This decision balances technical precision with compliance needs and allows the project to move forward.

## Decision Log: The Berlin AI Pivot
---
## Chapter 8 | Date: May 10, 2026 | Decision-Maker: Habiba Ashraf(London)
---

### The Situation

Berlin's AI module currently has a CPI of 0.50, meaning the team is spending $2 for every $1 of delivered value. Approximately $2,000,000 has already been spent while only $1,000,000 of actual value has been produced.

The remaining AI work was originally estimated at $500,000 internally. However, based on the current CPI performance, the projected actual cost to complete internally is approximately $1,000,000.

An external Health-AI vendor has offered to complete the AI diagnostic module for a fixed-price contract of $600,000 with significantly lower execution risk.

---

### Options Considered

| Option | Description | Projected Cost to Complete |
|--------|-------------|----------------------------|
| A: Continue Internal | Berlin team continues with current approach | ~$1,000,000 |
| B: Outsource to Vendor | External Health-AI firm completes the module | $600,000 |
| C: Descope | Remove AI module from Phase 1 entirely | $0 |

---

### Decision: OPTION B — Outsource to External Vendor

**Reasoning:**

The project team has decided to outsource the Berlin AI module to the external Health-AI vendor for a fixed price of $600,000. Based on the current CPI of 0.50, continuing internal development would likely cost approximately $1,000,000 with a high probability of additional schedule delays and performance issues.

Option B reduces execution risk, improves delivery confidence, and saves approximately $400,000 compared to continuing with the current internal team structure. The selected vendor has previous experience delivering healthcare AI solutions successfully, making this the most reliable corrective action for the project recovery strategy.

---

### Why the $2M Already Spent Does NOT Factor Into This Decision

**The Sunk Cost Principle:**

The $2,000,000 already spent on the Berlin AI initiative is considered a sunk cost. This money has already been spent and cannot be recovered regardless of which decision is made next.

The project team intentionally excluded the sunk cost from the decision-making process because professional project management focuses on future cost, future value, and future risk — not past spending.

Wrong reasoning (Sunk Cost Trap):

> "We already spent $2M, so we must continue internally."

Correct professional reasoning:

> "The $2M is already gone. The only relevant question is which option provides the best outcome moving forward."

Option A would require approximately $1,000,000 more with high delivery risk.

Option B requires $600,000 with lower risk and a higher probability of successful completion.

Therefore, Option B provides the best forward-looking business value.

---

### Impact on Project Baseline

- ETC revised: Internal ~$1,000,000 → Vendor $600,000
- Estimated savings from pivot: ~$400,000
- Revised EAC:
  - Original EAC: $14,670,000
  - Savings from Vendor Pivot: −$400,000
  - Revised EAC: $14,270,000

- Berlin RAG Status:
  - Previous Status: 🔴 RED
  - Updated Status: 🟡 AMBER (Vendor onboarding and transition phase)

- Knowledge Transfer Period:
  - Estimated duration: 2 weeks
  - Estimated overlap cost: ~$30,000

---

### Tuckman Note

This pivot decision may create a temporary Storming-stage disruption within the Berlin team as responsibilities transition to the external vendor. The PM must communicate the decision professionally and respectfully, acknowledging the effort already contributed by the Berlin team while redirecting key specialists toward higher-priority core diagnostic modules.
