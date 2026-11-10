# Competitor battlecard: a trial on the invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-09
- **Template version:** 0.1.0

This is a record of one run of the capability template on its own invented example. The companies, deals, pages and prices are invented, and no client data was used. It shows what the template produced once, on one set of inputs. It is not a test in any company's environment.

This is the second run on the same example. An earlier run the same day, by a model that had not written the template, showed where the instructions left room to guess and where the published example broke the template's own rules. The template and the example were then revised, and the run recorded here was made on the revised template. It was made by the model that made those revisions, which had already read the published example and the earlier run. It is therefore not an independent check: it shows that the revised instructions can be followed to a card that keeps the rules, not that a fresh reader would produce one. What the earlier run found, and what was changed, is at the end.

The run used the inputs section of `public/example.md` as published (the card settings, the four saved pages, the fact sheet, the four deal notes and the deal export; no previous card), the instruction block and the output format.

## What came out

Nothing in the inputs called for a stop. Every part of the output format was produced. The card as produced:

```
COMPETITOR BATTLECARD: Company Z vs Competitor A

For: account executives, selling to architecture and engineering practices of 10 to 150 people. Card date: 2 November 2026. Recheck by: 30 December 2026 (90 days after 1 October 2026, the fact sheet). Status: draft for the sales lead's approval.
Read: 4 sources on the competitor (S1 to S4; S4 past recheck, not used), fact sheet of 1 October 2026, 4 deal notes, deal export of 2 November 2026, no previous card.

In short: Competitor A leads with time entry from any device, even offline (S1, S3), and a free 14-day trial (S1). We are stronger for practices that bill by phase and want onboarding and phone support in the price (F4, F2, S2).

What they say: "Time tracking your whole firm will actually use." (S1). Price: Team, $15 per user per month, billed annually, time tracking and timesheets; Business, $29 per user per month, billed annually, adds project budgets and invoicing; guided onboarding for a one-time fee, figure not stated; email support on all plans (S2). Like for like: our $24 per user per month, billed annually (F2), against Business at $29 (S2): $5 less per user per month. Business has project budgets, invoicing and email support, onboarding extra (S2); ours has phase budgets, invoicing, two onboarding sessions and phone support (F2). Their main claims, as they make them: they show "Trusted by 2,000 firms" above a row of customer logos (S1).

Where they are strong:
1. Their pages describe time entry even offline, on iPhone and Android (S1, S3; N1, N4). Our app needs a connection (F3). The D-431 buyer chose them for it.
2. A lower entry price: Team, at $15, covers time tracking and timesheets (S2); ours is $24 with budgets and invoicing (F2).
3. A free 14-day trial (S1). We offer a demo on the buyer's own projects (F5).

Where we are stronger:
1. Phase budgets in hours and fees, with an alert to the project lead at 80% of a phase's hours (F4). Their side: project budgets and budget alerts by project (S2, S3); no mention of budgets by phase found in (S1 to S3) as of 26 October 2026. Why it matters: a buyer who bills by phase raised it (N3). Proof: Practice B may be named on calls: "We see which phase is over budget before the invoice goes out." (F6). Ask: "How do you find out today that a phase is running over?"
2. Two onboarding sessions and phone support in the price (F2). Their side: onboarding is a one-time fee, figure not stated; support is by email (S2). Why it matters: $5 per user per month less on the like-for-like plans, before their onboarding fee (What they say). Proof: no shareable proof: say only what (F2) states. Ask: "Is setup priced on top for each option?"

If they come up: "They're strong when most of your time is entered on site without signal. If you bill by phase, compare how each shows a phase running over and what budgets, invoicing and onboarding cost." Then ask: "Who enters time, and where?"

What buyers have told us:
"Competitor A's budgets are by project, not by phase. We bill by phase." (finance manager, D-425, note of 6 October 2026, N3)
"Competitor A is cheaper per person." (principal, D-418, note of 22 September 2026, N2)
"Competitor A's app works with no signal on site. Half our engineers are on construction sites all day." (office manager, D-412, note of 8 September 2026, N1)

Objections they bring to the buyer:
"Competitor A is cheaper per person." (N2)
Answer: Their Team plan is, but it covers time tracking and timesheets only; with budgets and invoicing it is $29, against our $24 with onboarding (S2, F2). If time tracking is all you need, theirs costs less. Ask: "Do you need budgets and invoicing this year?"
"Competitor A's app works with no signal on site." (N1)
Answer: That's right: their pages describe offline entry, and our app needs a connection (S1, S3, F3). If most time is entered without signal, weigh that first. Ask: "How many of your people enter time without signal?"

Questions that bring out the difference:
1. "How do you bill your clients: by project or by phase?" (brings out point 1)
2. "What does setup cost on top of the subscription for each option?" (brings out point 2)

Do not raise first: offline entry (strength 1); the entry-plan price (strength 2); the free trial (strength 3).

Where they fit better: practices whose staff enter most of their time on sites without signal (S1, S3, N1, N4). The sales lead decides whether to pursue these deals.

Head-to-head, closed deals naming Competitor A, 1 July 2026 to 31 October 2026: 7 (won 3, lost 4), too few for a rate, under 10. Lost, by reason as recorded: Competitor 2 (D-412, D-431); Price 1 (D-405); No decision 1 (D-421). Not recorded: none. Not read: D-436, open.

What changed: no previous card.

Held back (not for use with buyers):
- "Competitor A is cutting staff." (N4): about their staff, left off by rule.
- "The buyer said Competitor A quoted them $3,000 for onboarding." (N4): one buyer's report; no source states a figure, and the pricing page says only "a one-time fee" (S2).
- "Connect with 40 apps, including payroll." (S4): source past recheck: reread https://competitor-a.example/integrations
- Case study, Practice C (F7): no permission on record.

Sources:
S1 Homepage, https://competitor-a.example/, saved 26 October 2026, 7 days old.
S2 Pricing page, https://competitor-a.example/pricing, saved 26 October 2026, 7 days old.
S3 Product updates page, https://competitor-a.example/updates, saved 26 October 2026, 7 days old.
S4 Integrations page, https://competitor-a.example/integrations, saved 15 June 2026, 140 days old. Past recheck.
F Company Z fact sheet (F1 to F7), dated 1 October 2026, 32 days old.
N1 D-412, note of 8 September 2026, account executive. N2 D-418, note of 22 September 2026, account executive. N3 D-425, note of 6 October 2026, sales lead. N4 D-431, note of 20 October 2026, account executive.
Export: deals-competitor-a.csv, taken 2 November 2026, 8 rows.

Draft for the sales lead's approval before it is shared. Nothing has been sent or posted, and no record has been changed.
```

## What was observed

**Required parts.** Every section of the format was produced. The recheck date came to 30 December 2026, the fact sheet of 1 October 2026 plus 90 days, since the integrations page (S4) is past recheck and not used. The head-to-head counted 7 closed deals, 3 won and 4 lost, with no rate under the group minimum of 10; lost by reason, Competitor 2, Price 1, No decision 1, with Price before No decision because it appears first in the export; the open deal D-436 not read. The Read line named S4 as past recheck and not used, as the revised format asks.

**Length.** The first full draft ran to 812 words from In short to the end of Where they fit better, counting headings and tags. The check in step 18 found it over the 700-word ceiling, and lines were cut, never tags: a sentence noting that the competitor's minimum number of users is not stated; the date of the competitor's Android update; a second question on point 1, which repeated that point's own question; the buyer's practice size after "principal"; and shorter wording in the like-for-like line, the strengths, the second point's question and the objection answers. The card as recorded is 698 words. Because the person cutting had seen the published example, several cuts ended on the example's wording.

**What the revisions settled.** The price comparison went under What they say as "Like for like", and the price point under Where we are stronger referred to it rather than repeating it. Offline entry was written as what their pages describe, under Where they are strong, and not listed again as a claim. Proof was taken only from F6, which has permission on record; the second point used the fixed wording "no shareable proof: say only what (F2) states". Where they fit better added no condition that the inputs do not state. "Not recorded" counted lost deals only.

**Where the instructions still leave room to guess.**
- Like for like: the nearest plan, Business, has project budgets where Company Z has phase budgets, and email support where it has phone support. The revised step allows a partial match with the differences named, and the run used it; whether these plans have "the same inclusions" remains a judgement.
- The fixed proof wording still reads oddly on a point about what the price includes.
- A strength the sources show but which is not worth a numbered strength, such as the competitor's budget alerts by project, has no place of its own; the run put it on "their side" of the first point under Where we are stronger.

**Differences from the published example.**
- Like for like: the run names invoicing on both sides; the example leaves it out because both plans include it.
- Where we are stronger, point 1: the run gives their side as project budgets and budget alerts by project (S2, S3); the example gives budget alerts by project (S3). The question is worded differently.
- Where we are stronger, point 2: the same point and the same proof wording. The run's "Why it matters" gives the \$5 difference on the like-for-like plans; the example's says their onboarding costs extra and ours comes in a plan \$5 below Business. The questions differ.
- If they come up: the run opens "They're strong"; the example "They're a good choice". The run adds onboarding to what to compare.
- Questions that bring out the difference: two each. The second differs: the run asks what setup costs on top of each subscription; the example asks who will train the team and how they will reach support.
- The first objection answer: the run's opens "Their Team plan is, but"; the example's "Their Team plan is cheaper, but".
- Held back: the same four lines and reasons, worded slightly differently; the run gives the integrations page's address, the example names the page.
- Sources: the run adds "(F1 to F7)" to the fact sheet line.
- Everything else, including the strengths, the buyer quotations, the second objection, what not to raise first, where they fit better and the head-to-head, is the same in substance.

**Facts in either output that are not in the inputs.**
- Both: "If most time is entered without signal, weigh that first" is advice, not a sourced line. "\$5 less per user per month" is computed (\$29 - \$24), not stated by any input.
- Both: In short says Company Z is stronger "for practices that bill by phase". That rests on F4 and on the buyer in N3, but N3 is not among In short's tags.
- No other line in either card states something the inputs do not.

**Checklist, as applied to this run.** Every statement about the competitor is tagged, and each tag checks against its saved page. No line rests on S4. Silence is reported as "no mention found in (S1 to S3)". The competitor's three strengths are all on the card. Proof comes from F6 only. The price difference recomputes. The head-to-head recomputes from the export, with no rate under 10. Nothing about the competitor's staff appears on the card. The card is 698 words, inside the ceiling.

**Not tried.** Only the ordinary case was run. The acceptance tests, including the stale price, the mismatched header, the request to share and the two-competitor request, were not run, and the template was not tried in a client environment.

## The earlier run, and what was changed

The first run, on 9 November 2026 in Claude Code with Claude Sonnet 5.5, used the template as first written and the same inputs. It was made by a model that had not written the template, which read only the inputs section of the example before running and compared afterward. It produced every section, the same recheck date, the same head-to-head and the same four held-back lines as the example then published. It differed in these ways, and noted these things:

- Its card ran to about 1,000 words from In short to Where they fit better, and the example's to about 900 by its count. Neither was plausibly one page, and the template did not say how to measure one; it marked checklist item 9 as failed.
- It had three points under Where we are stronger: phase budgets, onboarding and phone support included, and price against the nearest comparable plan. The example then had two and did not use the fact sheet's phone support against the competitor's email support.
- The example's second point gave "the two price lists (F2, S2)" as proof, one of them the competitor's own page; the template allows proof only from fact sheet lines with permission on record. The run used the fixed wording "no shareable proof".
- The example's Where they fit better added "who do not bill by phase", which no input states. Its In short tagged the free trial with (S1, S3), though only S1 mentions a trial.
- Where it had to guess: the price comparison had no place in the output format; "like for like" was not defined for a partial match; the Read line did not say how to show a source read but not used; steps 3 and 4 pulled against each other for a feature known only from the competitor's page; how much inference Where they fit better allows was not said; "Not recorded" did not say it counts lost deals only; and some "Why it matters" lines it wrote went beyond the inputs.

Changed after the first run, before the run recorded above:

- **Proof.** The example's second point now uses "no shareable proof: say only what (F2) states", as the template requires.
- **Where they fit better.** The example's clause "who do not bill by phase" and the tags that supported only it were cut. Step 12 now says a kind of deal joins what a source shows the competitor offers to what a note shows a buyer needed or chose, and adds no condition no input states.
- **Length.** "One page" is now 700 words at most from In short to the end of Where they fit better, tags included, in the procedure, the pasted instructions and the checklist. The example was trimmed to fit.
- **Price comparison.** It has a slot under What they say, "Like for like:", and a partial match is compared with each difference named. The example now has that line and uses phone support against email support.
- **Claims and strengths.** A feature the competitor's pages describe is written as what their pages describe, under Where they are strong, and is not listed again as a claim.
- **The Read line** names a source past recheck as "past recheck, not used".
- **Not recorded** counts lost deals with a blank reason only.
- **The pasted instructions** now carry the wording for a price whose only source is past recheck, and "no deal notes supplied".
- **The example's In short** tags offline entry (S1, S3) and the free trial (S1) separately, and its held-back lines keep the wording of the note and the page they came from.

Changed after the run recorded above, and not run again:

- The procedure, the pasted instructions and the checklist now say how the 700 words are counted: words separated by spaces, headings and tags included. The run counted the same way.
- After an independent review, the template was clarified in ways that do not change what this run's inputs call for. When the fact sheet is past recheck, Recheck by now reads "now, fact sheet past recheck" instead of a date already passed; the example's fact sheet is current, so this case did not arise. The objections step now says the objections are ones buyers raised, quoted as the note records it, and that the limit may be one untagged sentence of advice that states no fact, as both cards' second answer has. A competitor feature too small for a numbered strength now goes on "Their side" of the point it bears on, as this run placed budget alerts by project. The rule against saying why deals were won or lost now names the head-to-head count, and a note's account of why one buyer chose carries that note's tag. In short's tag in the output format now allows a note tag. The template now says that the pasted instructions number their steps differently from the procedure; step numbers in this record, such as "step 18" under Length, are those of the pasted instructions.
- The published example was edited after the same review, so the differences listed above describe the example as it stood at this run. Its In short now tags N3; its first strength now reads (S1, S3, N1, N4) and tags the D-431 buyer's choice (N4); its second point under Where we are stronger now says why the point matters to a buyer comparing price per person (N2) instead of restating the price difference. Its card is 699 words. The run's own card, recorded above, keeps In short without N3 and the strength's tags as produced.
- Still open: the fixed proof wording on a point about what the price includes, noted above, was not changed. Only the ordinary case has been run, by the model that revised the template; none of the eleven acceptance tests has been run.
