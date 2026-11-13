# Frameworks used in the sessions

Use these to structure exercises and to challenge weak answers. Name the framework when you use it. Prodloop's own method is in `prodloop-way.md` and takes precedence where the two overlap.

## Three stages of AI maturity
- **AI-assisted:** AI added to the old way of working. Remove the tools and the work keeps its shape, only slower.
- **AI-accelerated:** at least one workflow or product redesigned around AI, but as an island.
- **AI-native:** AI carries real load. Problems chosen deliberately, quality measured, a team owns the behaviour.
- **The removal test:** if AI vanished tomorrow, would the shape of the work change, or only its speed?

## Executor and leader mindsets
Executor asks "can we build this?", "when can you deliver?", "can we add AI to this?". Leader asks "should we build this?", "what problem are we solving?", "should this be AI at all?".

## Feature teams and empowered teams (Marty Cagan, SVPG)
Feature teams are given features and judged on output. Empowered teams are given problems and judged on outcomes.

## Four product risks (Marty Cagan, SVPG)
- **Value:** will customers choose to use it? (product manager)
- **Usability:** can they work out how to use it, and when to trust it? (designer)
- **Feasibility:** can we build it, and will it behave reliably on real, messy inputs at a cost we can carry? (tech lead)
- **Viability:** does it work for the business: cost, regulators, privacy, brand when it is wrong? (product manager)

## Opinion, hypothesis, validated
An opinion is a starting point. A hypothesis is a testable statement that could be proved wrong. Validated means evidence gathered before engineering time is committed.

## Opportunity solution tree (Teresa Torres)
Outcome at the top. Customer opportunities (needs, pains, desires) beneath it. Several solutions per opportunity. A test for the riskiest assumption under each solution. AI appears at the solution level, never at the top.

## Three filters for a first AI bet
- **Constraint:** is it where the business or customer is actually held back?
- **Repetition:** is it high-volume and repetitive?
- **Reversibility:** is it safe to get wrong while we learn?

## The lowest rung that solves it
1. Rules and workflow. 2. Classic machine learning. 3. Small language model. 4. Large language model. 5. Agent. Start at the lowest rung that solves the problem.

## Validation ladder (riskiest to least risky)
6. Just build it and see. 5. MVP with a small group. 4. Wizard of Oz prototype. 3. Interview customers about the problem (best starting point). 2. Look at data for signals. 1. Internal validation.

## The model's job in one sentence
Given [input], produce [output], for [whom], and never [the thing it must not do].

## Context pyramid
1 Intent, 2 User, 3 Domain (usually skipped), 4 Rules, 5 Environment, 6 Exposition (what the model actually receives).

## AI PRD on one page
1 Problem and outcome. 2 The model's job. 3 Data and context. 4 Behaviour: must do, must never do, when unsure. 5 Success thresholds. 6 Human in the loop. 7 Failure plan. 8 Evaluation.

## Golden set
Inputs with an agreed good answer, written by people who know the domain. Normal, edge and adversarial cases. Re-run on every change to a prompt, model or data source.

## Two scorecards
User metrics and AI-quality metrics. If user metrics rise while AI quality falls, you are borrowing trust.

## Failure table (FTCEM)
Failure mode, Trigger, Consequence, Early warning, Mitigation.

## Three human-in-the-loop modes
1. Human approves every output. 2. Human reviews exceptions. 3. Human audits samples. Start at mode 1; move down only when evidence earns it.

## Day-2 checklist
Monitoring live. Golden set re-run on every change. Feedback routed into the test set. Cost alerts. Rollback rehearsed.

## Interaction ladder (design)
1 Invisible. 2 Suggestion. 3 Draft for review. 4 Guided conversation. 5 Open conversation or agent. A chat box fits when needs are hard to predict; a form or button fits when the task has known steps.

## Four states of every AI feature
Right, unsure, wrong, out of scope.

## Five ways to show uncertainty
Say it in plain words. Show the source. Offer alternatives. Ask a clarifying question. Decline and point to who can help.

## Five ways to correct it
Edit, retry, undo, dismiss, report.

## The AI design review
1 Is it clear this is AI? 2 Does the user know what it can and cannot do? 3 Is it on the lowest rung that solves the problem? 4 Is there a designed state for unsure? 5 Can the user correct a wrong answer cheaply? 6 Is the handover designed from both sides? 7 Can the user see where an answer came from? 8 Are corrections captured for the team? 9 Does it work on a slow connection and a small screen? 10 What happens when the model is unavailable?

## SCIA for updates
Situation, Complication, Implication, Action.
