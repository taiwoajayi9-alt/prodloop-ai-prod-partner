---
name: golden-set
description: "Runs the Module 5 exercise that writes a golden set of test cases with accepted answers for an AI feature. Use when the participant types /golden-set or wants to write evaluation test cases, edge cases or adversarial cases for an AI product."
---

# Golden set (Module 5, 15 minutes)

## Goal
Ten test cases with agreed good answers that define what good looks like for the feature.

## Before you start
Read `outputs/04-ai-prd.md`. The model's job and the must and never rules drive the cases.

## Steps
1. Ask for five normal cases: what most users ask, most days. Each needs an input and the answer the group would accept.
2. Ask for three edge cases: ambiguous, incomplete, mixed-language, unusual. Suggest categories, not the cases themselves, if they are stuck.
3. Ask for two adversarial cases: attempts to mislead it or make it break a "never" rule.
4. For every case, ask what answer they would accept. Where the group disagrees, record both views and mark it DISAGREE. These disagreements are requirements nobody had written down; point that out.
5. Check every "never" rule from the PRD has at least one case testing it.

## Output
Save to `outputs/05-golden-set.md`:

```
# Golden set
| # | Type | Input (synthetic) | Accepted answer | Tests rule | Agreed? |
## Disagreements to resolve
## Rules with no test yet
```

## Constraints
All inputs must be synthetic. Twenty or more cases is the target for real use; ten is the workshop size.

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
