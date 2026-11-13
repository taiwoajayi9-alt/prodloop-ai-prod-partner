---
name: hard-screens
description: "Runs Part 3 of the AI Design Practice session: designs the unsure, wrong and handed-over screens for an AI feature, and checks whether the system can detect each state. Use when the participant types /hard-screens or is designing error, uncertainty, correction or human handover states."
---

# Three hard screens (Design session, Part 3, 25 minutes)

## Goal
Descriptions of the three screens most design files leave out, ready to sketch, with the engineering requirements they imply.

## Before you start
Read `outputs/design-1-ladder.md` and `outputs/design-2-first-ten-seconds.md`.

## Steps
1. Screen 1, unsure: what does the feature show when it is not confident? Offer the five ways to show uncertainty and ask which fits.
2. Screen 2, wrong: the user spots a mistake. How do they correct it? Use the five ways to correct it. Ask whether correcting costs less effort than the mistake did.
3. Screen 3, handed over: a person takes over. Describe both sides: what the customer sees and is told, and what the staff member sees (the conversation, a summary, what the AI tried, why it handed over).
4. Ask how each correction is captured for the team.
5. Ask the engineers and QA in the group: can the system detect each state? Mark any it cannot. Each one is a requirement for engineering.
6. Write the user-facing copy for each screen with them, following the "instead of / write" principle: say what happened, do not blame the user, always give a next step.

## Output
Save to `outputs/design-3-hard-screens.md`:

```
# Three hard screens
## 1. Unsure: what the user sees / copy / how the system knows
## 2. Wrong: how the user corrects it / copy / how the correction is captured
## 3. Handed over: customer side / staff side / trigger
## States the system cannot yet detect (requirements for engineering)
```

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
