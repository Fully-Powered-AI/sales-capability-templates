# Win-loss review: an invented example

*Illustrative example with invented data.* The company, its accounts, its competitors, its people, the deals, the dates and the amounts below are all invented. The seller is an invented 45-person company that designs and installs pallet racking and shelving for warehouses. Its sales team is a sales lead, three account executives and a sales coordinator who keeps the deal record. First come the inputs the sales lead supplied, in full, then the review the workflow template returned.

## The inputs

### 1. Your facts (typed by the sales lead)

```
Review date: Monday 5 October 2026
Export taken: Monday 5 October 2026
Period: 1 July to 30 September 2026
Reads it: Sales lead

Our stages, in order: Enquiry, Site survey, Proposal, Negotiation.
Size bands: under $25,000; $25,000 to $75,000; over $75,000.

Our reasons for lost deals:
- Price: the buyer said our price was too high or over their budget.
- Lead time: we could not install by the date the buyer needed.
- Competitor: the buyer chose another supplier for a reason other
  than price.
- Timing: the buyer put the project off.
- No decision: the buyer went quiet or kept what they already had.
- Not a fit: we declined the work.

Minimums: the defaults.
Notes: for the five largest won and five largest lost deals.
```

### 2. The closed-deal export

```
deal_id,account,segment,deal_type,lead_source,amount,created_date,closed_date,outcome,stage_at_close,close_reason,competitor
Q-301,Account A,Distributor,New,Referral,92000,2026-04-20,2026-07-09,won,Negotiation,,Competitor A
Q-302,Account B,Manufacturer,New,Website,31000,2026-05-11,2026-07-14,lost,Proposal,Price,
Q-303,Account C,Distributor,New,Website,12500,2026-06-22,2026-07-16,lost,Enquiry,Not a fit,
Q-304,Account D,Distributor,Expansion,Referral,18000,2026-06-08,2026-07-21,won,Proposal,,
Q-305,Account E,Manufacturer,New,Trade show,84000,2026-04-27,2026-07-28,lost,Proposal,Price,Competitor A
Q-306,Account F,Manufacturer,New,Referral,46000,2026-05-18,2026-07-30,won,Negotiation,,
Q-307,Account G,Retailer,New,Website,22000,2026-06-15,2026-08-04,lost,Site survey,No decision,
Q-308,Account H,Manufacturer,New,Website,58000,2026-05-04,2026-08-06,lost,Proposal,Price,
Q-309,Account J,Manufacturer,New,Referral,27500,2026-06-01,2026-08-11,won,Proposal,,
Q-310,Account K,Manufacturer,New,Website,39000,2026-05-26,2026-08-13,lost,Proposal,Lead time,
Q-311,Account L,Retailer,Expansion,Trade show,9500,2026-07-06,2026-08-18,lost,Site survey,Competitor,Competitor B
Q-312,Account M,Distributor,New,Website,76000,2026-05-12,2026-08-20,lost,Negotiation,Competitor,Competitor A
Q-313,Account N,Manufacturer,New,Referral,64000,2026-05-19,2026-08-25,won,Negotiation,,
Q-314,Account P,Distributor,New,Website,14000,2026-07-13,2026-08-27,lost,Enquiry,Price,
Q-315,Account Q,Manufacturer,Expansion,Referral,21000,2026-07-01,2026-09-01,won,Proposal,,
Q-316,Account R,Distributor,New,Referral,52000,2026-06-02,2026-09-03,lost,Proposal,Competitor,Competitor A
Q-317,Account S,Retailer,New,Trade show,16500,2026-07-20,2026-09-08,won,Proposal,,
Q-318,Account T,Manufacturer,New,Website,61000,2026-06-09,2026-09-10,lost,Proposal,Price,
Q-319,Account U,Retailer,Expansion,Website,24000,2026-07-27,2026-09-15,won,Proposal,,
Q-320,Account V,Manufacturer,New,Referral,43000,2026-06-16,2026-09-17,lost,,,
Q-321,Account W,Distributor,New,Website,35000,2026-06-23,2026-09-22,won,Negotiation,,
Q-322,Account X,Retailer,New,Trade show,19000,2026-07-28,2026-09-24,lost,Site survey,No decision,
Q-323,Account Y,Manufacturer,New,Referral,47000,2026-06-29,2026-09-28,lost,Proposal,Lead time,
Q-324,Account Z,Distributor,New,Referral,81000,2026-05-25,2026-09-29,won,Negotiation,,
Q-325,Account AA,Distributor,New,Website,29000,2026-08-17,,open,Proposal,,
Q-298,Account AB,Retailer,New,Referral,15000,2026-04-06,2026-06-24,lost,Site survey,Timing,
```

### 3. Deal notes (pasted from the team's call notes and email)

```
Q-301, 9 July 2026 (account executive): The warehouse manager walked
the site survey with us and preferred our layout to Competitor A's.
Came to us through an existing customer.

Q-305, 28 July 2026 (account executive): Email from the operations
director: "Competitor A came in about 12% lower. We've gone with them."

Q-306, 30 July 2026 (account executive): Warehouse manager at the site
survey. Our installation date fitted their stock-take shutdown.

Q-308, 6 August 2026 (account executive): Call with the operations
manager: "We liked the design, but your earliest installation is after
our peak season starts."

Q-312, 20 August 2026 (sales lead): The warehouse manager was at our
site survey. Operations director by email: "Competitor A will also
inspect the racking every year. You don't offer that."

Q-313, 25 August 2026 (account executive): Site survey with the
warehouse manager and their safety lead. The safety lead asked for an
inspection plan, which we sent with the proposal.

Q-316, 3 September 2026 (account executive): Purchasing manager: "We're
staying with Competitor A. They already supply our shelving."

Q-318, 10 September 2026 (account executive): Purchasing manager: "Your
price was fine. We couldn't wait 14 weeks for installation."

Q-321, 22 September 2026 (account executive): Signed after one
revision. The purchasing manager ran the whole process.

Q-324, 29 September 2026 (account executive): The warehouse manager
joined the site survey and asked for two changes to the layout.
```

### 4. The previous review (the part the workflow template reads)

```
WIN-LOSS REVIEW: 1 April 2026 to 30 June 2026 (reviewed 6 July 2026)
Actions the sales lead accepted:
1. Record a close reason on every lost deal. Kind: start recording.
   Owner: Sales coordinator.
2. Bring the installation lead to site surveys on deals over $50,000.
   Kind: change how we sell. Owner: Sales lead.
```

## The output

**WIN-LOSS REVIEW: 1 July 2026 to 30 September 2026**

**For:** Sales lead. **From:** closed-deal export of 5 October 2026, 26 rows; your stages (Enquiry, Site survey, Proposal, Negotiation); size bands (under \$25,000; \$25,000 to \$75,000; over \$75,000); your reason list (6 reasons); notes for 10 deals; previous review of 6 July 2026. **Minimums:** 20 deals in the set, 10 deals in a group, 5 deals for a firm finding, 20-point gap.

**Coverage:** Rows read: 24 (10 won, 14 lost, closed between 1 July 2026 and 30 September 2026). Not read: Q-325, open; Q-298, closed 24 June 2026, outside the period. Amount missing: none. Outcome: complete.

**Headline:** Half the quarter's losses, 7 of 14, ended at Proposal. Referral deals won 7 of 10, and website deals won 2 of 10.

**Win rate:** overall 10 of 24 (42%).

- By lead source: Referral 7 of 10 (70%). Website 2 of 10 (20%). Trade show 1 of 4, too few to read.
- By deal type: New 7 of 20 (35%). Expansion 3 of 4, too few to read.
- By segment: Manufacturer 4 of 11 (36%). Distributor 4 of 8, too few to read. Retailer 2 of 5, too few to read.
- By size band: Under \$25,000 4 of 9, too few to read. \$25,000 to \$75,000 4 of 11 (36%). Over \$75,000 2 of 4, too few to read.

**Where the losses ended:** Enquiry 2 of 14 (14%). Site survey 3 of 14 (21%). Proposal 7 of 14 (50%). Negotiation 1 of 14 (7%). Stage not recorded 1 (7%).

**Time and amounts:** Median days from created to closed: won 72 (10 deals), lost 85 (14 deals). Won \$425,000, median \$31,250. Lost \$568,000, median \$41,000. Left out: none.

**Why we lost, as the export records it:**

- Price: 5 of 14 losses, \$248,000. Deals: Q-302, Q-305, Q-308, Q-314, Q-318. Of these, 2 have a note naming a different reason: Q-308, Q-318. In the buyer's words: "Competitor A came in about 12% lower. We've gone with them." (Q-305, operations director, note of 28 July 2026).
- Lead time: 2 of 14 losses, \$86,000. Deals: Q-310, Q-323. No note.
- Competitor: 3 of 14 losses, \$137,500. Deals: Q-311, Q-312, Q-316. In the buyer's words: "Competitor A will also inspect the racking every year. You don't offer that." (Q-312, operations director, note of 20 August 2026).
- Timing: none.
- No decision: 2 of 14 losses, \$41,000. Deals: Q-307, Q-322. No note.
- Not a fit: 1 of 14 losses, \$12,500. Deals: Q-303. No note.
- Other, as recorded: none.
- Not recorded: 1, \$43,000. Deals: Q-320.

**Competitors named on lost deals:** Competitor A: 3 (Q-305, Q-312, Q-316). Competitor B: 1 (Q-311). Named on won deals: Competitor A: Q-301. No competitor recorded: 10 lost deals.

**Largest deals read:**

- Lost: Q-305 · Account E · \$84,000 · ended at Proposal: export reason Price, competitor Competitor A; "Competitor A came in about 12% lower. We've gone with them." (operations director, note of 28 July 2026).
- Lost: Q-312 · Account M · \$76,000 · ended at Negotiation: export reason Competitor, competitor Competitor A; the warehouse manager was at our site survey; "Competitor A will also inspect the racking every year. You don't offer that." (operations director, note of 20 August 2026).
- Lost: Q-318 · Account T · \$61,000 · ended at Proposal: export reason Price; "Your price was fine. We couldn't wait 14 weeks for installation." (purchasing manager, note of 10 September 2026).
- Lost: Q-308 · Account H · \$58,000 · ended at Proposal: export reason Price; "We liked the design, but your earliest installation is after our peak season starts." (operations manager, note of 6 August 2026).
- Lost: Q-316 · Account R · \$52,000 · ended at Proposal: export reason Competitor, competitor Competitor A; "We're staying with Competitor A. They already supply our shelving." (purchasing manager, note of 3 September 2026).
- Won: Q-301 · Account A · \$92,000: the warehouse manager walked the site survey and preferred our layout to Competitor A's; the deal came through an existing customer (note of 9 July 2026).
- Won: Q-324 · Account Z · \$81,000: the warehouse manager joined the site survey and asked for two changes to the layout (note of 29 September 2026).
- Won: Q-313 · Account N · \$64,000: site survey with the warehouse manager and their safety lead; the inspection plan the safety lead asked for went with the proposal (note of 25 August 2026).
- Won: Q-306 · Account F · \$46,000: warehouse manager at the site survey; our installation date fitted their stock-take shutdown (note of 30 July 2026).
- Won: Q-321 · Account W · \$35,000: signed after one revision; the purchasing manager ran the whole process (note of 22 September 2026).

**What the wins share:** The warehouse manager attended the site survey: stated in the notes of 4 of 5 won deals with notes, and of 1 of 5 lost deals with notes.

**Findings: 2 firm, 5 thin**

1. **Firm.** Seven of 14 losses (50%) ended at Proposal. Counted: 7 losses that ended at Proposal; contested: 0. Question for the sales lead: What happens between sending the proposal and the buyer's answer on the deals we lose?
2. **Firm.** Lead source: referral deals won 7 of 10 (70%); website deals won 2 of 10 (20%), a 50-point gap. Trade show, 1 of 4, lies between them. Counted: 10 closed deals in the smaller of the two groups (each has 10); contested: 0. Question for the sales lead: What do referred buyers already have when they reach us that website enquiries do not?
3. **Thin, misses: group minimum (expansion, 4 deals); firm-finding minimum (4 deals counted).** Deal type: expansion deals won 3 of 4 (75%), a group too small to read on its own, with Q-304, Q-315 and Q-319 won and Q-311 lost; new deals won 7 of 20 (35%), a 40-point gap. Counted: 4 closed deals in the smaller group, expansion; contested: 0. Question for the sales lead: Why do existing customers who buy again choose us, in their own words?
4. **Thin, misses: firm-finding minimum (3 deals counted).** Price is the reason the export records most often: 5 of 14 losses (Q-302, Q-305, Q-308, Q-314, Q-318). Counted: 3 losses recorded as Price with no note naming another reason (Q-302, Q-305, Q-314); contested: 2 (Q-308 and Q-318, whose notes name installation lead time). Question for the account executives: When a buyer gives price as the reason, what else did they say?
5. **Thin, misses: firm-finding minimum (2 deals counted).** Lead time: the export records it on 2 losses (Q-310, Q-323), and notes name it on 2 more that the export records as Price (Q-308, Q-318), 4 in all. Counted: 2 losses recorded as Lead time (Q-310, Q-323); contested: 2 (Q-308, Q-318). Question for the sales lead: How many buyers this quarter needed installation sooner than we could offer it?
6. **Thin, misses: firm-finding minimum (3 deals counted).** Competitor A is named on 3 lost deals (Q-305, Q-312, Q-316) and on 1 won deal (Q-301). Counted: 3 lost deals the export names it on; contested: 0. Question for the sales lead: Where do we meet Competitor A, and what did the buyers who chose them say they valued?
7. **Thin, misses: firm-finding minimum (4 deals counted); group minimum (5 won and 5 lost deals with notes).** The warehouse manager attended the site survey: stated in the notes of 4 of 5 won deals with notes (Q-301, Q-306, Q-313, Q-324) and 1 of 5 lost deals with notes (Q-312). Counted: 4 won deals whose notes state it; the lost deal is not counted; contested: 0. Question for the account executives: On which other deals this quarter was the warehouse manager at the site survey?

**Actions proposed, for the sales lead to decide: 5**

1. Read the seven deals lost at Proposal with the account executives, and agree one change to what happens between sending a proposal and the buyer's answer. Kind: change how we sell. Owner: Sales lead. From finding 1.
2. Decide whether to ask existing customers for introductions. Kind: change how we sell. Owner: Sales lead. From finding 2.
3. Add a second close reason to the record, so that a buyer who names both price and lead time is counted under both. Kind: start recording. Owner: Sales coordinator. From findings 4 and 5.
4. Record who attended the site survey on every deal. Kind: start recording. Owner: Sales coordinator. From finding 7.
5. Read expansion deals and deals naming Competitor A again in the next review. Kind: watch next quarter. Owner: Sales lead. From findings 3 and 6.

**Carried from the last review:** Record a close reason on every lost deal (Sales coordinator): close_reason filled on 13 of 14 lost deals this period. Bring the installation lead to site surveys on deals over \$50,000 (Sales lead): not shown in the export; ask the sales lead.

**At odds with the record:** Q-308: the export says "Price"; the note of 6 August 2026 quotes the operations manager: "your earliest installation is after our peak season starts." Q-318: the export says "Price"; the note of 10 September 2026 quotes the purchasing manager: "Your price was fine. We couldn't wait 14 weeks for installation."

**Gaps in the record:** Q-320: stage_at_close and close_reason blank.

**Corrections to propose, for the sales coordinator to make:** Q-308: close_reason, now "Price", proposed "Lead time", from the note of 6 August 2026. Q-318: close_reason, now "Price", proposed "Lead time", from the note of 10 September 2026.

Findings describe these deals; they do not show why they happened. Prepared from the closed-deal export of 5 October 2026 and the notes supplied. Nothing has been sent, and no record has been changed.
