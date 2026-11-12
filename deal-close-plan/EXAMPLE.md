# Deal close plan: an invented example

*Illustrative example with invented data.* The companies, the people, the deal, the dates and the amounts below are all invented. The seller is an invented 40-person company that sells stock-planning software to food distributors; its people on this deal are an account executive, a solutions engineer, a sales lead and a finance director. The buyer, Account D, is an invented regional food distributor. First come the inputs the account executive supplied, in full, then the close plan the workflow template returned.

## The inputs

### 1. Deal facts (typed by the account executive)

```
Today: Monday 16 November 2026
Account: Account D. Deal: D-214, stock planning first year.
Target signature date: none set here; use the record's close date.
Outputs: both.
Our side: account executive (me), solutions engineer, sales lead,
  finance director.
Working days: Monday to Friday. Both companies are closed on Thursday
  26 and Friday 27 November.
Already promised: I told the operations director she will have the
  business case by Wednesday 18 November.
Signatures: we allow one working day for both signatures.
Covering note to: the operations director.
```

### 2. Deal record row (exported from the sales system)

```
deal_id,account,deal_name,stage,amount,close_date,next_step,next_step_date
D-214,Account D,Stock planning first year,Negotiation,63000,2026-11-30,Send order form,2026-11-13
```

### 3. The quote as sent

```
Quote Q-0418, 6 November 2026, for Account D
Stock-planning subscription, with expiry alerts on every stock line:
  $60,000 a year list, less 10% discount = $54,000 a year. Term: 12 months.
Setup and import of order history: $9,000 one time. Setup takes six
  weeks from signature.
Planner training: two sessions, included.
Billing: annually in advance.
First-year total: $63,000.
```

### 4. Buyer notes, in the order supplied

```
Discovery call, Thursday 22 October 2026. Notes by the account executive.
Operations director: "Planners find out stock is expiring when it's
already on the write-off report." "We write off about $18,000 of
expired stock every month." "Late deliveries cost us something like
$6,000 a month in customer penalties." "I want write-offs cut in half
by the end of March 2027, and the new system live by the start of our
spring season on 1 March 2027."

Demo call, Tuesday 3 November 2026. Notes by the solutions engineer.
Operations director: "The expiry alerts are the part my team got
excited about."
IT manager: "Anything that touches our order data goes through our
security review. We need ten working days once we have your
questionnaire answers, and nobody here signs until security has
cleared it."

Email from the operations director, Monday 9 November 2026.
"Our CFO wants to see the numbers before she agrees the budget, and she
decides in that meeting. I've asked her for Tuesday 24 November and am
waiting to hear back. Once she agrees, procurement needs ten working
days to set you up as a supplier and issue the purchase order.
Procurement will also ask for quarterly billing rather than annual in
advance. Our lawyers review your order form before anyone signs,
usually five working days. When the purchase order is out, the CFO
signs; she signs anything over $50,000."

My own note, Thursday 12 November 2026 (account executive).
Sent the security questionnaire answers to the IT manager today. Our
integration with their warehouse system is a big differentiator.
```

### 5. Our approval steps

```
- Billing other than annually in advance: the finance director approves
  before the order form goes out. 3 working days.
- Discount above 10% of list: the sales lead approves. 2 working days.
- Order form: sent by the account executive 1 working day after the
  approvals it needs.
- Countersignature: the sales lead signs for us on the day the buyer
  signs.
```

## The output

**DEAL CLOSE PLAN: Account D, Stock planning first year**

- **For:** Account executive. Deal D-214. Prepared Monday 16 November 2026.
- **From:** deal facts [F]; deal record row [R]; quote [Q] of Friday 6 November 2026; buyer notes N1 to N4, dated Thursday 22 October 2026 to Thursday 12 November 2026; your approval steps [A].
- **Target signature date:** Monday 30 November 2026 (from the record's close date). **Plan built on:** Friday 11 December 2026. **TARGET CANNOT BE MET:** earliest signature Friday 11 December 2026, 9 working days after the target.
- **Working days:** Monday to Friday. **Closed:** Thursday 26 November 2026, Friday 27 November 2026.

**PART 1. DRAFT FOR THE BUYER**

Nothing here has been shared with Account D; you decide what they see. Remove the source tags in square brackets before sharing.

**The business case for Account D**

1. **The problem today:** "Planners find out stock is expiring when it's already on the write-off report." (Operations director) [N1]. What it costs them: about \$18,000 of expired stock written off every month [N1].
2. **What they want:** write-offs cut in half by the end of March 2027 (Wednesday 31 March 2027) [N1]; the new system live by the start of the spring season on Monday 1 March 2027 [N1].
3. **What the offer does:** stock-planning subscription with expiry alerts on every stock line -> cutting write-offs in half [Q, N1]. Setup and import of order history, six weeks from signature -> live by Monday 1 March 2027 [Q, N1]. Planner training, two sessions -> not linked to a stated goal [Q].
4. **The arithmetic:** Investment: subscription \$60,000 a year list, less a 10% discount, \$54,000 a year for a 12-month term; setup \$9,000 one time; first year \$63,000 [Q]. Value at their own target: half of \$18,000 a month = \$9,000 a month; \$9,000 × 12 = \$108,000 a year [N1]. Recovery: \$63,000 ÷ \$9,000 = 7 months of value at target recover the first year's cost [Q, N1]. On Account D's own figures and target; not a forecast and not a promise of results.
5. **The cost of waiting:** each month the target is not met costs \$9,000 on their own figures (half of \$18,000) [N1]. They want to be live by Monday 1 March 2027 [N1]; setup takes six weeks from signature [Q]; Monday 1 March 2027 less six weeks is Monday 18 January 2027, the latest signature that meets it. Signatures on Friday 11 December 2026 put go-live on Friday 22 January 2027 [Q].
6. **What they valued:** "The expiry alerts are the part my team got excited about." (Operations director) [N2].

**Mutual action plan: signatures by Friday 11 December 2026**

1. Send the security questionnaire answers to the IT manager · Us · Owner: Account executive · Done Thursday 12 November 2026 [N4]
2. Send the business case to the operations director · Us · Owner: Account executive · Planned Wednesday 18 November 2026 · Must finish by Monday 23 November 2026 · Date agreed [F]
3. Internal approval before the order form goes out · Us (internal) · Owner: Finance director · Planned Thursday 19 November 2026 · Must finish by Wednesday 2 December 2026 · Date not agreed [A, N3]
4. Send the order form · Us · Owner: Account executive · Planned Friday 20 November 2026 · Must finish by Thursday 3 December 2026 · Date not agreed [A, R]
5. Review the business case and decide the budget · Buyer · Owner: CFO · Planned Tuesday 24 November 2026 · Must finish by Tuesday 24 November 2026 · Date not agreed [N3]
6. Security review · Buyer · Owner: IT manager · Planned Monday 30 November 2026 · Must finish by Thursday 10 December 2026 · Date not agreed [N2, N4]
7. Review the order form · Buyer · Owner: to be named by the buyer · Planned Tuesday 1 December 2026 · Must finish by Thursday 10 December 2026 · Date not agreed [N3]
8. Set up the supplier and issue the purchase order · Buyer · Owner: Procurement · Planned Thursday 10 December 2026 · Must finish by Thursday 10 December 2026 · Date not agreed [N3]
9. Signatures · Buyer · Owner: CFO; with Sales lead (Us) · Planned Friday 11 December 2026 · Must finish by Friday 11 December 2026 · Date not agreed [N3, A, F]

**PART 2. FOR YOU ONLY**

- **Target:** cannot be met: earliest signature Friday 11 December 2026, 9 working days after the target of Monday 30 November 2026.
- **Chain that sets the signature date:** 5 -> 8 -> 9. Step 5 is the CFO's budget decision, requested for Tuesday 24 November 2026 [N3]. Step 8 takes ten working days after it, to Thursday 10 December 2026 [N3]. Step 9 takes one working day after steps 6, 7 and 8 [F].
- **Spare working days:** none: 5, 8, 9. Step 2: 3; step 3: 7; step 4: 7; step 6: 8; step 7: 7.
- **Flags:**
  - Business case line 3, link not stated by the buyer: the quote lists expiry alerts on every stock line [Q] and the operations director wants write-offs cut in half [N1], but no note says the alerts will do that; N2 says only that her team "got excited about" them. The link is the assistant's reading; confirm it with the operations director before sharing.
  - Step 3, condition expected, not yet met: the quote bills annually in advance [Q]; the operations director writes that procurement "will also ask for quarterly billing rather than annual in advance" [N3]. The inputs do not say when procurement will ask, so step 3 waits on nothing. If the buyer does not ask, drop step 3; step 4 would then be planned for Tuesday 17 November 2026 and the signature date would not move.
  - Step 4, record date passed: the deal record dates "Send order form" Friday 13 November 2026 [R]; it is not reported done, and it waits on step 3, the finance director's approval of quarterly billing [A, N3].
  - Step 5, your side's attendee not stated: the inputs do not say whether anyone from your side is invited to the CFO's meeting, so no second owner is named. Ask the operations director whether she wants you there.
- **Owners and dates to confirm with the buyer:** Step 5: the operations director has asked the CFO for Tuesday 24 November 2026 and is waiting to hear back [N3]. Step 6: date worked out from the ten working days the IT manager gave [N2]; not agreed. Step 7: owner to be named by the buyer (the email says only "our lawyers" [N3]); date worked out from the five working days in the operations director's email [N3]; not agreed. Step 8: date worked out from procurement's ten working days [N3]; not agreed. Step 9: date not agreed with the CFO.
- **Not used in the business case until the buyer backs it:**
  - Late-delivery penalties, "something like \$6,000 a month" [N1]: the buyer gave no target for them, so no value is counted and the cost is left out of Part 1. Question for the next conversation: how much of the penalty cost does the operations director expect to remove, and by when?
  - "Our integration with their warehouse system is a big differentiator." [N4]: your own note; no buyer reaction is recorded. Question for the next conversation: does the warehouse connection matter to the operations director or the IT manager?
- **Internal lines:** Step 3: the finance director's approval of quarterly billing, needed because procurement is expected to ask for billing other than annually in advance [A, N3]; decide whether the buyer sees it.
- **Usual steps the inputs never mention:** none.
- **Your approval steps not needed:** Discount above 10% of list (sales lead): the quote's discount is 10%, not above it [Q, A].
- **Proposed changes to the deal record, for you to approve and make:**
  - close_date: now "2026-11-30", proposed "2026-12-11", because the earliest possible signature is Friday 11 December 2026 (chain 5 -> 8 -> 9).
  - next_step: now "Send order form", proposed "Send the business case to the operations director", because step 2 is your side's open step with the earliest planned date.
  - next_step_date: now "2026-11-13", proposed "2026-11-18", the planned date of step 2.

**Covering note to Operations director, a draft, not sent**

> Thank you for setting out how things work on your side. Here is the plan to signature we have put together from what you and your colleagues have told us, aiming for signatures on Friday 11 December. Could you confirm or correct these lines?
>
> - The CFO's review on Tuesday 24 November: has she confirmed the date?
> - Security review: finished by Monday 30 November, ten working days after our answers on 12 November.
> - Review of our order form: who will lead it for you? Five working days takes it to Tuesday 1 December.
> - Supplier setup and purchase order: ten working days after the CFO's decision, so Thursday 10 December.
> - Signatures on Friday 11 December: does that work for the CFO?
>
> You will have the business case on Wednesday 18 November, as promised.

**Source key:** F = your deal facts. R = deal record row for D-214. Q = quote Q-0418, Friday 6 November 2026. A = your approval steps. N1 = discovery call notes, Thursday 22 October 2026, by the account executive; speaker: operations director. N2 = demo call notes, Tuesday 3 November 2026, by the solutions engineer; speakers: operations director, IT manager. N3 = email from the operations director, Monday 9 November 2026. N4 = your own note, Thursday 12 November 2026.

Draft for the account executive. Nothing has been sent or shared, and no record has been changed.
