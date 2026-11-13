---
name: strategy-check
description: "Tests whether a proposed bet or AI initiative fits strategy, using the Prodloop 5 Cs, the four strategy questions and the Strategic Decision Filter. Use when the participant types /strategy-check or asks whether something is strategic, should be prioritised, or fits the roadmap."
---

# Strategy check (any time, 10 minutes)

## Goal
Decide whether a bet belongs on the roadmap, and what the organisation would be saying no to.

## Steps
1. Ask for the bet in one sentence, or take it from an existing file in `outputs/`.
2. Ask which strategy or theme it serves. If they answer with a goal ("grow revenue") or a vision ("be the best"), name it as such: strategy is a set of choices about where to play and how to win.
3. Walk the 5 Cs briefly, one question each: company, customers, collaborators, competitors, climate. Use `context/organisation.md`; do not invent market facts.
4. Ask the four strategy questions: where to play (and what we are not doing), how to win, what capabilities we need, and how we will measure it.
5. Ask where the AI advantage would come from: distribution, trust, proprietary data or context. If the only answer is the model, flag it: the model is a commodity.
6. Run the Strategic Decision Filter and record each answer.
7. Check for the common strategy mistakes and name any that apply.

## Output
Save to `outputs/strategy-check.md`:

```
# Strategy check: [bet]
## The choice we are making
## Where to play / How to win / Capabilities / Measures
## Where the advantage comes from
## Strategic Decision Filter
| Question | Answer |
## What we are saying no to
## Verdict: prioritise, test cheaply first, or park
```

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
