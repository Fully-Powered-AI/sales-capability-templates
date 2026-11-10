# Stalled-deal review: an invented example

*Illustrative example with invented data.* The company, its accounts, its people, the deals, the dates and the amounts below are all invented. The seller is an invented 35-person company that sells maintenance-planning software to manufacturers. Its sales team is a sales lead, two account executives and a solutions engineer. First come the inputs the sales lead supplied, in full except the previous review, of which only the part the capability reads is shown; then the review the capability returned.

## The inputs

### 1. Your facts (typed by the sales lead)

```
Review date: Monday 2 November 2026
Export taken: Monday 2 November 2026
Closed deals: since the previous review on 26 October 2026
Reads it: Sales lead

Our stages, in order:
1. Discovery. Leaves when: the buyer's problem, the person who decides
   and a target date are all recorded. Usual owner: Account executive.
   Limit: 21 days.
2. Demo. Leaves when: the demo has been held with the person who decides
   and the buyer has asked for a proposal. Usual owner: Solutions
   engineer. Limit: 14 days.
3. Proposal. Leaves when: the proposal has been sent and the buyer has
   gone through it with us on a call. Usual owner: Account executive.
   Limit: 21 days.
4. Negotiation. Leaves when: terms are agreed and the order form has been
   sent for signature. Usual owner: Sales lead. Limit: 14 days.
```

### 2. The deal export

```
deal_id,account,stage,stage_entered,next_step,next_step_owner,next_step_date,last_activity,status,closed_date,close_reason
D-101,Account A,Proposal,2026-10-05,Proposal review call,Account executive,2026-10-22,2026-10-14,open,,
D-102,Account B,Demo,2026-10-20,Demo with the plant manager,Solutions engineer,2026-11-05,2026-10-29,open,,
D-103,Account C,Negotiation,2026-10-12,Send revised order form,Sales lead,,2026-10-19,open,,
D-104,Account D,Discovery,2026-09-28,,,,2026-10-02,open,,
D-105,Account E,Proposal,2026-10-26,Buyer to confirm budget after their board meeting,Account executive,2026-11-12,2026-10-27,open,,
D-106,Account F,Demo,2026-10-14,,,,2026-10-28,lost,2026-10-28,Price
D-107,Account G,Closed lost,2026-10-01,,,,2026-10-09,lost,2026-10-30,No response
D-108,Account H,Negotiation,2026-10-15,,,,2026-10-29,won,2026-10-29,Signed
D-109,Account J,Discovery,2026-10-19,,,,2026-10-27,lost,2026-10-27,Not a fit
```

### 3. Deal notes (pasted from the team's call notes and email)

```
D-101, 14 October 2026 (account executive): Sent the proposal, $26,400 a
year. The operations director says their finance team signs off anything
over $20,000 before she can book a review call. She will let us know.

D-103, 19 October 2026 (sales lead): Call with the buyer's operations
manager. Terms agreed except payment: they want 60 days instead of our
standard 30. I'll send the revised order form once our finance director
approves 60 days.

D-105, 27 October 2026 (account executive): Operations VP on the call:
"We'll come back to you after our board meets on the 10th." I'll check in
on the 12th.

D-106, 28 October 2026 (account executive): Email from the plant manager:
"Not this year. The budget is going into a new press line. Ask me again
in April."

D-109, 27 October 2026 (account executive): We declined. They need a
mobile app for floor staff, which we don't offer.
```

### 4. The previous review (an excerpt: its first line and its "Open at this review" line, the only part the capability reads)

```
STALLED-DEAL REVIEW: Monday 26 October 2026
Open at this review: D-099, D-101, D-102, D-103, D-104, D-105, D-106,
D-107, D-108, D-109.
```

## The output

**STALLED-DEAL REVIEW: Monday 2 November 2026**

**For:** Sales lead. **From:** deal export of 2 November 2026, 9 rows; your stages (4, limits in days: Discovery 21, Demo 14, Proposal 21, Negotiation 14); notes for 5 deals; previous review of 26 October 2026.

**Coverage:** Rows read: 9 (5 open, 1 won and 3 lost between 27 October and 2 November 2026). Not read: none. Open at the last review and missing now, under Could not assess: D-099. Outcome: partial: D-099 was open on 26 October and is not in this export.

**Open at this review:** D-101, D-102, D-103, D-104, D-105.

**Stalled deals: 3**

**D-101** · Account A · stalled at Proposal: the proposal was sent (note of 14 October), and the record shows no call since to go through it with us. Whose move: the buyer's (operations director): their finance team signs off a proposal over \$20,000 before she books the review call.

- Why: next-step date passed on 22 October; in Proposal 28 days, over the 21-day limit.
- On the record: last activity 14 October (19 days before the review); note of 14 October: the operations director says finance signs off anything over \$20,000 before she can book a review call, and she will let us know.
- Next step as recorded: Proposal review call, Account executive, 22 October 2026; waiting on the buyer, our check not set.
- Question to settle it, for the operations director: Has your finance team seen the proposal, and when will they decide on it?

**D-103** · Account C · stalled at Negotiation: terms are agreed except payment (the buyer asked for 60 days against our standard 30), and the record shows the revised order form not yet sent for signature. Whose move: a colleague's (finance director): whether to approve 60-day payment terms.

- Why: in Negotiation 21 days, over the 14-day limit.
- On the record: last activity 19 October (14 days before the review); note of 19 October: terms agreed except payment; the sales lead will send the revised order form once the finance director approves 60 days.
- Next step as recorded: Send revised order form, Sales lead, no date set; waiting on a colleague (finance director).
- Question to settle it, for the finance director: Will you approve 60-day payment terms for Account C, and by when?

**D-104** · Account D · stalled at Discovery: unknown: the record does not show whether the buyer's problem, the person who decides or a target date is recorded. Whose move: unknown.

- Why: no next step; in Discovery 35 days, over the 21-day limit.
- On the record: last activity 2 October (31 days before the review); no notes.
- Next step as recorded: none.
- Question to settle it, for the account executive: Which of the buyer's problem, the person who decides and a target date have we recorded for D-104, and what is the next step and who owns it?

**Moving deals: 2**

- **D-102** · Demo · Demo with the plant manager, Solutions engineer, 5 November 2026.
- **D-105** · Proposal · Buyer to confirm budget after their board meeting, Account executive, 12 November 2026; waiting on the buyer, our check 12 November 2026.

**Promises with no date set:** looked and found none.

**Waiting on the buyer:**

- D-101: the finance team's sign-off, then the operations director books the review call (operations director, note of 14 October); recorded date: 22 October 2026; our check: check date not set.
- D-105: come back to us after their board meets "on the 10th" (operations VP, note of 27 October); recorded date: 12 November 2026; our check: 12 November 2026, Account executive.

**Waiting on a colleague:** D-103: approve 60-day payment terms (finance director, note of 19 October); then: Send revised order form, Sales lead, no date set.

**Where the noes ended: 3 lost between 27 October and 2 November 2026**

Closed at Discovery:

- **D-109** · Account J · closed 27 October. Reason: "They need a mobile app for floor staff, which we don't offer." (ours, note of 27 October). Whose call: ours. What would reopen it: not recorded.

Closed at Demo:

- **D-106** · Account F · closed 28 October. Reason: "Not this year. The budget is going into a new press line." (plant manager, note of 28 October). Whose call: the buyer's. What would reopen it: "Ask me again in April." (plant manager, note of 28 October).

Stage not recorded:

- **D-107** · Account G · closed 30 October. Reason: No response (from the record, not the buyer's words). Whose call: unknown. What would reopen it: not recorded.

**Won between 27 October and 2 November 2026:** D-108, 29 October.

**At odds with the record:** D-106: the export's close reason says "Price"; the note of 28 October quotes the plant manager: "Not this year. The budget is going into a new press line."

**Gaps in the record:** D-104: which parts of the Discovery exit are met, and whose move it is. D-107: the stage it closed at, and whose call it was.

**Corrections to propose, for the sales lead or the deal's owner to make:** D-106: close_reason, now "Price", proposed "Not this year. The budget is going into a new press line.", from the note of 28 October.

Prepared from the deal export of 2 November 2026 and the notes supplied. Nothing has been sent, and no record has been changed.
