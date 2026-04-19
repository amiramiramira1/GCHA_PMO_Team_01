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
