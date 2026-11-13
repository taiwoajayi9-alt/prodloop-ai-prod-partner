---
name: failure-table
description: "Runs the Module 5 exercise that fills a failure table for an AI feature and chooses a human-in-the-loop mode and success thresholds. Use when the participant types /failure-table or is planning for AI failure, risk, rollback or human oversight."
---

# Failure table and human in the loop (Module 5, 10 minutes)

## Goal
The two worst ways the feature could fail, planned for before building, and a clear rule for when a person checks it.

## Before you start
Read `outputs/04-ai-prd.md` and `outputs/05-golden-set.md`.

## Steps
1. Ask: imagine it has already failed badly in front of a client. What happened? Collect two or three answers, then ask them to pick the two worst.
2. For each, fill the failure table: failure mode, trigger, consequence (who is hurt: customer, client, regulator, brand), early warning, mitigation.
3. Ask them to choose a human-in-the-loop mode: approves every output, reviews exceptions, or audits samples. Remind them to start at mode 1 unless evidence says otherwise.
4. Return to the success thresholds in the PRD. Ask them to fill in the numbers they can now defend.
5. Update section 6 to 8 of `outputs/04-ai-prd.md` with the mode, the failure plan and a pointer to the golden set.

## Output
Save to `outputs/06-failure-table.md`:

```
# Failure table
| Failure mode | Trigger | Consequence | Early warning | Mitigation |
## Human-in-the-loop mode and why
## Who can stop the system
## Thresholds agreed
```

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
