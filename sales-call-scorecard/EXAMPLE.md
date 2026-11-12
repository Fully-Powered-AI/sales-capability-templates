# Sales call scorecard: an invented example

*Illustrative example with invented data.* The companies, the people, the call, the words spoken and the dates below are all invented. The seller is an invented 40-person company that sells servicing and route-planning software to delivery firms. Its sales lead is coaching a newer account executive. First come the inputs the sales lead supplied, in full, then the scorecard the workflow template returned.

## The inputs

### 1. Call facts (typed by the sales lead)

```
Call date: Tuesday 6 October 2026
Account: Account D, a regional delivery firm
Call type: discovery
Reviewed by: Sales lead
Review date: Wednesday 7 October 2026

Goal for the call (from the account executive's preparation brief):
Learn how they track servicing today, what a van off the road costs
them, and who else decides; book a demo with the fleet manager.

Focus agreed after the last reviewed call (22 September 2026):
Ask what the problem costs before describing the product.
```

### 2. The team's criteria

```
criterion_id,criterion,shown_when,applies_to
C1,Agenda agreed,"The salesperson states the purpose of the call and asks the buyer to add or change anything, in the first five minutes.",discovery; demo
C2,Today's process,"The buyer describes how the work is done now, in their own words, in answer to a question.",discovery
C3,Cost of the problem,"The buyer, not our side, states what the problem costs in money or time.",discovery; account review
C4,Who decides,"The buyer names the people involved in the decision and how it is made.",discovery; demo; proposal or pricing
C5,Concern explored,"When the buyer raises a concern, the salesperson asks about it before answering, and the buyer says the answer covers it.",all
C6,Next step,"A next meeting with a date, attendees and a purpose is agreed on the call.",all
C7,Demo fitted to the buyer,"The demo shows the buyer's own process or data before any general feature.",demo
```

### 3. The people

```
name,side,role,on_call
Jordan,ours,Account executive,yes
Sam,buyer,Operations director,yes
Lee,buyer,Fleet manager,no
```

### 4. The transcript (exported from the meeting tool)

```
[00:00] Jordan: Hi Sam, thanks for making time.
[00:03] Sam: Sorry, something's come up at the depot. I've only got about five minutes.
[00:09] Jordan: No problem. So the plan for today: I'd like to understand how you look after the vans now, and then show you a little of what we do.
[00:18] Sam: Fine.
[00:20] Jordan: How do you keep track of when each van is due for a service today?
[00:25] Sam: Honestly, it's a spreadsheet my fleet manager keeps, and a whiteboard in the yard. When a driver reports a fault, they ring the depot, someone writes it on the board, and Lee moves it into the spreadsheet at the end of the week. We've got forty-two vans across two depots.
[00:52] Jordan: And how well does that work?
[00:55] Sam: It works until it doesn't. Last month we missed two services because the board got wiped.
[01:04] Jordan: That's exactly the sort of thing our platform fixes. Every van gets its service schedule built in automatically, drivers log faults from their phone, and your fleet manager sees everything on one screen. We also do route planning, fuel reports and tyre tracking, and there's a link with most leasing companies so the service intervals come straight across. Most of our customers are up and running in about two weeks.
[01:36] Sam: Okay.
[01:39] Jordan: So if a van's off the road, that's what, a few hundred dollars a day?
[01:44] Sam: Something like that. I'd have to check.
[01:48] Jordan: So two missed services could easily be costing you thousands a month.
[01:53] Sam: Probably.
[01:56] Jordan: What made you take the call this month?
[02:00] Sam: We renew our van leases in March, and I want the servicing sorted before then. The leasing company charges us if a van goes back with services missed.
[02:14] Jordan: Got it. Who else would be involved in a decision like this?
[02:18] Sam: Me, obviously. And [inaudible 02:20 to 02:33].
[02:34] Jordan: Great. And have you tried anything else for this?
[02:38] Sam: We tried a maintenance app two years ago. Our drivers won't use another app. They stopped logging anything after a month.
[02:49] Jordan: Ours is much simpler than most. It's one button for a fault, and it works offline, so drivers out in the country can still log things. We've had really good uptake with delivery firms your size.
[03:04] Sam: Maybe. I'd want Lee to see it. He's the one who'd live with it. He's only just back from leave, so he's swamped this week.
[03:15] Jordan: Shall we set up a demo with Lee next week?
[03:19] Sam: Thursday the 15th works. Ten o'clock. I'll bring Lee.
[03:25] Jordan: Perfect. I'll send the invite and a one-page summary today. Could you send me the spreadsheet Lee uses, with the drivers' names taken out, so I can set the demo up with your service intervals?
[03:37] Sam: I'll ask him to send it by Monday.
[03:41] Jordan: Thanks, Sam. Speak on the 15th.
[03:44] Sam: Thanks. Bye.
```

## The output

**SALES CALL SCORECARD: Account D, discovery, Tuesday 6 October 2026**

**For:** Sales lead. **Salesperson:** Account executive. **Buyer side on the call:** Operations director.
**Source:** transcript with timestamps, last line at 03:44. **Gaps:** 02:20 to 02:33. **Speakers:** all placed from the people list.
**Call type:** discovery.
**Criteria:** your criteria, 7.
**Coverage:** 7 criteria. Shown 2. Partly shown 3. Not shown 1. Not applicable 1. Cannot tell 0.
One call, reviewed for coaching. No overall score; not for employment decisions.

**Headline:** The call drew out how servicing is tracked today and ended with a dated demo that brings in the fleet manager. The cost figure came from our side rather than the buyer, and the drivers' concern was answered with features before it was explored.

**Criteria**

- **C1 Agenda agreed.** Partly shown. Evidence: "So the plan for today: I'd like to understand how you look after the vans now, and then show you a little of what we do." (our side, account executive, 00:09). Missing: the buyer was not asked to add or change anything.
- **C2 Today's process.** Shown. Evidence: "How do you keep track of when each van is due for a service today?" (our side, account executive, 00:20). "Honestly, it's a spreadsheet my fleet manager keeps, and a whiteboard in the yard. When a driver reports a fault, they ring the depot, someone writes it on the board..." (buyer side, operations director, 00:25). Missing: none.
- **C3 Cost of the problem.** Partly shown. Evidence: "The leasing company charges us if a van goes back with services missed." (buyer side, operations director, 02:00). "So if a van's off the road, that's what, a few hundred dollars a day?" (our side, account executive, 01:39). "Something like that. I'd have to check." (buyer side, operations director, 01:44). Missing: the buyer named a cost but no amount; the only amounts came from our side, and the buyer did not confirm them.
- **C4 Who decides.** Partly shown. Evidence: "Who else would be involved in a decision like this?" (our side, account executive, 02:14). "Me, obviously. And [inaudible 02:20 to 02:33]." (buyer side, operations director, 02:18). "I'd want [fleet manager] to see it. He's the one who'd live with it." (buyer side, operations director, 03:04). Why: the rest of the answer falls in the gap at 02:20 to 02:33. Missing: whoever else was named in the gap, and how the decision is made.
- **C5 Concern explored.** Not shown. Evidence: "Our drivers won't use another app. They stopped logging anything after a month." (buyer side, operations director, 02:38). "Ours is much simpler than most. It's one button for a fault, and it works offline..." (our side, account executive, 02:49). "Maybe. I'd want [fleet manager] to see it." (buyer side, operations director, 03:04). Missing: no question about the concern before the answer, and the buyer did not say the answer covered it.
- **C6 Next step.** Shown. Evidence: "Shall we set up a demo with [fleet manager] next week?" (our side, account executive, 03:15). "Thursday the 15th works. Ten o'clock. I'll bring [fleet manager]." (buyer side, operations director, 03:19). Missing: none.
- **C7 Demo fitted to the buyer.** Not applicable. Evidence: none. Why: not this call type; the criterion applies to demos. Missing: none.

**Goal for the call:** Learn how they track servicing today, what a van off the road costs them, and who else decides; book a demo with the fleet manager. Partly met: how servicing is tracked, met: "Honestly, it's a spreadsheet my fleet manager keeps, and a whiteboard in the yard." (00:25). What a van off the road costs, not met: the figure came from our side, "a few hundred dollars a day?" (01:39), and the buyer said "I'd have to check." (01:44). Who else decides, partly met: "Me, obviously." (02:18) and "I'd want [fleet manager] to see it." (03:04); the rest of the answer falls in the gap at 02:20 to 02:33. A demo with the fleet manager, met: "Thursday the 15th works. Ten o'clock. I'll bring [fleet manager]." (03:19).

**Talk balance (estimate from word count):** our side 268 of 454 words (59%), buyer side 186 (41%). Longest turn by our side: 70 words, starting 01:04. Your criteria set no target for talk balance.

**Where the call left the deal**

- **Next step:** agreed with a date and an owner. A demo on Thursday 15 October 2026 at 10:00, the operations director bringing the fleet manager; the account executive sends the invite. "Thursday the 15th works. Ten o'clock. I'll bring [fleet manager]." (buyer side, operations director, 03:19).
- **Our side's commitments:** send the invite and a one-page summary, by Tuesday 6 October 2026: "I'll send the invite and a one-page summary today." (03:25).
- **Buyer side's commitments:** bring the fleet manager to the demo on Thursday 15 October 2026: "I'll bring [fleet manager]." (operations director, 03:19). Ask the fleet manager to send the servicing spreadsheet, with the drivers' names taken out, by Monday 12 October 2026: "I'll ask him to send it by Monday." (operations director, 03:37).

**What the buyer said**

- **How the work is done today:** "Honestly, it's a spreadsheet my fleet manager keeps, and a whiteboard in the yard." (operations director, 00:25).
- **The problem:** "Last month we missed two services because the board got wiped." (operations director, 00:55).
- **What it costs:** "The leasing company charges us if a van goes back with services missed." (operations director, 02:00).
- **Timing:** "We renew our van leases in March, and I want the servicing sorted before then." (operations director, 02:00).
- **Who else is involved:** "Me, obviously." (operations director, 02:18). "I'd want [fleet manager] to see it. He's the one who'd live with it." (operations director, 03:04).
- **How they decide:** not stated on the call.
- **Concerns:** "Our drivers won't use another app. They stopped logging anything after a month." (operations director, 02:38).
- **Said by our side, not stated by the buyer:** a van off the road costs "a few hundred dollars a day" (01:39); the buyer's reply: "Something like that. I'd have to check." (01:44). Two missed services "could easily be costing you thousands a month" (01:48); the buyer's reply: "Probably." (01:53).
- **Left open:** who else was named in the gap at 02:20 to 02:33, and how the decision is made; what a van off the road costs; what made the drivers stop using the last app.

**Coaching note**

Went well:

1. C2, 00:20: an open question about today's process drew a full account of the spreadsheet, the whiteboard and the move from board to spreadsheet at the end of the week. "Honestly, it's a spreadsheet my fleet manager keeps, and a whiteboard in the yard." (buyer side, operations director, 00:25).
2. C6, 03:15: the account executive asked for a demo with the fleet manager and left with a date, a time and the person who would use the software. "Thursday the 15th works. Ten o'clock. I'll bring [fleet manager]." (buyer side, operations director, 03:19).

To work on:

1. C5, 02:49: the drivers' concern was answered with features at once, and the buyer's reply was "Maybe." "Ours is much simpler than most. It's one button for a fault, and it works offline..." (our side, account executive, 02:49). Next time, try: ask what happened with the last app before answering, such as "What made them stop after a month?", then check: "Would that deal with it for your drivers?"
2. C3, 01:39: the cost figure came from our side, after the product had been described at 01:04. "So if a van's off the road, that's what, a few hundred dollars a day?" (our side, account executive, 01:39). Next time, try: straight after "we missed two services", ask "What did those two cost you?" and wait for the buyer's number.
3. C1, 00:09: the plan was stated, but the buyer, who had just cut the call to five minutes, was not asked what they needed from it. "...and then show you a little of what we do." (our side, account executive, 00:09). Next time, try: "With five minutes, what's the one thing you'd want to get out of this?"

**Focus for the next call:** C3: before showing anything, ask the operations director and the fleet manager what the two missed services cost and what the leasing company charges, and let them give the number, at the demo on Thursday 15 October 2026.

**Last focus:** "Ask what the problem costs before describing the product." Not shown: the product was described at 01:04, before the first question about cost at 01:39.

**Limits of this review:** The gap at 02:20 to 02:33 holds the rest of the answer on who decides, so C4 is marked Partly shown and the goal's part on who else decides is partly met. One personal detail about someone on the call or named on it was left out. One call shows what happened on that call, not how the salesperson sells in general.

Prepared from the transcript of the call on Tuesday 6 October 2026. A review of one call, for coaching. Nothing has been sent, and no record has been changed.
