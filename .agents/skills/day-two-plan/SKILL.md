---
name: day-two-plan
description: "Runs the Module 6 exercise that plans how an AI feature is run after launch: monitoring, re-testing, feedback, cost and rollback. Use when the participant types /day-two-plan or asks how to operate, monitor or own an AI product after launch."
---

# Day-2 plan (Module 6, 10 minutes)

## Goal
A plan for looking after the product once it is live, so launch is the start, not the finish.

## Before you start
Read `outputs/04-ai-prd.md`, `outputs/05-golden-set.md` and `outputs/06-failure-table.md`.

## Steps
Walk the Day-2 checklist one item at a time and ask who owns it and how:
1. Monitoring: which user metrics and which AI-quality metrics, and where they are watched. Choose user metrics with HEART (happiness, engagement, adoption, retention, task success) and test each one: if it moves, do we know what to do? Drop vanity metrics.
2. Golden set re-run: on which changes, run by whom.
3. Feedback: how corrections and complaints reach the test set.
4. Cost: the ceiling per user and per successful outcome, and who is alerted.
5. Rollback: how to get back to a safe state, and whether it has been rehearsed.
Then ask which team owns the product six months after launch. If the answer is "support" or "nobody", record it as the main risk.

## Output
Save to `outputs/07-day-two-plan.md`:

```
# Day-2 plan
| Item | What we do | Owner |
## Two scorecards
User metrics: / AI-quality metrics:
## Owner six months after launch
```

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
