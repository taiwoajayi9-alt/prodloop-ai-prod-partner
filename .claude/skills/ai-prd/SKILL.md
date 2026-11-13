---
name: ai-prd
description: "Runs the Module 4 workshop exercise that drafts an AI product requirements document, version one, from the opportunity brief. Use when the participant types /ai-prd or is defining an AI product, writing the model's job, data needs, behaviour rules or success thresholds."
---

# AI PRD, version one (Module 4, 25 minutes)

## Goal
A one-page AI product requirements document that engineering and QA can challenge.

## Before you start
Read `outputs/03-opportunity-brief.md`. If it is missing, ask for the problem and outcome first.

## Steps
1. Write the model's job in one sentence with them: given [input], produce [output], for [whom], and never [what it must not do]. Most teams forget the "never"; insist on it.
2. List the data and context it needs. For each source ask: who owns it, is it current, are we allowed to use it, is it in a state the model can use? Unknowns are findings; mark them.
3. Walk the context pyramid. Ask what domain knowledge (entities, definitions, rules) the model must be given. This is the layer most teams skip.
4. Ask for three things it must always do and three it must never do. Ask how each could be tested; reword any that cannot.
5. Ask what it should do when it is unsure.
6. Draft success thresholds for quality, cost per outcome and speed. Leave a number blank if they cannot defend it. Thresholds are completed in Module 5.
7. Run the Strategic Decision Filter: does this support the current theme, move the goal metric, justify the bet, and can it be tested cheaply first? Record any "no".

## Output
Save to `outputs/04-ai-prd.md` using the eight sections in `context/frameworks.md` (AI PRD on one page), followed by a short **Strategic fit** section with the filter results. Sections 6 to 8 may say "to complete in Module 5".

## Constraints
Do not choose a model or vendor for them. Model choice follows the use case and the evaluation evidence.

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
