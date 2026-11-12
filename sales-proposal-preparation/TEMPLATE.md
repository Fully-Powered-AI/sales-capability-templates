# Sales proposal preparation

Workflow template, version 0.1.0.

## Purpose

Prepare a proposal pack for review from three things only: the buyer's stated requirements, the company's approved information and the agreed scope. The pack holds an account brief, a proposal draft in the buyer's format, an evidence checklist tying every claim to an approved source, and the open questions for the buyer and each internal reviewer. A named reviewer confirms commercial terms and claims before anything is sent. The assistant never invents a reference, a result or a price.

## When to use it and when not to

Use it when an RFP, tender, or security or procurement questionnaire arrives; when a buyer asks for a written proposal after a call; or when the buyer's answers or the agreed scope change.

Do not use it when:

- no scope has been agreed. A draft written without one invents the offer;
- the document is a contract redline. That goes to the contracts reviewer;
- the buyer wants pricing outside the approved schedule and no exception has been approved.

## Roles

- **Runs it:** the account executive who owns the opportunity.
- **Reviews scope and service claims:** the solutions lead.
- **Reviews commercial terms:** the finance or contracts reviewer.
- **Reviews references, approves and sends:** the sales lead. The assistant never sends anything.

## Inputs

1. **The buyer's stated requirements.** RFP or questionnaire, call notes, emails, from the opportunity record. If there are only call notes, the account executive confirms them with the buyer in writing before submission.
2. **Approved company information.** Service descriptions, security overview, case summaries, sample outputs, from the approved content library, each with a version. An item with no version or owner counts as unapproved; list a question for its likely owner.
3. **The reference register.** Which customers may be named, to whom, and when permission was recorded. If missing, name no reference.
4. **The agreed scope.** The scope note approved by the solutions lead, with inclusions and exclusions. If missing, stop.
5. **The approved pricing.** The schedule approved by the finance or contracts reviewer. If missing, use placeholders and list a question.
6. **The response format.** The buyer's format or the company's template. If neither, follow the buyer's requirement order.

## The procedure

1. **Check the inputs.** Confirm the requirements, scope note and pricing are present and current. If the scope note is missing, stop and ask the account executive. Record the version and date of every source.
2. **List the requirements.** Number each in the buyer's order, quoting the buyer's words and section. Mark each mandatory, scored or informational as the buyer states, or "unstated".
3. **Write the account brief.** One page: buyer, what they asked for, why now, who decides, agreed scope, fees by reference only, what is open. Every line cites a source. The account executive checks it against the call notes; the sales lead approves it before drafting.
4. **Match each requirement to evidence.**
   - State only what an approved source states. Do not round, extend or improve it.
   - If the source covers part of the requirement, draft that part and hold the rest.
   - If nothing covers it, hold the row and write no claim.
   - If notes or emails contradict the RFP, quote both and hold the row.
5. **References and results.** Name a reference only if the register records permission for this use within [your permission period]. State a result or figure only if an approved case summary states it, word for word.
6. **Commercial terms.** Copy fees, payment terms, contract length and discounts exactly from the schedule. Never calculate a total, apply a discount or accept the buyer's terms. If the buyer asks for different terms, quote both and hold the row for the finance or contracts reviewer. If the change would move contract value by more than [your threshold], flag the sales lead too.
7. **Draft the proposal.** Answer each requirement in order. For a held row, state the actual position from the source ("assessment completed, report not yet issued") and add a bracketed placeholder for the reviewer's decision.
8. **Build the evidence checklist.** One row per claim. Status is Ready, Held: question, or Copied, not calculated.
9. **Write the open questions.** For the buyer first, with section references; then for each internal reviewer by role. One sentence each.
10. **Return the pack** to the account executive, stating what is held and who must answer.
11. **Revise on answers.** Update the brief, draft and checklist; mark each question answered with its source and date.

## Exceptions and stop conditions

- **No agreed scope:** stop; the account executive gets the solutions lead's approval.
- **Guarantees, penalties, liability, indemnity, data protection or regulatory compliance:** hold and refer to the contracts reviewer. Draft no position.
- **A source older than [your review period] or with no owner:** treat as unapproved; ask its owner.
- **Asked to state something no source supports:** decline, hold the row and name the source that would be needed.

## Output format

```
ACCOUNT BRIEF: [Buyer], [request reference]
Buyer: [description] ([source])
What they asked for: [requirements] ([sections])
Why now: [reason the buyer gave] ([source, date])
Who decides: [roles] ([source])
Agreed scope: [inclusions]. Excluded: [exclusions]. ([scope note, date])
Fees: As set in [pricing schedule]. The brief states no figures.
Open before drafting: [held items]
Approved by: sales lead, [date]

PROPOSAL DRAFT
[Section and requirement, quoted]
[Response] [Held: placeholder for reviewer decision]

EVIDENCE CHECKLIST
[n]. Claim: [as drafted] | Source: [document, version] | Status: [Ready / Held: question / Copied, not calculated] | Checks it: [role]

OPEN QUESTIONS
For [buyer]: [n]. [question] ([section])
For [role]: [n]. [question]

Status: Prepared for review. Not sent.
```

## Reviewer checklist

1. Every claim in the draft is on the evidence checklist with an approved source. (Solutions lead)
2. Held rows appear only as disclosed gaps or agreed answers, never as claims. (Solutions lead)
3. Scope and exclusions match the approved scope note. (Solutions lead)
4. Every named reference has permission on record for this use. (Sales lead)
5. Fees, payment terms and contract length match the schedule or a written exception. (Finance or contracts reviewer)
6. Every requirement has a response or a stated reason for none. (Account executive)
7. The buyer's answers are recorded and reflected in the draft. (Account executive)
8. Approval to submit. (Sales lead)

## Acceptance tests

Proposed tests. None has been run.

1. **Complete inputs.** Every requirement has an approved source. Expected: full draft; every row Ready or Copied.
2. **No evidence.** The RFP asks for an independent security report; the security overview says the assessment is done and no report is issued. Expected: row held; the draft states the actual position with a placeholder; questions to the buyer and solutions lead. Fails if the draft says a report is available.
3. **Different terms.** RFP asks for net 45; the schedule says net 30. Expected: net 30 copied, both quoted, question to the finance or contracts reviewer.
4. **Reference without permission.** Notes mention a satisfied customer not in the register. Expected: not named; question to the sales lead.
5. **Contradiction.** Call notes say 280 laptops; the RFP says 320. Expected: both quoted, row held, question to the buyer.
6. **No scope note.** Expected: stops before drafting and asks for it.
7. **Pressure to overstate.** Asked to write "fully compliant with all security requirements". Expected: declines, holds the row, names the source needed.
8. **Ambiguity.** "24/7 support" without saying help desk or monitoring. Expected: covered part drafted; clarifying question to the buyer.

## Instructions for the AI assistant

```
You prepare sales proposal packs for review. You never send anything.

Use only the sources the user supplies: the buyer's stated requirements,
approved company information, the reference register, the agreed scope
note, the approved pricing schedule and the response format. Record the
version and date of every source you use.

If the scope note is missing, stop and ask for it. If pricing is missing,
use placeholders and list a question for the finance or contracts reviewer.

1. Number every buyer requirement in the buyer's order, quoting the buyer's
   words and section.
2. Write a one-page ACCOUNT BRIEF citing a source on every line. State fees
   by reference only, never as figures.
3. For each requirement, state only what an approved source states. If it
   covers part, draft that part and hold the rest. If nothing covers it,
   hold the row and write no claim. If the buyer's notes and documents
   disagree, quote both and hold the row.
4. Name a reference only if the register records permission for this use.
   State a result or figure only if an approved case summary states it.
5. Copy fees, payment terms and contract length exactly. Never calculate,
   discount or accept the buyer's terms; quote any difference and hold the
   row for the finance or contracts reviewer.
6. Write the PROPOSAL DRAFT in the buyer's order and format. For a held row,
   state the actual position and add [Held: placeholder for reviewer].
7. Build the EVIDENCE CHECKLIST: "[n]. Claim | Source | Status | Checks it",
   with status Ready, Held: question, or Copied, not calculated.
8. Write OPEN QUESTIONS: "For [buyer]" first, then "For [role]" for each
   internal reviewer. One sentence each.
9. End with: "Status: Prepared for review. Not sent."

Hold and refer, never draft, anything on guarantees, penalties, liability,
indemnity, data protection or regulatory compliance. If asked to state
something no source supports, decline, hold the row and name the source
that would be needed. Return the four sections in the order above.

If the user asks for the brief alone, stop after it: the sales lead
approves the brief before the draft goes to review. When the user supplies
answers, update the brief, draft and checklist, and mark each question
answered with its source and date.
```

## What to customize

- Where approved information lives, who owns each item, and [your review period] after which a source is out of date.
- The reference register and [your permission period].
- The pricing schedule that governs, and [your threshold] for flagging requested changes to the sales lead.
- Reviewer roles for scope, claims, terms and submission.
- Your proposal template.
- Which files the assistant may read in ChatGPT, Claude, Copilot or Gemini, and where the pack is saved.

## Version notes

- 0.1.0, 9 November 2026. Written by Fully Powered AI. Not yet tested in a client environment.
