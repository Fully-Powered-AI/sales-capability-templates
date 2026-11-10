# Bid or no-bid and RFP response plan

Capability template, version 0.1.0.

## Purpose

Prepare the two documents a bid manager needs when a request for proposals arrives. Part A, the bid decision pack, lists every requirement in the request in the buyer's order, says what kind of requirement each is and whether the company's own evidence covers it, tests the company's bid criteria one by one, drafts the questions for the buyer and sets out the decision for the person who makes it. Part B is prepared only after that person has recorded the decision: for a bid, a response plan counted back in working days from the deadline, with every section, milestone and gap action given its owner and date, and every problem flagged as a question for the bid manager; for no bid, a short record of the decision. The assistant prepares; it never decides whether to bid, gives a chance of winning, writes the answers, sets a price, reviews or accepts terms, assigns an owner, sends anything to the buyer or submits the response.

## When to use it and when not to

Use it the day a request for proposals, a tender, a request for quotation or a supplier questionnaire with a deadline arrives, and in any case before the buyer's deadline for questions. Run part B as soon as the decision is recorded, and again whenever the buyer's answers, an absence or a condition changes the dates.

Do not use it:

- to write the response itself. The answers are written by the section owners; the sales proposal preparation capability helps with that once the plan exists;
- to decide whether to bid. The decision-maker named in the bid criteria decides;
- to price the work, or to review, change or accept the buyer's terms. Those belong to the pricing owner and the terms reviewer;
- for a buyer conversation with no written request. There is nothing to check the evidence against.

## Roles

- **Runs it:** the bid manager, proposal lead or owner.
- **Decides whether to bid, and on what conditions:** the decision-maker named in the bid criteria, usually the owner or managing director.
- **Approves the plan and settles every flag:** the bid manager.
- **Writes and reviews each section:** the owner and reviewer named in the section assignments.
- **Sets the price; approves the price:** the pricing owner, who is the owner of the pricing section in the section assignments; the pricing approver.
- **Reviews the buyer's terms and lists any exceptions:** the terms reviewer the company names.
- **Gives final approval; submits:** the final approver; the person named to submit. Always people.

## Inputs

For part A:

1. **The buyer's request.** The full text: instructions, timetable, requirements, scoring, the response structure and the attachments supplied. If it is missing, stop. If the request refers to an attachment that was not supplied, list it as "not supplied" in the header and continue.
2. **The evidence list.** The company's own record of what it can show: one row per item. Default column headers: `id, item, type, covers, expires, owner`. `covers` says in plain words what the item proves; `expires` is the date it runs out, or the date a reference's permission ends, or blank. If the headers do not match these and the person has not said which column is which, stop and ask. If there is no evidence list, stop: fit cannot be judged without it.
3. **The bid criteria,** written before the request was read, and who decides. If the criteria are missing, use the default criteria below with their limits unset, and write "default criteria, limits not set" in the header. A criterion whose limit is not set is "Unknown: limit not set". If who decides is missing, write "decision-maker not named".
4. **Deal notes** from the bid manager: when and how the company learned of the request, any contact with the buyer before it was issued, the incumbent and what is known about it, the rival bidders known or expected, and whether delivery can be staffed. A fact the notes do not give is "not stated".
5. **Settings.** Today's date, the working days of the week, the days the office is closed, and who is running it. If today's date or the working days are missing, stop and ask.

For part B:

6. **Part A as reviewed.** If it is missing, stop: part A comes first.
7. **The decision, as recorded by the person who made it:** bid, bid with a partner (and the partner) or no bid; their name and role; the date; and any conditions. If it is missing, or if the person asks the assistant to choose, stop.
8. **Section assignments.** Default column headers: `section, owner, reviewer`, one row per section of the buyer's response structure. If the headers do not match, stop and ask. A section with no row is "not assigned".
9. **Roles and absences.** The pricing approver, the terms reviewer, the final approver and who submits; anyone away before the deadline, with dates; and any change to the default lead times. A role not given is "not named". The price is set by the owner of the pricing section in the assignments; if that section is not assigned, the pricing owner is "not assigned".

Default bid criteria, used only when none are supplied:

1. Every must-have requirement is covered by our evidence.
2. We spoke with the buyer about the work before the request was issued.
3. At least [N] working days from today to the deadline.
4. Estimated value between [low] and [high].
5. The work is within our services and our area.
6. There is no incumbent, or we know why the buyer wants a change.
7. The person who runs delivery confirms we can staff the work.
8. No more than [N] rival bids known or expected.

The assistant works from files and notes the person supplies. It needs no access to the buyer's portal or any company system and never asks for a password or a login code.

## The procedure

Part A, the bid decision pack:

1. **Check the inputs.** One request, one evidence list with the expected columns, today's date and the working days. If two evidence items share an id, stop and ask.
2. **Read the header facts.** The buyer, the request's title and reference, the submission deadline with its time, time zone and method, the notice-of-intent date, the questions deadline, the date answers are published, the date the work starts and the format limits. A date or limit the request does not give is "not stated". Count the working days after today up to and including the deadline day, skipping non-working weekdays and closed days, and list the closed days skipped. Dates and format rules go in the header, not in the register.
3. **Number the requirements.** Every numbered item or sentence that asks the respondent to have, do, provide or describe something becomes R01, R02 and on, in the order the request gives them, each with the request's section number. A statement of scope is numbered too, because the price must cover it. Background statements (an overview's term, budget or number of sites) and submission instructions (where, when and how to submit, or what to include with a form) are not numbered: dates and format rules go in the header, a background fact is used where a criterion or a fit needs it, and an instruction saying where a requirement is answered is used in part B to place that requirement. Quote the buyer's words; shorten only with "...".
4. **Give each a kind,** from the request's own wording. Test the kinds in this order and apply the first that fits, wherever the requirement sits in the request; so a "shall" in a scope section is Must, and a "should" that a scored section answers is Scored. **Must:** must, shall, required, mandatory, pass or fail, or a statement that a proposal will be rejected without it. **Preferred:** may, optional, desirable, preferred, or "not required". **Scored:** points are attached to it, or to the response section the request says answers it; give the section and its points. A "should" with no points is Preferred. **Unclear:** none of these.
5. **Judge the fit.** **Covered:** an evidence item's `covers` text states it, and the item is in date at the deadline. **Part covered:** an item states part of it, or the item has expired or will expire before the deadline; say exactly what is missing. **Not covered:** no item states it. A claim in the deal notes is not evidence; record it as "claimed in the notes, no evidence item". Three kinds of requirement are not judged against evidence: a form the buyer supplies to complete is "Form to complete"; pricing is "Price, for the pricing owner"; the buyer's contract terms are "Terms, for the terms reviewer". An Unclear requirement is "Not judged: kind unclear" and gets a question. Never raise a fit on general knowledge, and never write a claim that covers a gap.
6. **Count.** The must-haves by fit. Each scored section takes the weakest fit of the requirements it answers (not covered, then part covered, then covered), or "price" for a pricing section. Add up the points in sections that are part covered or not covered, out of the total. If the request gives no points, write "scoring not stated in the request".
7. **Write the evidence notes.** Every item used above that expired before today, expires before the deadline, or expires before the work starts, with its owner.
8. **Test the bid criteria.** Each criterion as written, then Met, Not met or Unknown, with the fact and where it comes from. Unknown means the inputs do not settle it. A value the buyer states, such as its budget, may stand for the estimated value when the inputs give no estimate of the company's own; say it is the buyer's figure. Where the request contradicts itself on a fact a criterion needs, the criterion is Unknown unless the result is the same whichever version is right; then give the result, say what stays open and name the buyer question. Never estimate a chance of winning, a score or a percentage.
9. **Draft the buyer questions.** One for each Unclear requirement, each contradiction inside the request (quote both versions and use neither), and each wording a fit depends on. Each names its R number. They are due the working day before the buyer's questions deadline. A person approves and sends them.
10. **Set out the decision.** The three options: bid, bid with a partner, no bid. The must-haves not fully covered, the criteria not met and the criteria unknown. The decide-by date is the earlier of the notice-of-intent date and the working day before the questions deadline; if the request gives neither, write "decide-by date not set". Recommend nothing unless the decision-maker asks.
11. **Return part A** with "Decision: not yet recorded" for the decision-maker.

Part B, after the decision is recorded:

12. **Check the decision.** It names a choice, a person, a role and a date. If not, stop.
13. **No bid:** write the no-bid record: the reasons as recorded, whether the request asks for a notice and by when, who tells the buyer, and the criteria not met and must-haves not covered from part A, kept for the next request. Stop there.
14. **Build the calendar.** D-1 is the working day before the deadline day, D-2 the working day before that, and so on back to D-9. List every day skipped from D-9 to the deadline: non-working days such as weekends, and closed days marked "office closed".
15. **Date the milestones.** Defaults: notice of intent by the buyer's date, if the request asks for one; kickoff on the first working day after the decision; buyer questions sent on the working day before the buyer's questions deadline; the buyer's answers read and the plan updated on the first working day after the answers are published; drafts of the high-score sections on D-9; all other drafts and the draft price on D-7; the complete draft to reviewers on D-6; review comments back, the price approved and any exceptions to the terms listed on D-4; review changes made on D-3; final approval on D-2; submission on D-1. Use the person's lead times where they differ. Each milestone names its owner by role, taken from the inputs: drafts and review changes belong to the section owners, review comments to the section reviewers, the price to the pricing owner and pricing approver, the exceptions to the terms reviewer, final approval to the final approver and submission to the person named to submit. The process milestones (kickoff, sending the notice of intent and the buyer questions, reading the buyer's answers and updating the plan, and sending the complete draft to the reviewers) belong to the person running it unless the decision or the roles name someone else. A milestone whose role the inputs do not give is "not named".
16. **List the sections** in the buyer's response structure, with points, owner, reviewer, draft date and the requirements each answers. The high-score sections are those whose points, taken largest first, reach at least half the total. Place a requirement where the request says it is answered; a requirement the request places nowhere goes under "Not placed", for the bid manager. Never choose an owner or a reviewer.
17. **List the gap actions.** Only the conditions in the recorded decision, each with its R number, owner and date as recorded. Add none of your own. A condition that only approves a milestone, such as the buyer questions, is shown as that milestone's approval instead.
18. **Price and terms.** Name who sets the price (the owner of the pricing section), who approves it and by when, and who reviews the terms and by when. Set no price and write, change or accept no terms.
19. **Flag the problems** on the item itself, without moving it: **no owner** or **no reviewer**; **owner away** on its due date, or **reviewer away** on D-4; **reviews own work** (owner and reviewer the same); **does not fit** (a date before the kickoff or before today). An item with several problems carries them in one flag and counts once.
20. **Write the decisions** for the bid manager: one per flagged item, with the facts, what waits on it and the question. Order: sections in the buyer's order, then milestones by date, then gap actions. For a "does not fit" flag, give how many working days are short. Recommend nothing unless asked.
21. **Also noted.** Each part cover, each preferred requirement not covered and each evidence note from part A that no condition addresses.
22. **Return part B** to the bid manager for approval. A person shares the approved plan with the team.

## Exceptions and stop conditions

- **No request, no evidence list, no today's date or no working days:** stop and ask.
- **Evidence or assignment headers that do not match the defaults:** stop and ask which column is which.
- **Asked to decide whether to bid, or to give a chance of winning:** decline. The criteria check is the record; the decision-maker decides.
- **Asked to write the answers to the request:** decline; the section owners write them.
- **Asked to set or change a price, or to review, change or accept the buyer's terms:** decline and name the pricing owner or the terms reviewer.
- **Asked to send the questions or the notice of intent, sign a form or submit:** decline. A person does each, after the approval the plan names.
- **The request contradicts itself,** such as two different site counts or dates: quote both, use neither, and write a buyer question.
- **The deadline has passed, or the default plan cannot fit before it:** flag "does not fit" on each date affected, say how many working days are short, and shorten nothing.
- **The inputs contain a portal login, a password or bank details:** do not repeat them; tell the person to remove them from the source.
- **The inputs contain a person's background-check result or other personal details:** do not repeat them; refer to the role.

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

## Reviewer checklist

1. Every requirement in the request appears once, in the request's order and quoted from it; no requirement has been added. (Bid manager)
2. Each kind follows the request's wording, and each scored requirement carries its section's points. (Bid manager)
3. Every "Covered" names an evidence item that states it and is in date at the deadline; no gap is written around. (Owner of each evidence item)
4. Every criterion result rests on a fact from the inputs, and no chance of winning appears anywhere. (Decision-maker)
5. Every buyer question is needed, names its requirement and is dated before the buyer's deadline. (Bid manager)
6. The decision is recorded by a named person before part B is used. (Decision-maker)
7. Every date in the plan falls on a working day and matches the calendar. (Bid manager)
8. Every owner and reviewer comes from the assignments, the roles or the decision, and the process milestones go to the person running it; none was chosen by the assistant. (Bid manager)
9. Price and terms are left to the pricing owner, the pricing approver and the terms reviewer. (Pricing approver, terms reviewer)
10. The plan is approved before it is shared, and nothing reaches the buyer without a person sending it. (Bid manager)

## Acceptance tests

Proposed tests. None has been run.

1. **Ordinary request.** Every must-have covered, criteria met, owners for every section. Expected: no flags; a decide-by date; part A ends "Decision: not yet recorded".
2. **Must-have with no evidence.** Expected: "Not covered" on that requirement, listed under the decision, criterion 1 not met; no claim written to fill it.
3. **Evidence that expires before the deadline.** Expected: "Part covered", with the date, and an evidence note naming its owner.
4. **Claim in the notes only.** The notes say "we can do this" with no evidence item. Expected: "Not covered", marked "claimed in the notes, no evidence item".
5. **Contradiction inside the request.** Two different site counts. Expected: both quoted, neither used, one buyer question.
6. **Evidence list with different headers.** Expected: stops and asks which column is which.
7. **Asked for a chance of winning, or to decide.** Expected: declines; points to the criteria check and the decision-maker.
8. **Part B with no recorded decision.** Expected: stops and asks for the decision.
9. **No bid.** Expected: the no-bid record only; no plan.
10. **Owner away on a due date, and an owner reviewing their own section.** Expected: both flagged on the section, one decision each; nothing moved or reassigned.
11. **Too little time.** The decision is recorded four working days before the deadline. Expected: "does not fit" on each date before the kickoff, with the working days short; nothing shortened.
12. **Asked to set the price, or to accept the buyer's terms.** Expected: declines and names the pricing owner or the terms reviewer.
13. **Portal login in the notes.** Expected: not repeated; the person is told to remove it.

## Instructions for the AI assistant

Paste this block as custom instructions, followed by the output format above.

```
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
```

## What to customize

- Your bid criteria and their limits, and who decides. Write them before the next request arrives, not while reading it.
- The evidence list: its columns, the types of item you keep, who owns each and how often it is checked for dates.
- The lead times: D-9, D-7, D-6, D-4, D-3, D-2 and D-1 suit a response of a few weeks; a long tender needs more days between drafts and review.
- The high-score rule. As written, the sections that together reach half the points are drafted two working days earlier.
- The roles: who sets and approves the price, who reviews the buyer's terms, who gives final approval and who submits.
- Your working days and closed days for the year.
- Where the approved plan lives and how owners mark a milestone done.
- Which files the assistant may read in ChatGPT, Claude, Copilot or Gemini.

## Version notes

- 0.1.0, 9 November 2026. Written by Fully Powered AI. Editorially reviewed. Tried once on its invented example in Claude on 9 November 2026; the record of that run is published with the example. Edited after that run, following an independent review, and not run again: the pasted instructions now carry the eight default bid criteria; the procedure and the pasted instructions now say that background statements and submission instructions are not numbered as requirements, that the process milestones belong to the person running it, that the owner of the pricing section sets the price, and that the days skipped include weekends; "three requirements" became "three kinds of requirement". Each of these settles an ambiguity the trial record lists in the way that run already chose. In the example, buyer questions Q1 and Q3 were reworded from the request's own words, the quote of section 7 was given in full, criterion 5 no longer relies on a site count the request contradicts, decision 1 no longer offers dates, an inference about Friday calls was cut, and two invented client names in the evidence list were changed to names not found in use. Edited again after a second independent review, and again not run: step 4 now says to apply the first kind that fits, wherever the requirement sits; step 8 now says a buyer's stated value may stand for the estimated value, and that a contradicted fact makes a criterion Unknown unless the result is the same either way; the pasted instructions now also carry the stop on duplicate evidence ids, the stop on assignment headers that do not match, "decide-by date not set", one count per flagged item and the working days short on a "does not fit" flag. In the example, criteria 4 and 5 now state the reason those two rules give, the price line no longer adds the optional energy-saving prices (R10), and decision 3 says only that Attachment D was not supplied. None of the stop conditions or refusals has been run. Not yet tested in a client environment, and not yet tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.
