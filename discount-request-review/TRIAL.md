# Discount request review: tried on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-09

The inputs were the invented example's own. No client data was used. The assistant did not write the template.

## Inputs used

The five inputs in [the example](example.md), unchanged: the sales lead's facts (review date 5 November 2026, reader the sales lead, the managing director handles contract terms, comparable decisions the same product mix over six months), the discount request DR-2026-041 for Account K with the customer's email, the discount policy version 3, the cost figures and the six-row discount log.

## How it was run

The fenced instruction block and the output format of the template were followed on those inputs. One slip in method: the first command that displayed the example also printed the start of the example's output, up to the "Reason given" line, before the run began. The figures in the request section were therefore seen first and then recomputed by hand and checked twice, but that section is not an independent result. Everything from the competing-offer line onward, including margin, the policy test, the route, the log sections and the questions, was produced before the example's output was read.

## What came out

The review matched the published example in every figure and decision.

- **The request:** line 1 \$48,000 at list, \$37,200 proposed, 22.5% off; line 2 \$9,000 at list, \$6,000 proposed, 33.3% off. First year: \$57,000 at list, \$43,200 proposed, \$13,800 off (24.2%), measured as clause 1 defines it. Over 24 months: \$105,000, \$80,400, \$24,600 off (23.4%). No free items. Quarterly billing, 45-day payment terms.
- **Customer's concession:** the 24-month term, marked in writing from the customer, quoting the operations director's email of 3 November 2026. The competing offer was marked as stated by the account executive, no copy supplied.
- **Margin:** line 1 \$39,360 (82.0%) at list and \$28,560 (76.8%) after, 27.4% of margin removed; line 2 \$4,800 (53.3%) and \$1,800 (30.0%), 62.5% removed; whole first year \$44,160 (77.5%) and \$30,360 (70.3%), 31.3% removed.
- **Against the policy:** clause 3 Within (\$57,000 is under \$60,000); clause 4 Outside (onboarding 33.3% against 25%); clause 5 Within (a written 24-month term is on the clause's list); clause 7 Outside (45 days against 30); clause 8 Within (76.8%); clauses 1, 2, 6, 9 and 10 Not a test, each with where it is used. Outside: 2 (clauses 4 and 7). Not covered by the policy: billing quarterly in advance.
- **Route:** lands in clause 2.3 at 24.2%. Sales lead (2.3), finance director (2.3 and 7), head of delivery (4). The policy sets no order, so it was listed with 2.3's roles first. Approval holds 30 days; the sales lead records it.
- **Earlier discounts:** one, 14 May 2026, 10%, approved, expired on 13 June 2026.
- **Comparable decisions:** three on the same mix since 5 May 2026 (Accounts P, M and L), approved range 15% to 27%; this request is within it.
- **Outside this review:** for the managing director, the customer's own data protection terms.
- **Questions:** one, for the account executive, asking for the competitor's quote or its source.
- **Decision lines:** three, one for each approver, left blank. The closing sentence was included: nothing approved, sent or recorded.

## What was observed

Every part the format requires was produced. Nothing in the run called for a stop, and nothing in the inputs asked for an action. No fact appeared in either output that is not in the inputs; both outputs only calculate from them or quote them.

Differences from the published example: none in figures, clause marks, route, log sections, questions or decision lines. The wording of a few labels differed slightly.

Where the template left room to guess:

- **Sub-clauses.** The policy numbers its approval levels 2.1 to 2.4. The template says one line per numbered clause. This run, like the example, gave clause 2 one "Not a test" line and used 2.3 in the route; marking each sub-level separately is equally defensible.
- **Order of approvers.** Clause 2.3 reads "the sales lead and the finance director", which could be an order or just a list. The run treated it as no order. The template does not say how to read such a phrase.
- **"The subscription's margin" in clause 8.** The run tested line 1 alone (76.8%). The whole deal is 70.3%, also above the floor, so the result did not change, but the template does not say which figure to test when they could differ.
- **Whether a written email counts as the clause 5 concession.** The customer's sentence is conditional on the price. The template says to mark it in writing when quoted, and the run did; it does not say how to treat a conditional commitment.
- **Placeholder in the instruction block.** The block still contains "[your look-back]", the unfilled placeholder from the customizing section. This run used the six months given in the facts. A user who pasted the block as it stands would see a stray bracket.
- **"Per year" in the figures step.** The step asks for the whole deal per year and over the term, but the output format has lines only for the first year and the full term.

The reviewer checklist was walked through on the output and each item held. Only the first-year totals were checked against a second calculation; the 24-month totals follow from them. The acceptance tests were not run; this was one trial on one example, in one product, and says nothing about other products or real client use.

## Changed after this run

Changed on 9 November 2026 after an independent review of the published template, and not run again. The output and the observations above are as recorded and describe the template and the example as they stood at the run:

- **Sub-clauses.** The procedure and the pasted instructions now say that a clause with sub-clauses gets one line and the route cites the sub-clause, as this run and the example did.
- **Order of approvers.** Both now say that roles named together in one clause are not an order unless the policy says so, as this run read clause 2.3.
- **Which figure a clause tests.** Both now say to test the figure the clause names, and where it is unclear whether one line or the whole deal is meant, to show both and mark the clause "cannot check" if they fall on different sides of the limit. On the example, clause 8 names the subscription, and both figures are above the floor.
- **A conditional commitment.** Both now say to quote any condition the customer's sentence sets with it, as the example already does.
- **Placeholder in the instruction block.** "[your look-back]" in the pasted instructions now reads "the look-back period the person sets", with six months if it is not set.
- **"Per year" in the figures step.** The procedure now asks for the whole deal for the first year and over the full term, matching the output format.
- **A boundary between two levels.** The pasted instructions now also say to mark the routing clause "cannot check", as the procedure and acceptance test 12 already did.
- **Wording only.** The margin sentence now reads "the margin falls by the full amount of the discount"; acceptance test 6 was reworded for clarity; and the example's clause 3 line now ends "so the clause adds no one".
