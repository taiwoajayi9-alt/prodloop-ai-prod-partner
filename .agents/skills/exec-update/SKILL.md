---
name: exec-update
description: "Turns metrics or pilot results into a five-sentence SCIA update that leads with the insight, using Prodloop's Making Numbers Speak. Use when the participant types /exec-update or needs to report results, write a status update, or explain what numbers mean to leadership."
---

# Executive update (any time, 10 minutes)

## Goal
An update a leader can act on, in five sentences or fewer.

## Steps
1. Ask for the numbers and the audience. Ask them to describe synthetic or aggregated figures only; no customer records.
2. Sort the metrics: keeping score (success, health, diagnosis) or telling the story. For an AI product, separate user metrics from AI-quality metrics and check whether one is rising while the other falls.
3. Test each metric: vanity or actionable? Drop vanity metrics or say why they stay.
4. Ask for the one headline number they would open with, and why.
5. Draft the update with SCIA: situation, complication, implication, action. Lead with the insight, use at most three numbers, and anticipate the first counter-argument.
6. Add one line on what the data cannot tell them yet.
7. Read it back as the audience would. Ask what decision it asks for.

## Output
Save to `outputs/update-[topic].md`:

```
# Update: [topic]
## The update (SCIA, five sentences or fewer)
## Headline number and why
## User metrics / AI-quality metrics
## What the data cannot tell us yet
## Likely counter-argument and our answer
```

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
