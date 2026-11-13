---
name: challenge-me
description: "Stress-tests any document in outputs/ against the four product risks, the evidence behind it and the baseline findings. Use when the participant types /challenge-me or asks for a critique, red team or devil's advocate review of their work."
---

# Challenge me (any time, 5 minutes)

## Goal
Find the assumption most likely to sink the work, before someone else does.

## Steps
1. Ask which file in `outputs/` to challenge, or take the most recently changed one.
2. Read it. Then give exactly three challenges, strongest first:
   - one on value or viability,
   - one on evidence: where does it sit on the Evidence Pyramid, and is it an opinion, a hypothesis or validated?
   - one on AI specifically (is AI needed, how will it fail, how will we know it is good?).
3. For each, name the framework you are using and ask one question the participant must answer. Do not answer it for them.
4. If the document proposes a build, add a fourth challenge from the Strategic Decision Filter.
5. Ask which challenge is fatal, fixable or wrong. Record their answers.
6. If they fix something, update the original file.

## Output
Append to the challenged file:

```
## Challenges ([date])
| Challenge | Fatal, fixable or wrong | What we changed |
```

## Constraints
Be direct but fair. Challenge the work, never the person.

---
Part of the Prodloop AI Prod Partner by Tai Ajayi. Credit: [prodloop.co](https://prodloop.co).
