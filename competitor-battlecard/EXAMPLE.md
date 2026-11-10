# Competitor battlecard: an invented example

*Illustrative example with invented data.* The companies, the deals, the people, the pages, the dates and the prices below are all invented, and the web addresses use the reserved `.example` domain. Company Z is an invented 30-person company that sells time-tracking, budgeting and invoicing software to architecture and engineering practices. Competitor A is an invented competitor. First come the inputs the sales lead supplied, in full, then the card the capability returned.

## The inputs

### 1. The card settings (typed by the sales lead)

```
Competitor: Competitor A
Our company: Company Z
For: account executives, selling to architecture and engineering
practices of 10 to 150 people
Card date: Monday 2 November 2026
Approver: sales lead
Recheck interval: 90 days
Head-to-head period: 1 July to 31 October 2026
Group minimum: 10
```

### 2. Sources on Competitor A (pages saved by the sales lead)

```
Homepage, https://competitor-a.example/, saved 26 October 2026
  Headline: "Time tracking your whole firm will actually use."
  Under the headline: "Enter time from any device, even offline."
  Shows: "Trusted by 2,000 firms" above a row of customer logos.
  Button: "Start your free 14-day trial"

Pricing page, https://competitor-a.example/pricing, saved 26 October 2026
  Team: $15 per user per month, billed annually. Time tracking and
  timesheets.
  Business: $29 per user per month, billed annually. Everything in
  Team, plus project budgets and invoicing.
  "Guided onboarding is available for a one-time fee."
  Email support on all plans.

Product updates page, https://competitor-a.example/updates, saved 26 October 2026
  14 October 2026: "Offline time entry is now on Android as well as
  iPhone."
  2 September 2026: "Budget alerts by project: get notified when a
  project reaches a set share of its budget."

Integrations page, https://competitor-a.example/integrations, saved 15 June 2026
  "Connect with 40 apps, including payroll."
```

### 3. The fact sheet (Company Z, owned by the sales lead, confirmed 1 October 2026)

```
F1 What we sell: time tracking, phase budgets and invoicing for
   architecture and engineering practices of 10 to 150 people.
F2 Price: $24 per user per month, billed annually, minimum 10 users.
   Includes phase budgets, invoicing, two onboarding sessions and
   phone support.
F3 Mobile app: time entry on iPhone and Android. It needs a
   connection; there is no offline entry.
F4 Phase budgets: a budget in hours and fees for each phase of a
   project, with an alert to the project lead when a phase passes 80%
   of its hours.
F5 No free trial. We offer a demo set up with the buyer's own
   projects.
F6 Reference: Practice B, a 60-person engineering practice. May be
   named to prospects on calls; permission recorded by the sales lead
   on 12 August 2026. Approved quotation: "We see which phase is over
   budget before the invoice goes out."
F7 Case study: Practice C. Permission to share with prospects: not on
   record.
```

### 4. Deal notes (pasted from the team's call notes)

```
D-412, 8 September 2026 (account executive): Office manager: "Competitor
A's app works with no signal on site. Half our engineers are on
construction sites all day."

D-418, 22 September 2026 (account executive): Principal of a 25-person
architecture practice: "Competitor A is cheaper per person." We showed
phase budgets on their own projects. They signed with us.

D-425, 6 October 2026 (sales lead): Finance manager: "Competitor A's
budgets are by project, not by phase. We bill by phase." Signed with us.

D-431, 20 October 2026 (account executive): The buyer said Competitor A
quoted them $3,000 for onboarding. They chose Competitor A for offline
entry; their surveyors work in areas with no signal. My note: I heard
Competitor A is cutting staff.
```

### 5. The deal export (deals-competitor-a.csv, taken 2 November 2026)

```
deal_id,outcome,closed_date,competitor,close_reason
D-405,lost,2026-07-14,Competitor A,Price
D-409,won,2026-08-05,Competitor A,
D-412,lost,2026-09-10,Competitor A,Competitor
D-418,won,2026-09-24,Competitor A,
D-421,lost,2026-09-30,Competitor A,No decision
D-425,won,2026-10-08,Competitor A,
D-431,lost,2026-10-22,Competitor A,Competitor
D-436,open,,Competitor A,
```

No previous card was supplied.

## The output

**COMPETITOR BATTLECARD: Company Z vs Competitor A**

**For:** account executives, selling to architecture and engineering practices of 10 to 150 people. **Card date:** 2 November 2026. **Recheck by:** 30 December 2026 (90 days after 1 October 2026, the fact sheet). **Status:** draft for the sales lead's approval.
**Read:** 4 sources on the competitor (S1 to S4; S4 past recheck, not used), fact sheet of 1 October 2026, 4 deal notes, deal export of 2 November 2026, no previous card.

**In short:** Competitor A leads with time entry from any device, even offline (S1, S3), and a free 14-day trial (S1). We are stronger for practices that bill by phase and want onboarding and phone support in the price (F4, F2, S2, N3).

**What they say:** "Time tracking your whole firm will actually use." (S1). Price: Team, \$15 per user per month, billed annually, time tracking and timesheets; Business, \$29 per user per month, billed annually, adds project budgets and invoicing; guided onboarding for a one-time fee, figure not stated; email support on all plans (S2). Like for like: our \$24 per user per month, billed annually (F2), against Business at \$29 (S2): \$5 less per user per month. Business has project budgets and email support, onboarding extra (S2); ours has phase budgets, two onboarding sessions and phone support (F2). Their main claims, as they make them: they show "Trusted by 2,000 firms" and a row of customer logos (S1).

**Where they are strong:**

1. Their pages describe time entry even offline, on iPhone and Android (S1, S3, N1, N4). Our app needs a connection (F3). The D-431 buyer chose them for it (N4).
2. A lower entry price: Team, at \$15, covers time tracking and timesheets (S2); ours is \$24 with budgets and invoicing (F2).
3. A free 14-day trial (S1). We offer a demo on the buyer's own projects (F5).

**Where we are stronger:**

1. Budgets for each phase, in hours and fees, with an alert to the project lead at 80% of a phase's hours (F4). Their side: budget alerts by project (S3); no mention of budgets by phase found in (S1 to S3) as of 26 October 2026. Why it matters: a buyer who bills by phase raised it (N3). Proof: Practice B may be named on calls: "We see which phase is over budget before the invoice goes out." (F6). Ask: "How do you find out a phase is running over today?"
2. Two onboarding sessions and phone support in the price (F2). Their side: onboarding is a one-time fee, figure not stated; support is by email (S2). Why it matters: a buyer comparing price per person (N2) pays their onboarding fee on top (S2); see Like for like. Proof: no shareable proof: say only what (F2) states. Ask: "Is setup priced on top for each option you're comparing?"

**If they come up:** "They're a good choice when most of your time is entered on site without signal. If you bill by phase, compare how each shows a phase running over and what budgets and invoicing cost." Then ask: "Who enters time, and where?"

**What buyers have told us:**

"Competitor A's budgets are by project, not by phase. We bill by phase." (finance manager, D-425, note of 6 October 2026, N3)
"Competitor A is cheaper per person." (principal, D-418, note of 22 September 2026, N2)
"Competitor A's app works with no signal on site. Half our engineers are on construction sites all day." (office manager, D-412, note of 8 September 2026, N1)

**Objections they bring to the buyer:**

"Competitor A is cheaper per person." (N2)
Answer: Their Team plan is cheaper, but it covers time tracking and timesheets only; with budgets and invoicing it is \$29, against our \$24 with onboarding (S2, F2). If time tracking is all you need, theirs costs less. Ask: "Do you need budgets and invoicing this year?"

"Competitor A's app works with no signal on site." (N1)
Answer: That's right: their pages describe offline entry, and our app needs a connection (S1, S3, F3). If most time is entered without signal, weigh that first. Ask: "How many of your people enter time without signal?"

**Questions that bring out the difference:**

1. "How do you bill your clients: by project or by phase?" (brings out point 1)
2. "Who will train your team, and how will they reach support?" (brings out point 2)

**Do not raise first:** offline entry (strength 1); the entry-plan price (strength 2); the free trial (strength 3).

**Where they fit better:** Practices whose staff enter most of their time on sites without signal (S1, S3, N1, N4). The sales lead decides whether to pursue these deals.

**Head-to-head, closed deals naming Competitor A, 1 July 2026 to 31 October 2026:** 7 (won 3, lost 4), too few for a rate, under 10. Lost, by reason as recorded: Competitor 2 (D-412, D-431); Price 1 (D-405); No decision 1 (D-421). Not recorded: none. Not read: D-436, open.

**What changed:** no previous card.

**Held back (not for use with buyers):**

- "Competitor A is cutting staff." (N4): about their staff, left off by rule.
- "The buyer said Competitor A quoted them \$3,000 for onboarding." (N4): one buyer's report; no source states a figure, and the pricing page says only "a one-time fee" (S2).
- "Connect with 40 apps, including payroll." (S4): source past recheck: reread the integrations page.
- "Practice C case study" (F7): no permission on record.

**Sources:**

S1 Homepage, https://competitor-a.example/, saved 26 October 2026, 7 days old.
S2 Pricing page, https://competitor-a.example/pricing, saved 26 October 2026, 7 days old.
S3 Product updates page, https://competitor-a.example/updates, saved 26 October 2026, 7 days old.
S4 Integrations page, https://competitor-a.example/integrations, saved 15 June 2026, 140 days old. Past recheck.
F Company Z fact sheet, dated 1 October 2026, 32 days old.
N1 D-412, note of 8 September 2026, account executive. N2 D-418, note of 22 September 2026, account executive. N3 D-425, note of 6 October 2026, sales lead. N4 D-431, note of 20 October 2026, account executive.
Export: deals-competitor-a.csv, taken 2 November 2026, 8 rows.

Draft for the sales lead's approval before it is shared. Nothing has been sent or posted, and no record has been changed.
