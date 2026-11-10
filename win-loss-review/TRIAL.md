# Win-loss review: trial on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Opus 5.5 (model ID claude-opus-5-5)
- **Date:** 2026-11-09
- **Template version:** 0.1.0

This is a record of one run of the capability template on its own invented example. The company, its accounts, its competitors, the deals, the dates and the amounts are invented, and no client data was used. It shows what the template produced once, on one set of inputs. It is not a test in any company's environment.

This is the second run on the same example. An earlier run the same day, by a different model, showed that two rules at the heart of the template could be read two ways; steps 9 and 10 of the procedure and of the pasted instructions were rewritten, the example's findings were redone on the new rules, and the run recorded here was made on the revised instructions. What the earlier run found, and what was changed, is at the end.

## The inputs used

The inputs are exactly those in [the worked example](example.md), under "The inputs": the sales lead's facts, the closed-deal export of 26 rows, the ten deal notes and the previous review.

The run was a fresh session started from Claude Code with no tools and no access to any file. The template's instructions for an AI assistant and its output format were given as the session's instructions, and the inputs were sent as one message. That session did not see the example's own review, the earlier run, or the rest of the template. The same model, in a different session, had revised the instructions it followed and had read the example's review while doing so; the run tests whether the revised instructions can be followed to the intended result, and it is not an independent reading of what the template should produce.

## What came out

The complete output, as returned:

```
WIN-LOSS REVIEW: 1 July 2026 to 30 September 2026

For: Sales lead. From: closed-deal export of 5 October 2026, 26 rows; your stages (Enquiry, Site survey, Proposal, Negotiation); size bands (under $25,000; $25,000 to $75,000; over $75,000); your reason list (6 reasons); notes for 10 deals; previous review of 6 July 2026. Minimums: 20 deals in the set, 10 deals in a group, 5 deals for a firm finding, 20-point gap.

Coverage: Rows read: 24 (10 won, 14 lost, closed between 9 July 2026 and 29 September 2026). Not read: Q-325, open with no closed date; Q-298, closed 24 June 2026, before the period. Amount missing: none. Outcome: complete.

Headline: Half of this quarter's losses (7 of 14) ended at Proposal, more than at any other stage. Referral deals were won 7 of 10 times (70%) and Website deals 2 of 10 times (20%), a 50-point gap.

Win rate: overall 10 of 24 (42%).
By lead source: Referral 7 of 10 (70%); Website 2 of 10 (20%); Trade show 1 of 4, too few to read.
By deal type: New 7 of 20 (35%); Expansion 3 of 4, too few to read.
By segment: Manufacturer 4 of 11 (36%); Distributor 4 of 8, too few to read; Retailer 2 of 5, too few to read.
By size band: under $25,000 4 of 9, too few to read; $25,000 to $75,000 4 of 11 (36%); over $75,000 2 of 4, too few to read.

Where the losses ended: Enquiry 2 of 14 (14%). Site survey 3 of 14 (21%). Proposal 7 of 14 (50%). Negotiation 1 of 14 (7%). Stage not recorded 1 (7%).

Time and amounts: Median days from created to closed: won 72 (10 deals), lost 85 (14 deals). Won $425,000, median $31,250. Lost $568,000, median $41,000. Left out: none.

Why we lost, as the export records it:
  Price: 5 of 14 losses, $248,000. Deals: Q-302, Q-305, Q-308, Q-314, Q-318. Of these, 2 have a note naming a different reason: Q-308, Q-318. In the buyer's words: "Competitor A came in about 12% lower. We've gone with them." (Q-305, operations director, note of 28 July 2026)
  Lead time: 2 of 14 losses, $86,000. Deals: Q-310, Q-323. No note.
  Competitor: 3 of 14 losses, $137,500. Deals: Q-311, Q-312, Q-316. In the buyer's words: "Competitor A will also inspect the racking every year. You don't offer that." (Q-312, operations director, note of 20 August 2026)
  Timing: none.
  No decision: 2 of 14 losses, $41,000. Deals: Q-307, Q-322. No note.
  Not a fit: 1 of 14 losses, $12,500. Deals: Q-303. No note.
  Other, as recorded: none.
  Not recorded: 1, $43,000. Deals: Q-320.
Competitors named on lost deals: Competitor A: 3 (Q-305, Q-312, Q-316); Competitor B: 1 (Q-311). Named on won deals: Competitor A: Q-301. No competitor recorded: 10 lost deals.

Largest deals read:
  Lost: Q-305 · Account E · $84,000 · ended at Proposal: The export records Price, with Competitor A. The operations director wrote that Competitor A came in about 12% lower and they went with them (operations director; account executive's note of 28 July 2026).
  Lost: Q-312 · Account M · $76,000 · ended at Negotiation: The export records Competitor, with Competitor A. The warehouse manager was at our site survey. The operations director wrote that Competitor A will also inspect the racking every year and that we do not offer that (operations director; sales lead's note of 20 August 2026).
  Lost: Q-318 · Account T · $61,000 · ended at Proposal: The export records Price, with no competitor. The buyer said our price was fine and that they could not wait 14 weeks for installation (purchasing manager; account executive's note of 10 September 2026).
  Lost: Q-308 · Account H · $58,000 · ended at Proposal: The export records Price, with no competitor. The buyer said they liked the design but our earliest installation was after their peak season starts (operations manager; account executive's note of 6 August 2026).
  Lost: Q-316 · Account R · $52,000 · ended at Proposal: The export records Competitor, with Competitor A. The buyer said they are staying with Competitor A, which already supplies their shelving (purchasing manager; account executive's note of 3 September 2026).
  Won: Q-301 · Account A · $92,000: The warehouse manager walked the site survey with us and preferred our layout to Competitor A's. The deal came through an existing customer, and the export records the source as Referral (note of 9 July 2026).
  Won: Q-324 · Account Z · $81,000: The warehouse manager joined the site survey and asked for two changes to the layout (note of 29 September 2026).
  Won: Q-313 · Account N · $64,000: The site survey was with the warehouse manager and their safety lead. The safety lead asked for an inspection plan, which was sent with the proposal (note of 25 August 2026).
  Won: Q-306 · Account F · $46,000: The warehouse manager was at the site survey. Our installation date fitted their stock-take shutdown (note of 30 July 2026).
  Won: Q-321 · Account W · $35,000: The deal was signed after one revision. The purchasing manager ran the whole process (note of 22 September 2026).

What the wins share: The buyer's warehouse manager attended the site survey: stated in the notes of 4 of 5 won deals with notes, and of 1 of 5 lost deals with notes. The other notes do not say either way.

Findings: 2 firm, 5 thin
  1. Firm. Losses ended at Proposal on 7 of 14 lost deals (50%), more than at any other stage. Site survey is next with 3. Counted: 7 losses that ended at Proposal; contested: 0. Question for the sales lead: what do the seven lost proposals have in common, and what had each buyer said by the time the proposal went out?
  2. Firm. By lead source, Referral deals were won 7 of 10 (70%) and Website deals 2 of 10 (20%), a 50-point gap. Trade show (1 of 4, too few to read) takes part in the comparison and falls between the two. Counted: 10 closed Referral deals (the two groups are the same size); contested: 0. Question for the sales lead: how do Website enquiries differ from referrals by the time they reach a site survey or proposal?
  3. Thin, misses: firm-finding minimum (4 counted, 5 needed); group minimum (Expansion has 4 deals, 10 needed). By deal type, Expansion was won 3 of 4 (75% as a rate, too few to read) and New 7 of 20 (35%), a 40-point gap. Only New meets the group minimum, so there is no second gap to take. Counted: 4 closed Expansion deals (Q-304, Q-311, Q-315, Q-319); contested: 0. Question for the sales lead: does this pattern hold as more expansion deals close?
  4. Thin, misses: firm-finding minimum (3 uncontested, 5 needed). Price is the most recorded reason, on 5 of 14 losses, $248,000 (Q-302, Q-305, Q-308, Q-314, Q-318). Counted: 5 losses the export gives Price; contested: 2 (Q-308, Q-318; their notes name installation timing). Question for the sales coordinator: how is a close reason chosen when the buyer's words point to something else, and who confirms it?
  5. Thin, misses: firm-finding minimum (2 counted, 5 needed). The notes on 2 losses that the export records as Price name installation timing, which is Lead time on your list (Q-308, Q-318). The export gives Lead time to 2 other losses, Q-310 and Q-323, which have no notes. Lead time is named by either the export or a note on 4 losses. Counted: 2 losses the export gives Lead time (Q-310, Q-323); contested: 2 (Q-308, Q-318, added by notes and not counted). Question for the installation lead: on these four deals, what installation dates could we offer, and how did they compare with the dates the buyers needed?
  6. Thin, misses: firm-finding minimum (3 counted, 5 needed). Competitor A is named on 3 of 14 losses (Q-305, Q-312, Q-316) and on 1 win (Q-301). The export records the reason on those losses as Price (Q-305) and Competitor (Q-312, Q-316). Counted: 3 losses the export names Competitor A on; contested: 0. Question for the sales lead: on the 10 lost deals with no competitor recorded, was another supplier involved?
  7. Thin, misses: firm-finding minimum (4 counted, 5 needed); group minimum (5 won deals with notes and 5 lost deals with notes, 10 needed for each). The notes state that the buyer's warehouse manager attended the site survey on 4 of 5 won deals with notes (Q-301, Q-306, Q-313, Q-324) and on 1 of 5 lost deals with notes (Q-312). Notes cover only the largest deals. Counted: 4 won deals whose notes state it; contested: 0. Question for the account executives: on the other deals, which buyer roles attended the site survey?

Actions proposed, for the Sales lead to decide: 7
  1. Watch how many losses end at Proposal next quarter (this quarter: 7 of 14). Kind: watch next quarter. Owner: Sales lead. From finding 1.
  2. Watch win rate by lead source next quarter (this quarter: Referral 7 of 10, Website 2 of 10). Kind: watch next quarter. Owner: Sales lead. From finding 2.
  3. On every proposal, record the earliest installation date offered and the date the buyer needs. Kind: start recording. Owner: Sales coordinator. From findings 4, 5.
  4. Check each lost deal's close reason against the account executive's note before the deal is closed. Kind: start recording. Owner: Sales coordinator. From findings 4, 5.
  5. On every deal, record which buyer roles attended the site survey. Kind: start recording. Owner: Sales coordinator. From finding 7.
  6. On every lost deal, record a competitor, or "none". Kind: start recording. Owner: Sales coordinator. From finding 6.
  7. Watch the win rate on expansion deals against new deals next quarter. Kind: watch next quarter. Owner: Sales lead. From finding 3.

Carried from the last review: Record a close reason on every lost deal (Sales coordinator): close_reason filled on 13 of 14 lost deals this period (blank on Q-320). Bring the installation lead to site surveys on deals over $50,000 (Sales lead): not shown in the export; ask Sales lead.

At odds with the record: Q-308: the export says close reason "Price"; the note of 6 August 2026 says the operations manager liked the design but our earliest installation was after their peak season starts. Q-318: the export says close reason "Price"; the note of 10 September 2026 says the purchasing manager called our price fine and said they could not wait 14 weeks for installation.
Gaps in the record: Q-320: stage_at_close and close_reason blank. Competitor is blank on 10 lost deals, and a blank does not show that no competitor was involved.
Corrections to propose, for the sales coordinator to make: Q-308: close_reason, now "Price", proposed "Lead time", from the note of 6 August 2026. Q-318: close_reason, now "Price", proposed "Lead time", from the note of 10 September 2026.

Findings describe these deals; they do not show why they happened. Prepared from the closed-deal export of 5 October 2026 and the notes supplied. Nothing has been sent, and no record has been changed.
```

## What was observed

**What held.** Every part of the output format was produced, and nothing in the inputs called for a stop. Every figure that is counted agrees with the published example: the coverage, the win rates and which groups are too few to read, the losses by stage (shares adding to 99, as rounded one by one), the medians and totals, the reasons and their amounts, the competitors, the carried actions, the two items at odds with the record, the gap and the two corrections.

**The two rules this run was made to check.**

- *Small groups in a gap.* The run compared every group in a cut, including those shown as "too few to read". It produced the deal-type finding (expansion 3 of 4 against new 7 of 20, a 40-point gap) as thin, missing the group minimum and the firm-finding minimum, and noted that no second gap could be taken because only one deal type meets the group minimum. Segment (50 against 36) and size band (50 against 36) gave gaps of 14 points and no finding. On lead source it noted that trade show takes part and falls between referral and website, and kept the finding firm, as the example does.
- *Which deals count.* The run counted, for each finding, the deals the rewritten step 10 names: 7 losses at Proposal; 10 deals in the smaller lead-source group; 4 expansion deals; 3 uncontested Price losses; 2 losses recorded as Lead time, with the 2 deals the notes add treated as contested; 3 losses naming Competitor A; and 4 won deals for the warehouse-manager trait, with the lost deal not counted and both groups of notes (5 and 5) under the group minimum. Every firm or thin mark, and every test named as missed, is the same as in the example: 2 firm, 5 thin.

**Differences from the published example.**

- **What "Counted" holds.** On the Price finding the run wrote "Counted: 5 losses the export gives Price; contested: 2", while naming "3 uncontested" in the test it misses. On the Lead time finding it counted only the uncontested 2. The output format said "the deals counted, as step 10 defines them", which left room for both. The format now says the uncontested deals (see the end).
- **Buyers' words in the largest-deal lines.** The run paraphrased each buyer's reason where the example quotes it. The procedure says to quote it; the pasted instructions did not. They now do (see the end).
- **Actions.** The run proposed seven actions where the example proposes five: two "watch next quarter" actions for the two firm findings, where the example proposes changes to how the company sells, and recording actions for installation dates, competitors and attendance. All are kinds the template allows for their findings, with one exception worth knowing: action 4, "check each lost deal's close reason against the account executive's note before the deal is closed", is labelled start recording but is a change to how the record is kept, and it comes from thin findings.
- **Extras.** Under "Gaps in the record" the run added that competitor is blank on 10 lost deals; the template treats a blank competitor as none recorded, not as a gap. The coverage line gives the first and last closing dates (9 July to 29 September) where the example gives the period's bounds; the format allows either reading. One question goes to the installation lead, a role the inputs name only in the previous review.
- **Wording.** The headline, the questions on each finding and the phrasing of each line differ; the facts in them agree.

**Facts not in the inputs.** None. Every figure, quote and paraphrase traces to the export or a dated note.

**Where the instructions still leave room to guess.**

1. Whether the coverage line's dates are the period's bounds or the first and last closing dates.
2. Which roles may receive a finding's question; the template names none.
3. Whether a blank competitor belongs under "Gaps in the record".

## The earlier run, and what was changed

The first run, on 9 November 2026 in Claude Code by Claude Sonnet 5.5, used the template as first written and the same inputs. Its file read ran past the inputs and showed it the first half of the example's review (the win rates, the loss counts and the reasons) before it wrote its own; it then worked everything out again from the export and the notes. Its figures agreed with the example. It differed in these ways:

- It produced no deal-type finding. It read step 9's "the gap between the highest and lowest win rate among its groups" as comparing only groups whose percentage is shown, while the example compared a group of four shown as "too few to read".
- It listed a second trait, "the buyer asked for a change, or the proposal was revised", from two won deals' notes (Q-321, Q-324), and made it a thin finding. Step 8 gave no rule for when two notes state the same trait.
- For the warehouse-manager trait it counted only the 4 won deals toward the firm-finding minimum and so marked it thin, but recorded that counting all 5 deals whose notes state it, with the groups taken as all won and all lost deals, would have made it firm. The template did not say which deals "show" a finding, nor what the groups are for a trait.
- It recorded that the rounding rule covered win rates only, that the shares by stage add to 99, and that "contested" did not say whether a deal is measured against the export or against the finding.

Its own review was in other respects close to the example's: the same two firm findings, the same price, lead-time and competitor findings, and different but allowed actions.

Changed after the first run, before the run recorded above:

- **Small groups.** Every group in a cut is compared, including groups under the group minimum, which makes the finding thin for that test; a group of one deal is left out. When a small group is the highest or lowest, the gap among the groups that meet the minimum is a second candidate.
- **Deals counted.** For each kind of finding the procedure and the pasted instructions name the deals counted toward the firm-finding minimum: losses at the stage; the closed deals in the smaller of the two groups for a gap; the losses the export gives the reason, with deals the notes add or contest left out; the losses naming the competitor; the won deals whose notes state a trait, never the lost ones.
- **Groups compared.** For a gap, the two groups that make it; for a trait, the won deals with notes and the lost deals with notes, so a trait finding cannot be firm on the default five notes a side. "What to customize" now says so.
- **Contested.** A deal whose note names reason X where the export records Y is contested for both findings.
- **Traits.** Two notes share a trait only when each states the same fact; different facts are not joined under a wider label, which is why the example lists one trait.
- **Rounding.** Shares by stage are rounded like win rates, one by one, and need not add to 100.
- **The pasted instructions** now also carry the order of groups within a cut, asking once about an ambiguous date order, quoting from the largest agreeing deal under a reason, and leaving out a buyer's personal circumstances.
- **The output format.** Each finding carries a "Counted" line with the contested deals, and "No note" is capitalised as the example writes it.
- **The example's findings** 1 to 7 now show what was counted for each on these rules. The deal-type finding counts 4 deals, the smaller group, rather than 3, and the warehouse-manager finding also misses the group minimum.

Changed after the run recorded above, and not run again:

- The output format and the pasted instructions now say that "Counted" gives the uncontested deals, with contested deals separately.
- Step 7 of the pasted instructions now says to quote a buyer's reason in their own words, with the speaker's role, as the procedure already did.

Changed on 9 November 2026 after the independent review, and not run again:

- The coverage line's dates are now the period's start and end, not the first and last closing dates, in step 2, the pasted instructions and the output format. This settles the first guess point above; the recorded run gave the closing dates.
- A finding's question goes to a role named in the inputs, in step 10 and the pasted instructions. This settles the second guess point.
- The pasted instructions now list the blanks that go under "Gaps in the record" and say a blank competitor is not a gap. This settles the third guess point.
- The pasted instructions now define start recording as a field the review could not count, from now on; say "could not look: no [column] in the export" when the person says a column does not exist; allow a run on fewer than ten deals only if the person insists, with every finding thin; and have the headline name the two firm findings with the most deals when there are more. The procedure already said each of these.

**Limits of this record.** It is one run, by one model, on an invented example whose instructions that same model had just revised. It shows that the revised instructions can be followed to the intended findings on these inputs. It says nothing about other exports, other models, or a client's data.
