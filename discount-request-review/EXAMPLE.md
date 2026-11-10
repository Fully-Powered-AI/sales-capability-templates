# Discount request review: an invented example

*Illustrative example with invented data.* The company, its customers, its people, the policy, the prices, the costs and the dates below are all invented. The seller is an invented 50-person company that sells field-service scheduling software to maintenance contractors, as a yearly subscription per user with a one-off onboarding package. Its commercial team is a managing director, a finance director, a sales lead, three account executives and a head of delivery. First come the inputs the sales lead supplied, in full; then the review the capability returned.

## The inputs

### 1. Your facts (typed by the sales lead)

```
Review date: Thursday 5 November 2026
Reads it: Sales lead
Contract terms: the managing director handles them
Comparable decisions: same product mix, last six months
```

### 2. The discount request (the company's request form, filled in by the account executive)

```
Request: DR-2026-041          Date: Wednesday 4 November 2026
Account: Account K            Salesperson: Account executive
Decision needed by: Tuesday 10 November 2026 (they want to sign by the 13th)

Line 1: Scheduling subscription, 40 users, per user per year.
        List $1,200. Proposed $930.
Line 2: Onboarding package, 1, one-off. List $9,000. Proposed $6,000.
Term: 24 months, price fixed for both years.
Billing: quarterly in advance. Payment terms: 45 days.
Free months or units: none.

What the customer gives in return: a 24-month term. See their email below.

Reason: Account K has a quote from a competitor at about $900 a user.
They are ready to sign for two years if we get close.

Contract terms the customer asked to change: their procurement team
wants their own data protection terms added to the order form.

Attached: email from Account K's operations director, 3 November 2026:
"Thanks for the call. If you can get to $930 a user, we will sign for
two years. Our procurement team will send over our data protection
terms separately."
```

### 3. The discount policy

```
DISCOUNT POLICY, version 3, effective 1 July 2026
Owner: finance director. Approved by the managing director.

1. This policy covers every quote below list price. The discount on a
   deal is the whole deal's first-year value at list minus its
   first-year value as quoted, as a percentage of the value at list.
2. Approval levels, by the discount on the deal:
   2.1 Up to 10%: the account executive.
   2.2 Over 10% and up to 20%: the sales lead.
   2.3 Over 20% and up to 30%: the sales lead and the finance director.
   2.4 Over 30%: the managing director, after the sales lead and the
       finance director.
3. A deal whose first-year value at list is $60,000 or more also needs
   the finance director, whatever the discount.
4. The onboarding package is not discounted by more than 25%. A deeper
   cut also needs the head of delivery.
5. A discount over 15% needs something from the customer, in writing:
   a term of 24 months or more, annual payment in advance, or a written
   agreement to act as a reference.
6. Free months and free users count as discount, at list price.
7. Our payment terms are 30 days. Longer terms also need the finance
   director.
8. The subscription's margin after discount stays at 70% or above.
   Below that, the finance director decides.
9. An approval holds for 30 days from the decision. If the quote
   changes after a decision, it comes back as a new request.
10. The sales lead records every decision in the discount log.
```

### 4. Cost figures (from the finance director)

```
Scheduling subscription: cost of delivery 18% of list price
  (hosting, support and licences), per user per year.
Onboarding package: cost of delivery $4,200 per package
  (delivery team time).
```

### 5. The discount log (exported by the sales lead)

```
decided_on,account,product,list_value,discount_pct,term_months,decision,decided_by,concession,valid_until
2026-05-14,Account K,Subscription,24000,10,12,approved,Account executive,none,2026-06-13
2026-07-22,Account L,Subscription + onboarding,51000,18,24,approved,Sales lead,24-month term,2026-08-21
2026-08-05,Account M,Subscription + onboarding,66000,27,24,approved,Sales lead; finance director,annual prepay,2026-09-04
2026-09-10,Account N,Subscription,30000,32,12,declined,Managing director,none,
2026-10-02,Account P,Subscription + onboarding,45000,15,12,approved,Sales lead,none,2026-11-01
2026-10-20,Account Q,Subscription,12000,8,12,approved,Account executive,none,2026-11-19
```

## The output

**DISCOUNT REQUEST REVIEW: Account K, DR-2026-041**

**For:** Sales lead. Reviewed 5 November 2026 against the Discount policy, version 3, effective 1 July 2026. Requested by the account executive on 4 November 2026. Decision needed by 10 November 2026.
**From:** request of 4 November 2026, 2 lines; costs supplied; discount log 6 rows, from 14 May 2026 to 20 October 2026.

**The request**

- **Line 1:** Scheduling subscription, 40 × list \$1,200 = \$48,000; proposed \$930 = \$37,200; discount \$10,800 (22.5%).
- **Line 2:** Onboarding package, 1 × list \$9,000 = \$9,000; proposed \$6,000 = \$6,000; discount \$3,000 (33.3%).
- **Whole deal, first year:** list \$57,000, proposed \$43,200, discount \$13,800 (24.2%), measured as clause 1 defines it.
- **Over the term of 24 months:** list \$105,000, proposed \$80,400, discount \$24,600 (23.4%).
- **Free months or units:** none.
- **Billing and payment:** quarterly in advance, 45 days.
- **Reason given:** "Account K has a quote from a competitor at about \$900 a user. They are ready to sign for two years if we get close." (account executive, request form, 4 November 2026).
- **Competing offer:** a competitor's quote at about \$900 a user, as stated by the account executive; no copy supplied.
- **What the customer gives in return:** a 24-month term: in writing from the customer: "If you can get to \$930 a user, we will sign for two years." (operations director, email, 3 November 2026).

**Margin**

- **Line 1, per year:** at list \$39,360 (82.0%); after the discount \$28,560 (76.8%); share of margin removed 27.4%.
- **Line 2, one-off:** at list \$4,800 (53.3%); after the discount \$1,800 (30.0%); share of margin removed 62.5%.
- **Whole deal, first year:** at list \$44,160 (77.5%); after the discount \$30,360 (70.3%); share of margin removed 31.3%.

**Against your policy**

- **Clause 1,** what the policy covers and how the discount is measured: Not a test: used in the figures (first-year value).
- **Clause 2,** approval levels: Not a test: used in the route.
- **Clause 3,** finance director for deals of \$60,000 or more at list: Within: first-year value at list \$57,000, under \$60,000, so the clause adds no one.
- **Clause 4,** onboarding discount no more than 25%: Outside: onboarding discounted 33.3%, over the 25% limit.
- **Clause 5,** something in writing from the customer above 15%: Within: discount 24.2%; the customer's written agreement to a 24-month term is on the clause's list.
- **Clause 6,** free months and users count as discount: Not a test: used in the figures; none requested.
- **Clause 7,** payment terms of 30 days: Outside: 45 days asked, over the 30-day standard.
- **Clause 8,** subscription margin after discount at 70% or above: Within: 76.8%.
- **Clause 9,** approvals hold 30 days; a changed quote is a new request: Not a test: used in the route.
- **Clause 10,** the sales lead records every decision: Not a test: used in the route.
- **Outside the policy:** 2: clauses 4 and 7.
- **Not covered by your policy:** billing quarterly in advance.

**Approval route**

Lands in clause 2.3 (over 20% and up to 30%) at 24.2%.

1. Sales lead (clause 2.3) → 2. Finance director (clauses 2.3, 7) → 3. Head of delivery (clause 4).

- **Added by other clauses:** finance director, clause 7: payment terms of 45 days, over the 30-day standard (already required by clause 2.3); head of delivery, clause 4: onboarding discount of 33.3%, over the 25% limit. The policy sets no order; listed with clause 2.3's roles first, then in clause order.
- **Approval holds:** 30 days from the decision, clause 9. **Decision recorded by:** sales lead, clause 10.

**This customer's earlier discounts**

- 14 May 2026, Subscription, 10%, approved, decided by the account executive; expired on 13 June 2026.

**Comparable decisions**

3 on Subscription + onboarding since 5 May 2026: 2 October 2026, Account P, 15%, approved, concession: none; 5 August 2026, Account M, 27%, approved, concession: annual prepay; 22 July 2026, Account L, 18%, approved, concession: 24-month term.

This request at 24.2% is within the approved range of 15% to 27%.

**Outside this review**

For the managing director: "their procurement team wants their own data protection terms added to the order form."

**Questions before deciding: 1**

1. For the account executive: can you supply the competitor's quote, or say where the figure of about \$900 a user comes from?

**Decisions, one line for each approver on the route**

- Sales lead (clause 2.3): [ ] Approve as requested [ ] Approve with changes: ________ [ ] Decline Name: ________ Date: ________
- Finance director (clauses 2.3, 7): [ ] Approve as requested [ ] Approve with changes: ________ [ ] Decline Name: ________ Date: ________
- Head of delivery (clause 4): [ ] Approve as requested [ ] Approve with changes: ________ [ ] Decline Name: ________ Date: ________

Prepared on 5 November 2026 for the approvers' decision, from the request, the policy and the files supplied. Nothing has been approved, sent to the customer or recorded.
