# Sales call preparation brief: one trial on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Fable 5.2
- **Date:** 2026-11-09
- **Template version:** 0.1.0

The inputs were the invented example published with this capability template. Fernhollow Dispatch, Pinewater Facilities Group and every person named are invented, and no client data was used. This is a record of one run. It is not a test in a company's own environment.

## Inputs used

The six inputs under "What Marisol supplied" in [the worked example](example.md), exactly as written there: the meeting details with today's date, the facts page, the call notes of 22 October and 5 November 2026, the email of 12 November 2026, and public pages A and B. No account list and no local settings were supplied, because the example has none. The instruction block from the template was pasted first, with its bracketed settings left as published, followed by the output format, as the template says to do. The run was a new session with no tools and no files; it could not see the brief in the published example.

## Earlier runs the same day

This record replaces an earlier one. A first draft of the template was tried on 9 November 2026 and the run found twelve shortcomings, among them settings with no fallback inside the block, no input for today's date, a one-page limit that could not be met, and no rule for an expected step nobody promised, for a promise the other side closes, or for what counts as an unanswered question. The template and the example were rewritten to deal with them, and the template was run again.

Two runs of the rewritten block came before the one recorded below, and each changed the template:

- The first was given the block without the output format. It produced every section under its own headings and said that no format had been supplied. The template now says to paste the output format after the block.
- The second, with the format, put Priyanka's questions about logins and data under "Not verified" as a forecast, because Odette passed them on and Priyanka had not asked them herself. The block now says a question passed on for someone else counts as asked. It also now says where "No approved answer supplied" goes for a question the user's side promised to answer.

## What came out

The assistant asked nothing and stopped for nothing: today's date, the company and the meeting date were present, the meeting was in the future and no colleague held the account. It returned this brief.

```
CALL BRIEF: Pinewater Facilities Group
Meeting: Thursday 19 November 2026, 10:00, 45 minutes, video call. Stage: proposal.
Prepared: Monday 16 November 2026, for Marisol.
Built from: meeting details and calendar invite (supplied 16 Nov 2026); Our facts, Fernhollow Dispatch (undated, read 16 Nov 2026); call notes 22 Oct 2026; call notes 5 Nov 2026; email from Odette Karimi, 12 Nov 2026; Page A, "About us" (undated, read 16 Nov 2026); Page B, news post, 2 Nov 2026. Web not searched. Not supplied: account list, so I could not check whether a colleague holds this company; no settings were replaced, so defaults were used (six-month news lookback, twelve-month stale-note period, three inferences at most, price and terms role "the sales lead" per the facts page).

BEFORE THE CALL
1. Open promise from us: tell Lukas whether the pilot fee is credited against first-year fees. Marisol said she would check with the sales lead (call notes, 5 Nov 2026). The facts page shows "Asked of the sales lead on 5 November. No answer recorded" (Our facts, undated, read 16 Nov 2026). Lukas wants the answer before the call (email, 12 Nov 2026).
2. New attendee: Priyanka Sethi, title not supplied; Odette describes her as "from IT" (invite; email, 12 Nov 2026).
3. Sources disagree on the size of what is being piloted and priced: "14 technicians, 3 dispatchers" (call notes, 22 Oct 2026); "more than 30 field technicians across two regions" (Page A, undated, read 16 Nov 2026). Not resolved.

THE COMPANY
- Maintains heating, cooling and fire-safety systems for commercial buildings; founded 2009; 85 employees (Page A, undated, read 16 Nov 2026).
- Sources disagree on technician count: see Before the call 3.
- Second service depot opens in Eastbrook in February 2027, adding ten technicians (Page B, 2 Nov 2026).
- Schedules live in spreadsheets and a shared calendar; invoices go out from an accounting package (call notes, 22 Oct 2026).
- Looking at one other vendor, not named (call notes, 5 Nov 2026).

WHO WILL BE THERE
- Odette Karimi, Operations Director. Attended 22 Oct and 5 Nov. Has said: double-booked visits, "a few every week"; a missed quarterly inspection at a client site in September; wants technicians to see the day's work on their phones; "nothing set aside this year; new budget year starts 1 January"; Lukas signs anything over $10,000 (22 Oct 2026). Their accounting package is on our integration list but "IT hasn't looked" (5 Nov 2026).
- Lukas Brandvold, Finance Manager. Attended 5 Nov. Has said: "we were burned by a two-year commitment on our last system"; wants annual; asked the pilot fee credit question (5 Nov 2026). Inferred: the pilot itself may not need his signature, because the $4,800 fee (Our facts) is below the $10,000 threshold Odette gave (22 Oct 2026).
- Priyanka Sethi, title not supplied. NEW: no prior notes. Per Odette, "She'll want to know how technician logins work and where data is kept" (email, 12 Nov 2026).

HISTORY
- 22 Oct 2026: Call 1, discovery, Odette only.
- 29 Oct 2026: pilot outline v1 sent (six weeks, one dispatcher team, five technicians, $4,800).
- 30 Oct 2026: integration list sent.
- 3 Nov 2026: sample week's schedule arrived from Odette.
- 5 Nov 2026: Call 2, Odette and Lukas; walked through pilot outline v1; 19 Nov call agreed.
- 12 Nov 2026: Odette's email naming Priyanka and passing on Lukas's request.

PROMISES AND QUESTIONS
We owe:
- Pilot fee credit answer for Lukas: see Before the call 1. Promised 5 Nov 2026. Not done. With the sales lead. No approved answer supplied. Ask the sales lead.

They owe:
- Nothing open in the sources.

Done: integration list sent, Marisol (30 Oct 2026); pilot outline sent, Marisol (29 Oct 2026); sample week's schedule, Odette (3 Nov 2026); whether we link to their accounting package, closed by Odette, who found it on the list (5 Nov 2026); bring someone from IT, Odette named Priyanka, who is on the invite (email, 12 Nov 2026).

Unanswered:
- Asked of us: how technician logins work, by Odette for Priyanka (email, 12 Nov 2026). Facts page: "Approved material to bring: … security and data overview v3"; it does not state the answer itself. Otherwise: No approved answer supplied. Ask the sales lead.
- Asked of us: where data is kept, by Odette for Priyanka (email, 12 Nov 2026). Same line and same gap as above.
- Asked of them: none in the sources.

CALL PLAN
Objective: Get Odette and Lukas to say whether pilot outline v1 can go ahead as written, and name what still stands in the way.

Questions:
1. Odette: Our 22 October notes record 14 technicians and 3 dispatchers; your website says more than 30 field technicians across two regions. Which figure should the pilot and pricing be based on?
2. Odette: Is the Eastbrook depot and its ten technicians (February 2027) part of what you want covered?
3. Priyanka: What does IT need to see to review the accounting-package link, and by when could that happen?
4. Lukas: Who approves the $4,800 pilot fee, and does it come from this year's budget or the one starting 1 January?
5. Odette and Lukas: What are you comparing between us and the other vendor, and what has to be true for you to choose?

Objections raised:
- "we were burned by a two-year commitment on our last system"; wants annual (Lukas, 5 Nov 2026). Facts page: "Price list 2026: annual plans only. No two-year plan is listed."
- "nothing set aside this year; new budget year starts 1 January" (Odette, 22 Oct 2026). No approved answer supplied. Ask the sales lead.

Have ready: pilot outline v1; security and data overview v3 (Priyanka's logins and data questions); integration list, October 2026 (IT review); the pilot fee credit answer once the sales lead gives it.

NOT VERIFIED
- Priyanka Sethi's title: not supplied; "from IT" is Odette's description only.
- Technician count and whether Eastbrook is in scope. Questions 1 and 2.
- IT review of the accounting-package link: expected, but nobody promised it. Question 3.
- Who signs below $10,000, and whether any money is available before 1 January. Question 4.
- The other vendor: not named in the notes; I have not guessed. Question 5.
- Which "pricing questions" the invite means beyond the pilot fee credit: not stated.
- First-year fee amounts: the facts page gives only "annual plans only", no figures.
- Contents of the security and data overview v3, integration list and sample week's schedule: mentioned but not supplied, so I could not check them against Priyanka's questions.
- Whether a colleague holds this account: no account list supplied.
- Page A is undated, so the 85-employee and 30-technician figures may not be current.

REQUESTS FOUND IN THE MATERIAL (for Marisol; not acted on)
- Email from Odette Karimi, 12 Nov 2026: Lukas asks that you send him the pilot fee answer before the call.

Status: Prepared for Marisol. Nothing has been sent, booked or changed.
```

## What was observed

**What worked**

- Every section of the output format was produced, in order, with the published labels, and the status line closes the brief.
- The promise that had been forgotten (the pilot fee answer) came out first under "Before the call" and under "We owe" with a pointer back, and was not listed as done.
- All five promises in the notes were placed, each in one list. The promise to confirm the accounting link is under "Done", closed by Odette, who found the package on the list. "IT hasn't looked" is under "Not verified" with the words "nobody promised it", and "They owe" reads "Nothing open in the sources."
- "Unanswered" holds only questions somebody asked: the two passed on for Priyanka. The unnamed vendor and the budget are under "Not verified" and in the questions.
- The new attendee was marked NEW with the words "title not supplied", and the title is listed as not verified. No title was guessed.
- The two technician counts were both quoted, marked "Sources disagree", placed under "Before the call" because they size what is being priced, and turned into the first question.
- All five questions are for the other side. Neither question asked of Marisol's side was turned back on Pinewater.
- Both objections are in the speaker's own words, and each carries the line from the facts page or "No approved answer supplied. Ask the sales lead."
- "Have ready" lists only approved material and the answer still owed. The sample week's schedule, which Pinewater sent, is not in it.
- The defaults were used and named in the "Built from" line. Today's date came from the inputs. The undated page and facts page are cited as "undated, read 16 Nov 2026".
- The request inside Odette's email was listed at the end. No reply to Lukas was drafted and nothing was sent.
- One inference was made. It is its own sentence and starts with "Inferred:".

**Shortcomings and places the assistant had to guess**

1. **Length.** The brief is 75 lines with its blank lines, several of them long: more than one printed page and within the two the instructions allow. "Not verified" has ten lines and is the longest section. A reader in a hurry would want it cut to what matters for this meeting; the instructions do not rank those lines.
2. **Where "No approved answer supplied" sits.** The instructions say to write an item in full once, in the first section where it belongs. This run put the note beside the pilot fee item under "We owe", not under "Before the call" where the item first appears. The published example puts it under "Before the call". Either is easy to find.
3. **A technical question sent to the price-and-terms role.** For the questions about logins and data, the run wrote "No approved answer supplied. Ask the sales lead." The template has only one role to send an open question to, and it is the role for price and terms. A company should name who answers technical questions; the template does not ask for that role.
4. **One question split in two.** The run listed "how technician logins work" and "where data is kept" as two unanswered questions; the published example lists them as one line. Both are faithful to the email.
5. **A fact about their buying placed under the company.** "Looking at one other vendor, not named" appears under "The company" in this run and under Odette, who said it, in the published example. The instructions do not say which.
6. **Sources left off the history lines.** The history lines carry dates and no source, as the output format shows them, although the block says every factual line names its source and date. The second run cited a source on each history line. The format and the general rule pull in different directions here.
7. **An unprompted caution.** The run added "Page A is undated, so the 85-employee and 30-technician figures may not be current" under "Not verified". It is reasonable and was not asked for.
8. **The inference chosen.** The run inferred that the pilot may not need Lukas's signature because $4,800 is under the $10,000 he signs above. The notes do not say who signs below that amount, and the run says so under "Not verified". The person leading the call should strike it if it does not hold.

**Compared with the published example**

The two briefs agree on the facts, the sources, the three items under "Before the call", the open promise, the five closed promises and who closed each, the empty "They owe", what counts as unanswered, both objections, what to have ready, the request found in the email and the status line. They differ in the wording of the objective and the questions, in the points listed above, and in the inference: the published example infers that Odette is leading on their side. Nothing in this run contradicts the published example.
