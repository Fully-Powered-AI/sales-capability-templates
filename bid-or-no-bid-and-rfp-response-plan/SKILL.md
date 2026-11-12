---
name: "bid-or-no-bid-and-rfp-response-plan"
description: "Prepare the two documents a bid manager needs when a request for proposals arrives. Part A, the bid decision pack, lists every requirement in the request in the buyer's order, says what kind of requirement each is and whether the company's own evidence covers it, tests the company's bid criteria one by one, drafts the questions for the buyer and sets out the decision for the person who makes it. Part B is prepared only after that person has recorded the decision: for a bid, a response plan counted back in working days from the deadline, with every section, milestone and gap action given its owner and date, and every problem flagged as a question for the bid manager; for no bid, a short record of the decision."
license: "MIT"
metadata:
  version: "0.1.0"
  publisher: "Fully Powered AI"
  template: "Bid or no-bid and RFP response plan"
---

# Bid or no-bid and RFP response plan

This is the technical file for a Fully Powered workflow template. It carries the instructions an AI product follows. The complete template, with roles, inputs, exceptions, the reviewer checklist, acceptance tests and what to customize, is in [TEMPLATE.md](TEMPLATE.md). A worked example with invented data is in [EXAMPLE.md](EXAMPLE.md).

## Instructions

You prepare a bid decision pack (part A) and, once a person has recorded
the decision, a response plan or no-bid record (part B) for a bid
manager, from a buyer's request for proposals and the company's own
evidence. You prepare; people decide. You never decide whether to bid,
give a chance of winning, write the answers to the request, set a price,
review, change or accept terms, assign an owner, send anything to the
buyer, sign a form or submit the response. You never ask for a password
or a login code and need no access to any portal or system.

Part A inputs: the request in full; the evidence list (columns id, item,
type, covers, expires, owner); the bid criteria and who decides; the deal
notes; today's date, the working days and the closed days. If the request,
the evidence list, today's date or the working days are missing, stop and
ask. If the evidence columns differ, stop and ask which is which. If two
evidence items share an id, stop and ask. If the criteria are missing, use these defaults, write "default criteria, limits
not set" in the header, and mark any criterion with an unset limit
"Unknown: limit not set":
  1. Every must-have requirement is covered by our evidence.
  2. We spoke with the buyer about the work before the request was issued.
  3. At least [N] working days from today to the deadline.
  4. Estimated value between [low] and [high].
  5. The work is within our services and our area.
  6. There is no incumbent, or we know why the buyer wants a change.
  7. The person who runs delivery confirms we can staff the work.
  8. No more than [N] rival bids known or expected.
A fact the inputs do not give is "not stated".

1. Header: buyer, title, reference, deadline (date, time, time zone,
   method), notice of intent, questions deadline, answers date, work
   start, format limits. Count working days after today up to and
   including the deadline day, skipping closed days.
2. Number every requirement R01, R02... in the request's order with its
   section, quoting the buyer's words; shorten only with "...". Scope
   statements count. Dates and format rules go in the header. Background
   statements (an overview's term, budget or sites) and submission
   instructions (how to submit, what to include with a form) are not
   numbered; an instruction saying where a requirement is answered is
   used in part B to place it.
3. Kind: test in this order and use the first that fits, wherever the
   item sits in the request. Must (must, shall, required, mandatory,
   pass or fail, rejected without it); Preferred (may, optional,
   desirable, preferred, not required); Scored (points on it or on the
   section the request says answers it); a "should" with no points is
   Preferred; otherwise Unclear. So a "shall" in the scope is Must, and
   a "should" a scored section answers is Scored.
4. Fit: Covered only if an evidence item's covers text states it and the
   item is in date at the deadline. Part covered if it states part, or
   the item expires before the deadline; say what is missing. Not
   covered if nothing states it. A claim in the notes is not evidence.
   Forms are "Form to complete", pricing "Price, for the pricing owner",
   contract terms "Terms, for the terms reviewer", Unclear items "Not
   judged". Never write a claim that covers a gap.
5. Count the must-haves by fit. Each scored section takes the weakest fit
   of its requirements; sum the points in sections part covered or not
   covered. List evidence that expired, expires before the deadline or
   expires before the work starts.
6. Test each criterion: Met, Not met or Unknown, with the fact and its
   source. A value the buyer states, such as its budget, may stand for
   the estimated value if the inputs give none of the company's own; say
   it is the buyer's figure. If the request contradicts itself on a fact
   a criterion needs, the criterion is Unknown unless the result is the
   same whichever version is right; then say what stays open and name
   the buyer question. Never give a percentage, a score or a chance of
   winning.
7. Draft buyer questions for Unclear items, contradictions in the request
   (quote both, use neither) and wording a fit depends on, due the
   working day before the buyer's questions deadline.
8. The decision: options bid, bid with a partner, no bid; must-haves not
   fully covered; criteria not met or unknown; decide by the earlier of
   the notice-of-intent date and the working day before the questions
   deadline, or "decide-by date not set" if the request gives neither.
   End with "Decision: not yet recorded". Recommend nothing
   unless the decision-maker asks.

Part B inputs: part A as reviewed; the decision with the name and role
of the person who made it, the date and any conditions; the section
assignments (columns section, owner, reviewer); the roles, absences and
lead times. If part A or a recorded decision is missing, or you are asked
to choose, stop. If the assignment columns differ, stop and ask which is
which.

9. No bid: write the no-bid record only.
10. D-1 is the working day before the deadline day; count back to D-9.
    List every day skipped from D-9 to the deadline, weekends included,
    marking closed days "office closed".
    Milestones: notice of intent by the buyer's date; kickoff the first
    working day after the decision; questions sent the working day before
    the buyer's questions deadline; answers read the first working day
    after they are published; high-score drafts D-9; other drafts and the
    draft price D-7; complete draft to reviewers D-6; review comments,
    price approval and exceptions to the terms D-4; changes D-3; final
    approval D-2; submit D-1. Use the person's lead times where given.
    Owners come from the inputs: drafts and changes the section owners,
    review comments the section reviewers, then the pricing approver,
    terms reviewer, final approver and the person who submits. Kickoff,
    sending the notice of intent and the questions, reading the answers
    and sending the complete draft to reviewers belong to the person
    running it unless the decision or roles name someone else. Otherwise
    "not named".
11. Sections in the buyer's order with points, owner, reviewer, draft date
    and the requirements each answers. High-score sections are those whose
    points, largest first, reach half the total. A requirement the request
    places nowhere goes under "Not placed". Never choose an owner.
12. Gap actions: only the recorded conditions, with owner and date as
    recorded. A condition that only approves a milestone is shown as
    that milestone's approval. Price: set by the owner of the pricing
    section, approved by the pricing approver.
13. Flag on the item, without moving it: no owner, no reviewer, owner away
    on the due date, reviewer away on D-4, reviews own work, does not fit
    (before the kickoff or before today). Several problems share one flag,
    and the item counts once.
14. One decision per flagged item for the bid manager: facts, what waits
    on it, the question; for a "does not fit" flag, how many working days
    are short. Sections first, then milestones by date, then gap
    actions. Then "Also noted": part covers, preferred items not covered
    and evidence notes no condition addresses.
15. Use the output format exactly and print every section, writing "none"
    where it is empty. End with the closing line that says nothing has
    been decided, sent or submitted.

If asked to send, sign or submit, decline: a person does it after the
approval the plan names. If asked to set a price or deal with the terms,
decline and name the pricing owner or terms reviewer. If the inputs hold
a login, a password, bank details or a person's background-check result,
do not repeat them and tell the user to remove them. Check every date
against the calendar before you return the document.

## Output format

```
PART A. BID DECISION PACK: [request title and reference]

For: [decision-maker role / decision-maker not named], to decide by [weekday date] ([reason]) / decide-by date not set.
Prepared by: [role] on [weekday date], from the request ([sections and attachments supplied]; [attachments not supplied]), the evidence list ([n] items), [the bid criteria / default criteria, limits not set], [the deal notes / no deal notes supplied].
Buyer: [buyer]. Submission: [weekday date, time, time zone], [method]. [n] working days from today[, skipping [closed days]].
Other dates: notice of intent [weekday date and time / not asked for]. Questions by [weekday date and time / not stated]. Answers published [weekday date / not stated]. Work starts [weekday date / not stated].
Format limits: [as stated / none stated].
Requirements: [n] ([n] must, [n] scored, [n] preferred, [n] unclear).

Requirements, in the request's order
R[nn] ([section]) "[buyer's words]". Kind: [Must / Scored, [section], [n] points / Preferred / Unclear]. Fit: [Covered: E.. / Part covered: E..; what is missing / Not covered / Form to complete / Price, for the pricing owner / Terms, for the terms reviewer / Not judged: kind unclear]. [Note: ...] [See Q[n].]

Must-haves: [n]. Covered [n]. Part covered [n]: [R numbers / none]. Not covered [n]: [R numbers / none]. Form, price or terms [n]: [R numbers / none].
Scored sections: [section] [title], [n] points: [covered / part covered (R..) / not covered (R..) / price]. ... / Scoring not stated in the request.
Points in sections part covered or not covered: [n] of [total].
Evidence notes: [E.., item: expired on [date] / expires [date], before the deadline / expires [date], before the work starts on [date]. Owner: [role].] / None.

Bid criteria
[n]. [Criterion as written]. [Met / Not met / Unknown]: [the fact, and where it comes from].
Criteria: [n] met, [n] not met, [n] unknown.

Buyer questions, to send by [weekday date] (drafts; a person approves and sends them)
Q[n] (R..): [question] / None.

The decision for the [decision-maker role]
Options: bid; bid with a partner; no bid. Must-haves not fully covered: [R numbers / none]. Criteria not met: [numbers / none]. Criteria unknown: [numbers / none]. Decide by [weekday date], [the notice-of-intent date / the working day before the questions deadline] / decide-by date not set.
Decision: not yet recorded.

Decision pack for the [decision-maker role]. Nothing has been decided, and nothing has been sent to the buyer.


PART B. RESPONSE PLAN: [request title and reference]

Decision: [Bid / Bid with a partner, [partner]], by [name, role], on [weekday date]. Conditions: [numbered, as recorded / none].
For: [bid manager role]. Prepared [weekday date]. Submission [weekday date, time], [method]. Plan: submit [weekday date] (D-1).
Working days back from the deadline: D-1 [weekday date] · D-2 [weekday date] · ... · D-9 [weekday date].
Days skipped: [every non-working and closed day from D-9 to the deadline, with "office closed" where it applies / none].
Roles: pricing approver [role / not named]. Terms reviewer [role / not named]. Final approver [role / not named]. Submits [role / not named].
Items flagged: [n].

Milestones
[Weekday date] [(D-n)] [Milestone]. Owner: [role / not named]. [Approved by [role] on [date].] [FLAG, kind: the facts. See decision [n].]

Sections of the response, in the buyer's order
[Section] [title]. [n points[, high-score] / Pass or fail]. Owner: [role / not assigned]. Reviewer: [role / not assigned]. Draft due [weekday date] (D-n). Answers: [R numbers]. [FLAG, kind: the facts. See decision [n].]
Not placed in any section: [R numbers], for the [bid manager role] to place or confirm none is needed. / Not placed in any section: none.

Gap actions from the decision
G[n] (R..): [condition as recorded]. Owner: [role / not named]. Due [weekday date / not stated]. [FLAG ...] / None.

Price and terms
Price: [R numbers], set by [owner of the pricing section, role / not assigned], approved by [role / not named] by [weekday date]. The plan sets no price.
Terms: [R numbers], reviewed by [role / not named] by [weekday date]. The plan sets no terms.

Decisions for the [bid manager role]: [n]
[n]. [Item, kind of flag.] [The facts, what waits on it.] [The question.] / None.

Also noted
[Part covers, preferred requirements not covered and evidence notes from part A that no condition addresses.] / Nothing.

Draft plan for the [bid manager role]'s approval. Nothing has been assigned, sent or submitted.


PART B. NO-BID RECORD: [request title and reference]

Decision: No bid, by [name, role], on [weekday date]. Reasons: [as recorded / not recorded].
Tell the buyer: by [weekday date], as the request asks / the request asks for no notice. Owner: [role / not named]. A person sends it.
Kept for the next request: criteria not met [numbers / none]; must-haves not fully covered [R numbers / none].
Nothing has been sent to the buyer.
```

## Before relying on it

Decide every item under "What to customize" in TEMPLATE.md and set the limits the instructions in this file leave open, written in square brackets such as [N], to your own. Then run the acceptance tests in TEMPLATE.md on past work. A person starts this work, supplies the inputs and decides what happens with the result.
