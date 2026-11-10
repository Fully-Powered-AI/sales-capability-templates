# Sales pipeline review: tried on its example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-09

The inputs are the invented example in [example.md](example.md): the facts note, this week's export of 9 November 2026 and last week's export of 2 November 2026. No client data was used. The run followed the template's instruction block and output format, took only the three inputs from the example, produced the review, and only then compared it with the example's published output and the reviewer checklist. It was one attempt with no second try.

This record replaces an earlier one from the same day. That earlier run used Claude Sonnet 5.5 on the first version of the instructions. It matched the published example in every figure but raised eleven points where the instructions were unclear. The instructions were then revised: what counts as a gap in the export, the order of each "Where to look first" item, rules that had been only in the procedure (the gap between the exports, an unclear date order, "none last week", "target already met", "nothing needs a first look this week"), whether the review date is in the baseline window, rounding, two-part owner questions, the currency, and a "Defaults used" slot in the header. The example's "Gaps in the export" line and header were brought into line. This run is on the revised version.

**Who ran it.** This run is less independent than the earlier one. The model that ran it had made the revisions and had read the earlier record and the published example first. It worked out the figures itself, then checked the arithmetic with a short script over the example's exports. The script found no difference.

**Edited after this run (9 November 2026).** After review, three sentences in the instruction block were brought into line with the procedure, and the run was not repeated: a missing last week's export does not stop the review (write "last week's export not supplied" and compare nothing); the "Not read" list names every case the procedure names (a status other than open, won or lost, an amount that is not a number, and a closed deal whose closed date falls outside both the period and the baseline window); and a new deal with a blank amount adds nothing to the bridge and is named. The output format did not change. The output below is from the version before these edits.

## What came out

Every part of the output format was produced. The output, in full:

```
SALES PIPELINE REVIEW: Monday 9 November 2026

For: Sales lead. Forecast committed by: Managing director. Period: 1 October 2026 to 31 December 2026. From: this week's export of 9 November 2026, 16 rows; last week's export of 2 November 2026, 11 open rows (exports 7 days apart). Stages: 4; weights Qualified 10%, Site survey 25%, Quote sent 50%, Negotiation 75%; limits in days Qualified 21, Site survey 14, Quote sent 21, Negotiation 14. Quiet after 14 days. Movement threshold: $25,000 and 20%. Rates need 20 closed deals. Defaults used: none.

Coverage: Rows read: 16 (9 open; 2 won and 1 lost in the period; 4 closed earlier in the baseline window). Not read: none. Open last week and missing now, under Could not assess: R-199, Qualified, $54,000. Outcome: partial: R-199 was open in last week's export and is not in this week's, so its outcome is unknown.

Headline: 9 open deals, $724,000 (1 amount blank); weighted $297,250. Won in the period so far: 2, $185,000. Deals at risk: 3, $402,000. Coverage of the remaining target: 1.4 against your bar of 3.0.

By stage:
Qualified: 2 open, $95,000 (1 amount blank); last week 3, $196,000 (moved: down $101,000, 51.5%). Weighted $9,500. Average 9 days in stage (limit 21). No next step: 0. Quiet 14+ days: 0. Over limit: 0.
Site survey: 2 open, $257,000; last week 2, $248,000 (up $9,000, 3.6%: under the threshold). Weighted $64,250. Average 15 days in stage (limit 14). No next step: 1. Quiet 14+ days: 1. Over limit: 1.
Quote sent: 3 open, $222,000; last week 3, $231,000 (down $9,000, 3.9%: under the threshold). Weighted $111,000. Average 16 days in stage (limit 21). No next step: 0. Quiet 14+ days: 1. Over limit: 1.
Negotiation: 2 open, $150,000; last week 3, $223,000 (moved: down $73,000, 32.7%). Weighted $112,500. Average 22 days in stage (limit 14). No next step: 0. Quiet 14+ days: 0. Over limit: 1.
Total: 9 open, $724,000; last week 11, $898,000 (down $174,000, 19.4%: under the threshold). Weighted $297,250.

Since last week: exports 7 days apart
New: R-207, Qualified, amount blank
Advanced: R-205, from Qualified to Site survey; R-209, from Site survey to Quote sent
Moved back: none
Close date changed: R-202, from 30 November 2026 to 15 December 2026
Amount changed: R-203, from $64,000 to $58,000
Won: R-194, $73,000, 4 November 2026
Lost: R-196, $41,000, 6 November 2026
Missing from this week's export: R-199, Qualified, $54,000
Bridge: $898,000 + $0 − $73,000 − $41,000 − $54,000 − $6,000 = $724,000

This period (1 October 2026 to 31 December 2026):
Won so far: 2, $185,000 (R-190, R-194). Lost: 1, $41,000 (R-196).
Open with a close date in the period: 6, $582,000; by stage: Site survey, 1, $210,000; Quote sent, 3, $222,000; Negotiation, 2, $150,000. Close date already passed: R-208.
Weighted: $276,000.
Target: $600,000. Remaining: $415,000. Coverage: 1.4; weighted 0.7; below your bar of 3.0.

Deals at risk: 3, $402,000
R-204 · Account D · Account manager 2 · Site survey · $210,000 · close 18 December 2026
  Flags: no next step; quiet 17 days (limit 14); in stage 24 days (limit 14).
  To ask Account manager 2: What is the next step with Account D and its date, and what is holding the deal in Site survey?
R-202 · Account B · Account manager 2 · Quote sent · $126,000 · close 15 December 2026
  Flags: close date moved later since last week, from 30 November 2026; next-step date passed on 3 November 2026; quiet 20 days (limit 14); in stage 28 days (limit 21).
  To ask Account manager 2: Did the quote review with the operations director happen on 3 November, and what moved the close date to 15 December?
R-208 · Account H · Account manager 1 · Negotiation · $66,000 · close 30 October 2026
  Flags: close date passed on 30 October 2026; in stage 31 days (limit 14).
  To ask Account manager 1: What close date should R-208 carry now that 30 October has passed, and does the revised quote still go out on 10 November?

Closed-deal baseline (13 May 2026 to 8 November 2026): 7 closed: 4 won, $301,000; 3 lost, $159,000. Rates not computed: 7 of 20 closed deals.

For the forecast, for Managing director to commit:
Won so far $185,000. Open closing in the period $582,000 (6): at risk $402,000 (3), not flagged $180,000 (3). Weighted $276,000. Remaining to target $415,000.
Forecast committed: ________ by Managing director on ________. This review does not set a number.

Where to look first:
1. Agree a dated next step on R-204, for Account manager 2, because it is the largest deal at risk closing in the period, at $210,000, with no next step and quiet 17 days.
2. Decide how the remaining $415,000 will be covered, for the sales lead, because coverage is 1.4 against your bar of 3.0.
3. Find out what happened to R-199, for Account manager 2, because it was open last week at $54,000 and is missing from this week's export.

Gaps in the export: R-207: amount blank

Prepared from the exports of 9 November 2026 and 2 November 2026. Nothing has been sent, and no record has been changed.
```

## What was observed

**Every required part was produced.** Header with "Defaults used", coverage line, headline, by-stage lines and total, the "Since last week" list with the bridge, the period section, the deals at risk, the baseline, the forecast block with its blank line, the "Where to look first" list, the gaps line and the closing sentence.

**Nothing in the instructions made the run stop.** The headers matched, both exports were present, no deal ID repeated, every date was in ISO form with one possible reading, every stage was on the list, and the stages and review date were supplied. The stop rules were not exercised. Neither were the refusals (forecast, ranking owners, changing a record), because this input never asks for them.

**Checks that held.** The stage values add up to the total ($724,000), and the weighted stage values to $297,250. The bridge balances. The total fell $174,000, which clears the amount threshold, but 19.4 percent is under the 20 percent threshold, so the review says "under the threshold". The blank amount on R-207 is counted as a deal and left out of every value total. With 7 closed deals against a minimum of 20, no rate appears. The forecast line is blank, and no deal is called likely to close.

**How the revised rules played out.**
- "Gaps in the export" lists only R-207's blank amount. R-204's blank next step and next-step date appear as a risk flag, not a gap. Closed deals' blank next steps and open deals' blank closed dates are not listed. Nothing is written about the bridge there, because it balances.
- All three "Where to look first" items follow "[Action], for [role], because [figure]", with the action first.
- The baseline window runs from 13 May to 8 November 2026 and leaves out the review date. No closed deal fell on the edge, so this input does not show the difference the rule makes.
- Movement percentages have one decimal. Weighted coverage of 0.665 rounds to 0.7.
- Each owner question has two parts. R-202 carries four flags and R-204 three.
- Amounts carry the dollar sign from the target in the facts note. The exports carry bare numbers.
- "Defaults used: none", because the facts note sets every setting.

**Differences from the published example.** None in any figure, flag, count, date or list. The wording differs in these places:
- The Outcome sentence ("its outcome is unknown" against the example's "was open on 2 November and is not in this week's export").
- The owner questions. For R-204 the run also asked what is holding the deal in Site survey; the example asks only for the next step and its date. The R-202 and R-208 questions ask the same things as the example in other words.
- The verbs in "Where to look first" ("Agree", "Find out" against the example's "Set", "Confirm"). The order, the roles and the figures are the same.

**Facts not in the inputs.** None found. Every account, owner, date and amount traces to a row in the exports or to the facts note.

**Where the instructions still left a choice.**
1. "Since last week" in the format has no closing full stop; the example adds one. A matter of style only.
2. A "Where to look first" item about coverage names the sales lead as the one to act, and the sales lead is also the reader. That is fine here, but the template does not say whether the reader may be named this way.

**What this trial does not show.** This run was one attempt on the revised instructions, after one earlier run on the first version, both in one product, on a clean input, by the model that revised the template. It does not show how the template behaves on messy exports, mismatched headers, repeated deal IDs, a date that could be read two ways, exports more than 10 days apart, a target already met, or requests to forecast or rank people. Of the acceptance tests, it covers test 1 (ordinary week) and, along the way, test 9 (movement under the threshold), the blank amount in test 3, the vanished deal in test 4, the pushed close date in test 5 and the too-few-closed-deals case in test 6. Tests 2, 7, 8, 10 and 11 were not run. It is not a test in a client environment.
