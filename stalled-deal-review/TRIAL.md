# Stalled-deal review: tried on its example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-09
- **Template version:** 0.1.0

This is a record of the second run of the capability template on its own invented example. The company, the deals, the people and the dates are invented, and no client data was used. It shows what the template produced once, on one set of inputs. It is not a test in any company's environment.

2026-11-09: after the run recorded here, step 1 of the instruction block was edited so that only an open deal whose stage is not on the list goes under "Not read", as the long procedure already said; read literally, the earlier wording would have put D-107 (stage "Closed lost") under "Not read". The run followed the intended reading. The output format was not changed, and the run was not repeated.

An earlier run the same day, by a different model, showed where the instructions left room to guess. The instructions, the output format and the example were revised, and the run recorded here was made on the revised instructions. What the earlier run found, and what was changed, is at the end.

The inputs were the invented example in `public/example.md`: the sales lead's facts and stages, the nine-row deal export, the five deal notes and the excerpt of the previous review. The model followed the fenced instruction block and the output format. This run was not blind: it was made by the same model session that revised the template, after it had read the example's earlier published output and the earlier run's record. Read it as a check that the revised rules can be followed to a complete output on this example, not as an independent reading.

## What came out

**STALLED-DEAL REVIEW: Monday 2 November 2026**

**For:** Sales lead. **From:** deal export of 2 November 2026, 9 rows; your stages (4, limits in days: Discovery 21, Demo 14, Proposal 21, Negotiation 14); notes for 5 deals; previous review of 26 October 2026.

**Coverage:** Rows read: 9 (5 open, 1 won and 3 lost between 27 October and 2 November 2026). Not read: none. Open at the last review and missing now, under Could not assess: D-099. Outcome: partial: D-099 was open at the review of 26 October and is not in this export.

**Open at this review:** D-101, D-102, D-103, D-104, D-105.

**Stalled deals: 3**

**D-101** · Account A · stalled at Proposal: the proposal was sent (note of 14 October); the record does not show the call in which the buyer went through it with us. Whose move: the buyer's (operations director): her finance team signs off anything over $20,000, then she books the review call.

- Why: next-step date passed on 22 October; in Proposal 28 days, over the 21-day limit.
- On the record: last activity 14 October (19 days before the review); note of 14 October: proposal sent at $26,400 a year; the operations director says finance signs off anything over $20,000 before she can book a review call, and she will let us know.
- Next step as recorded: Proposal review call, Account executive, 22 October 2026; waiting on the buyer, our check not set.
- Question to settle it, for the operations director: Has your finance team signed off the proposal, and when can we book the call to go through it?

**D-103** · Account C · stalled at Negotiation: payment terms are not agreed (the buyer wants 60 days against our standard 30; the other terms are agreed), and the order form has not been sent for signature. Whose move: a colleague's (finance director): whether to approve 60-day payment terms.

- Why: in Negotiation 21 days, over the 14-day limit.
- On the record: last activity 19 October (14 days before the review); note of 19 October: terms agreed except payment; the sales lead will send the revised order form once the finance director approves 60 days.
- Next step as recorded: Send revised order form, Sales lead, no date set; waiting on a colleague (finance director).
- Question to settle it, for the finance director: Will you approve 60-day payment terms for Account C, and by what date?

**D-104** · Account D · stalled at Discovery: unknown: the record does not show whether the buyer's problem, the person who decides or a target date is recorded. Whose move: unknown.

- Why: no next step; in Discovery 35 days, over the 21-day limit.
- On the record: last activity 2 October (31 days before the review); no notes.
- Next step as recorded: none.
- Question to settle it, for the account executive: For D-104, which of the buyer's problem, the person who decides and a target date have we recorded, and what is the next step and who owns it?

**Moving deals: 2**

- **D-102** · Demo · Demo with the plant manager, Solutions engineer, 5 November 2026.
- **D-105** · Proposal · Buyer to confirm budget after their board meeting, Account executive, 12 November 2026; waiting on the buyer, our check 12 November 2026.

**Promises with no date set:** looked and found none.

**Waiting on the buyer:**

- D-101: finance sign-off, then booking the review call (operations director, note of 14 October); recorded date: 22 October 2026; our check: check date not set.
- D-105: come back to us after their board meets "on the 10th" (operations VP, note of 27 October); recorded date: 12 November 2026; our check: 12 November 2026, Account executive.

**Waiting on a colleague:** D-103: whether to approve 60-day payment terms (finance director, note of 19 October); then: Send revised order form, Sales lead, no date set.

**Where the noes ended: 3 lost between 27 October and 2 November 2026**

Closed at Discovery:

- **D-109** · Account J · closed 27 October. Reason: "They need a mobile app for floor staff, which we don't offer." (ours, note of 27 October). Whose call: ours. What would reopen it: not recorded.

Closed at Demo:

- **D-106** · Account F · closed 28 October. Reason: "Not this year. The budget is going into a new press line." (plant manager, note of 28 October). Whose call: the buyer's. What would reopen it: "Ask me again in April." (plant manager, note of 28 October).

Stage not recorded:

- **D-107** · Account G · closed 30 October. Reason: No response (from the record, not the buyer's words). Whose call: unknown. What would reopen it: not recorded.

**Won between 27 October and 2 November 2026:** D-108, 29 October.

**At odds with the record:** D-106: the export's close reason says "Price"; the note of 28 October says "Not this year. The budget is going into a new press line."

**Gaps in the record:** D-104: which parts of the Discovery exit are met, and whose move it is. D-107: the stage it closed at, and whose call it was.

**Corrections to propose, for the sales lead or the deal's owner to make:** D-106: close_reason, now "Price", proposed "Not this year. The budget is going into a new press line.", from the note of 28 October.

Prepared from the deal export of 2 November 2026 and the notes supplied. Nothing has been sent, and no record has been changed.

## What was observed

- **Every required part was produced.** Header, coverage line, the "Open at this review" line, stalled deals with all five sub-lines each, moving deals, the three next-step lists, the lost deals by closing stage, the won deal and the three closing lists, with the closing sentence. Nothing in the inputs triggered a stop: all headers matched, no deal ID repeated, every open deal's stage was on the list, every stage had an exit and a limit, and every date was in one unambiguous form.
- **No fact beyond the inputs.** Every date, count and quotation traces to the export or a dated note. The day counts were checked by hand: 28, 21 and 35 days in stage, 19, 14 and 31 days quiet; D-102 (13 days in Demo, limit 14) and D-105 (7 days in Proposal) are under their limits.
- **The revised rules each decided a case the earlier run had to guess:** D-101 sits under "Waiting on the buyer" with its recorded date kept apart from a check date; D-103 sits under "Waiting on a colleague", so "Promises with no date set" is empty and says so; D-104's question goes to the Discovery stage's usual owner, the account executive; the period starts on 27 October, the day after the previous review; both quoted reasons are the reason sentences, not the whole note; the proposed correction for D-106 is the plant manager's words; and the gaps line holds only what the review writes as "unknown" or "not recorded".
- **Differences from the published example:** small wording differences in the stalled-deal sentences, the questions and the "Waiting on" lines. The same deals, kinds, dates, quotations, gaps and correction appear in both.
- **Where a choice was still made:**
  1. Whether "Price" and "the budget is going into a new press line" disagree is a judgment; this run treated them as at odds, as acceptance test 9 implies.
  2. The D-105 note says "the 10th" with no month. The review quotes it as written and writes nothing as "unknown" for it, so under the gaps rule it is not a gap.
  3. D-105's export names the account executive as the step's owner although the step is the buyer's. The kind follows the note and the step's own words; the owner is shown as recorded.
- This was one run by one model on one invented example, made by the session that revised the template. It shows the revised instructions can be followed to a complete output here; it is not a test in a client environment.

## The earlier run, and what was changed

The first run, the same day, was made by Claude Sonnet 5.5 on the instructions as first written. It produced every required part and no fact beyond the inputs, and it found these places where the instructions left a choice:

1. A next step with a date that still depends on the buyer (D-101): no rule said which kind wins. That run listed D-101 under both.
2. A next step that waits on a colleague inside the company (D-103): no kind existed, so it went under "no date set".
3. When whose move is unknown and the export has no deal-owner column, the question's addressee was undefined; that run chose the account executive, the published example the sales lead.
4. No rule said whether a next step with "no date set" is also a gap; the published example listed it, that run did not.
5. "Since the previous review" did not say whether the previous review's own date is in the period.
6. No rule said whether a quoted reason is the whole note or the reason sentence; that run quoted whole sentences, including "We declined." for D-109, and the published example paraphrased D-109's reason and D-106's proposed correction.

Changed afterwards, in the template and the example: one kind for each next step, taken in a fixed order (waiting on the buyer, waiting on a colleague, dated, no date set), with a recorded date never read as a check date; a "Waiting on a colleague" list in the output format; the addressee rule (the stage's usual owner, else the sales lead); the gaps rule; the period running from the day after the previous review to the review date, both included; the quote rule for reasons and for proposed corrections; an "Open at this review" line, so the next review reads one line, and the example's previous review labelled as an excerpt of that line; and two rules from the long procedure (an ambiguous date order is asked once, a status other than open, won or lost is not read) added to the instruction block. The example's output was brought into line with these rules, and the run above was made on them.
