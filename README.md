# Prodloop AI Prod Partner

**Created by Tai Ajayi, Prodloop. [prodloop.co](https://prodloop.co)**

Your partner for the Prodloop AI-native product operating model sessions, or for your own product work. Each workshop exercise has its own command. The partner asks you questions, pushes back on weak answers and saves your work as you go.

## Set up (five minutes, before Day 1)

Download this repository (Code, then Download ZIP) and unzip it somewhere you can find it, or clone it. Then pick your tool.

| Tool | How to start |
|---|---|
| **Google Antigravity** | Open the folder as your workspace. The commands load from `.agents/skills`. |
| **OpenAI Codex** (CLI, app or IDE extension) | Open or `cd` into the folder. Codex reads `AGENTS.md` and `.agents/skills`; type `$` or `/skills` to pick a command. |
| **Claude Code** | Open or `cd` into the folder and run `claude`. It reads `CLAUDE.md` and `.claude/skills`. |
| **Claude app or ChatGPT** | Follow `chat/README.md` to set the partner up as a project. |

Then type `/partner-setup` (in Codex, `$partner-setup`). It interviews you and fills in `context/about-me.md`. If your organisation has context to share, fill in `context/organisation.md` too.

If a command does not appear, close and reopen the folder. Check that your file browser shows hidden dot-folders.

## Commands

### Product sessions (Day 1 and Day 2)

| Module | Command | What it does | Saves to |
|---|---|---|---|
| Before Day 1 | `/partner-setup` | Interviews you to set up your context | `context/about-me.md` |
| 1. The honest baseline | `/honest-map` | The Honest Map | `outputs/01-honest-map.md` |
| 2. The operating model | `/feature-to-problem` | Rewrites a feature request as a problem with an outcome | `outputs/02-feature-to-problem.md` |
| 3. Choosing AI problems | `/opportunity-brief` | Opportunities, three filters, lowest rung, test and kill criterion | `outputs/03-opportunity-brief.md` |
| 4. Defining AI products | `/ai-prd` | AI product requirements document, version one | `outputs/04-ai-prd.md` |
| 5. Evaluation and trust | `/golden-set` | Ten test cases with accepted answers | `outputs/05-golden-set.md` |
| 5. Evaluation and trust | `/failure-table` | Your two worst failures, and how a person stays in the loop | `outputs/06-failure-table.md` |
| 6. Operating AI-native | `/day-two-plan` | How the product is run after launch | `outputs/07-day-two-plan.md` |
| 6. Operating AI-native | `/roadmap-90` | 90-day roadmap and your 30-day commitment | `outputs/08-roadmap-90.md` |

### Design session

| Part | Command | What it does | Saves to |
|---|---|---|---|
| 1. The shift | `/interaction-ladder` | Places your feature on the interaction ladder | `outputs/design-1-ladder.md` |
| 2. Trust before the first answer | `/first-ten-seconds` | Introduction, starter suggestions and the out-of-scope message | `outputs/design-2-first-ten-seconds.md` |
| 3. When it is wrong | `/hard-screens` | The unsure, wrong and handed-over screens | `outputs/design-3-hard-screens.md` |
| 5. Review and commit | `/design-review` | Runs the ten-question AI design review | `outputs/design-4-review.md` |

### Any time

| Command | What it does |
|---|---|
| `/challenge-me` | Stress-tests any document in `outputs/` against the four product risks and the evidence behind it |
| `/strategy-check` | Tests whether a bet fits strategy: 5 Cs, the four strategy questions and the Strategic Decision Filter |
| `/stakeholder-pitch` | Prepares you to win support for a decision with the Influence Stack, then plays the stakeholder |
| `/exec-update` | Turns metrics into a five-sentence SCIA update that leads with the insight |
| `/handover-pack` | Combines your working documents into one pack for the engineering sessions |

## The Prodloop way

The partner works the way Prodloop teaches product: as a leader, not an executor. It places your work on the **Discovery Loop**, grades your evidence on the **Evidence Pyramid**, pushes you down the **Validation Ladder** before anything is built, checks every build against the **Strategic Decision Filter**, and helps you win support with the **Influence Stack** and tell results with **SCIA**. Each exercise ends with a short Prodloop check: where the work sits, the weakest evidence behind it, and the next step.

## Rules for using it

- **Use your real work**, not textbook examples. The exercises are built for it.
- **Never paste real customer, candidate or client data.** Describe it, or use made-up examples.
- **Your judgement decides.** The partner suggests and challenges; you and your group choose.
- **Your files are yours.** Everything is saved in `outputs/` as plain text you can copy into any document.

## Licence and credit

The Prodloop AI Prod Partner was created by Tai Ajayi at Prodloop.

- **Free for 30 days** from the day you run `/partner-setup`.
- **After 30 days**, subscribe to the quarterly licence (billed every three months) via [Paystack](https://paystack.shop/pay/3quslifp98). After paying, open `context/about-me.md` and change **Licence status** to "licensed".
- **Teams and organisations:** contact Prodloop at [prodloop.co](https://prodloop.co).
- **Not for commercial reuse.** You may not resell, redistribute, or use it to deliver paid training or consulting without written permission.

Keep the credit **Prodloop AI Prod Partner by Tai Ajayi, prodloop.co**. Full terms are in `LICENSE.md`.
