---
name: handover-pack
description: "Combines the participant's working documents into one handover pack for the engineering sessions and the case study. Use when the participant types /handover-pack or asks to prepare their work for engineering."
---

# Handover pack (end of programme, 10 minutes)

## Goal
One document engineering can build from, with gaps clearly marked.

## Steps
1. Check which of these exist in `outputs/`: `03-opportunity-brief.md`, `04-ai-prd.md`, `05-golden-set.md`, `06-failure-table.md`, `07-day-two-plan.md`. List any that are missing and ask whether to continue without them.
2. Read them all. List contradictions between them, for example a threshold in the PRD that the golden set does not test, or a never rule with no failure plan.
3. Ask the participant to resolve each contradiction or mark it open.
4. If `context/case-study.md` is filled in, check the pack against its constraints and note any mismatch.
5. Assemble the pack.

## Output
Save to `outputs/09-handover-pack.md`:

```
# Handover pack
## Summary (SCIA: situation, complication, implication, action)
## 1. Opportunity brief
## 2. AI PRD
## 3. Golden set
## 4. Failure table and human in the loop
## 5. Day-2 plan
## Open questions for engineering
## Contradictions still open
```

## Constraints
Copy content faithfully. Do not improve or add requirements the participant did not agree.

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
