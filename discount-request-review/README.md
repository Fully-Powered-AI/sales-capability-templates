# Discount request review

Before a price below list goes to a customer, whoever approves it gets one page: the discount and what it costs in margin, every clause of your own written policy met or missed, who approves and in what order, and what the customer gives in return. A person decides; nothing is sent.

*Workflow template · Sales · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflow templates/discount-request-review/)*

## The outcome

Every discount request arrives on the approver's desk in the same shape, already checked against the rules your company wrote. The page shows the real size of the ask, line by line and for the whole deal, and what it takes out of your margin: always a bigger share of the margin than the headline percentage, since delivery costs the same at any price. Each clause of your policy is marked as met, missed or impossible to check, so an exception is visible at a glance instead of buried in an email thread.

The route is clear before anyone is chased: which approval level the request lands in, which other rules bring in another approver and why, and nobody added who the policy does not require. The page sets what the customer offers in return against what they have actually put in writing, and shows how this request compares with the decisions your company has already made. Sales gets a faster answer, finance gets a consistent one, and both are looking at the same facts.

The approvers still decide. The page ends with a blank decision line for each of them; the AI assistant approves nothing, suggests no price and tells the customer nothing.

## Who starts the work, and when

The sales lead, a sales operations coordinator or the finance partner who receives discount requests runs it as soon as a salesperson asks for a price their own authority does not cover, before anyone tells the customer yes. It runs again whenever the quote changes, because a changed quote is a new request.

The approvers the policy names read it and decide. The salesperson answers any question it raises.

## What they supply

- **The discount request,** on your own form or in an email: each line with its list and proposed price, the term, billing and payment terms, what the customer offers in return and the reason.
- **Your written discount policy,** with numbered clauses. This is the only rulebook the review applies; it brings none of its own.
- **Cost figures from finance,** if you want the margin worked out.
- **Your discount log,** if you keep one, so the review can show this customer's earlier discounts and comparable decisions.
- **A few facts:** the review date, who reads it, who handles contract terms, and what counts as a comparable decision.

## What comes out

One review in a fixed order:

1. **The request,** line by line, for the first year and the full term, with free months valued at list.
2. **Margin,** before and after the discount, and the share of it the discount removes.
3. **Against your policy,** every clause in turn, plus any ask your policy does not cover.
4. **The approval route,** with the clause behind each approver, how long an approval holds and who records it.
5. **This customer's earlier discounts and comparable decisions** from your log.
6. **Outside this review:** any contract terms the customer has asked for, listed for the person who handles them.
7. **Questions before deciding,** each for the person who can answer it, and a blank decision line for each approver.

A good review lets an approver decide without opening another file, and explain the decision to anyone who asks later.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Sales](https://fullypowered.ai/functions/sales/): the moment between a salesperson's ask and the customer's answer, handled the same way every time.
- [Finance and accounting](https://fullypowered.ai/functions/finance-and-accounting/): the finance partner sees margin and payment terms before a price is promised, not after.
- [Software technology](https://fullypowered.ai/industries/software-technology/): subscriptions, onboarding and multi-year terms make the true size of a discount easy to misread.
- [Professional services](https://fullypowered.ai/industries/professional-services/): fee reductions on engagements eat directly into thin delivery margins.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/): volume pricing requests from distributors and large accounts need a consistent answer.
- [Logistics and trade](https://fullypowered.ai/industries/logistics-and-trade/): rate requests on contracts and lanes arrive often and need checking against written rules.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): the founder can no longer approve every discount personally, and the rules have to work without them.

It sits beside [Sales proposal preparation](https://fullypowered.ai/workflows/sales-proposal-preparation/), which drafts the proposal the approved price goes into, [Stalled-deal review](https://fullypowered.ai/workflows/stalled-deal-review/), which shows deals waiting on an internal approval, and [Sales pipeline review](https://fullypowered.ai/workflows/sales-pipeline-review/), which shows the open pipeline those deals sit in.

## What has to change for your company

- **Write the policy down.** Approval levels, any further rules, the concessions you accept, and how the discount on a deal is measured. Number the clauses. The review is only as sharp as the policy.
- **Fix the request form,** so every request arrives with the same fields.
- **Agree the log's columns once.** If yours differ from the defaults, write the mapping down; the assistant stops and asks rather than guess.
- **Name the people:** who supplies costs, who handles contract terms, who tells the customer and who records the decision.
- **Your platform.** The instructions are written to be pasted into ChatGPT, Claude, Copilot or Gemini. It works from files you supply and needs no connection to your sales or accounting systems.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its invented example on 9 November 2026; the record is published with it, and lists the small edits made afterward that have not been run again. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on past requests your sales lead and finance partner remember well, plus hard cases written in advance, each with its expected behavior: a discount that sits exactly on a boundary, a concession promised but not in writing, a request with free months, an ask your policy does not cover, contract terms tucked into the request. The approvers check every figure and every clause line before anyone relies on it. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 9 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 9 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete workflow template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the workflow template drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related workflow templates

- [Sales proposal preparation](../sales-proposal-preparation/)
- [Stalled-deal review](../stalled-deal-review/)
- [Sales pipeline review](../sales-pipeline-review/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
