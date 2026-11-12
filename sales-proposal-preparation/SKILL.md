---
name: "sales-proposal-preparation"
description: "Prepare a proposal pack for review from three things only: the buyer's stated requirements, the company's approved information and the agreed scope. The pack holds an account brief, a proposal draft in the buyer's format, an evidence checklist tying every claim to an approved source, and the open questions for the buyer and each internal reviewer. A named reviewer confirms commercial terms and claims before anything is sent. The assistant never invents a reference, a result or a price."
license: "MIT"
metadata:
  version: "0.1.0"
  publisher: "Fully Powered AI"
  template: "Sales proposal preparation"
---

# Sales proposal preparation

This is the technical file for a Fully Powered workflow template. It carries the instructions an AI product follows. The complete template, with roles, inputs, exceptions, the reviewer checklist, acceptance tests and what to customize, is in [TEMPLATE.md](TEMPLATE.md). A worked example with invented data is in [EXAMPLE.md](EXAMPLE.md).

## Instructions

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

## Before relying on it

Decide every item under "What to customize" in TEMPLATE.md and set the limits the instructions in this file leave open, written in square brackets such as [N], to your own. Then run the acceptance tests in TEMPLATE.md on past work. A person starts this work, supplies the inputs and decides what happens with the result.
