# Cold outreach sequence drafting: one trial on its invented example

- **Product:** Claude, run in Claude Code
- **Model:** Claude Fable 5.2
- **Date:** 2026-11-09
- **Template version:** 0.1.0

This is a record of one run of the template as it stood when the run was made; the edits made to the template since are listed below, under "Edited after this run". The inputs are the invented example published with this workflow template: Firm N, Prospect P, Dana, Lee, the job posting and every fact in them are invented. No client data was used, nothing was sent, and no one was contacted. One run on an invented example shows how the instructions behave once; it is not a test in anyone's working environment.

An earlier run the same day, on the first draft of the instructions, found eight places where the instructions had to be guessed at. The instructions were changed, and the run recorded here was made on the changed text. Both are described below: first the run, then the earlier findings and the change each led to.

**A limit on this record.** The earlier run was made before the example's own output had been read. This run was not: it was made in the same session that revised the instructions, after reading both the example's output and the earlier run. It shows what the revised instructions say when followed to the letter. It is not an independent second reading of them.

**Edited after this run, 9 November 2026.** Following the editorial review, the template was edited after the run recorded here, and the run was not repeated. The instruction block changed in four places: when the sender supplies the first note as sent, it is kept as Note 1 unchanged and only the remaining notes are drafted; "each has one ask" became "each before the last has one ask"; a slot is left for the sign-off when no voice sample shows one; and a named person with no stated address source, or a request to find or guess an address, is drafted at role level with the address left to the sender. The matching sentences were added to the template's inputs and procedure, and the sequence-settings default was reworded without changing it. The output format did not change. The published example was edited the same day: Note 2 lost the phrase "month in and month out", Note 3 lost the sentence "Nothing is migrated", and its Grounding now quotes the claims as drafted. The output and observations below are as recorded.

## The inputs used

The inputs block of [the worked example](example.md), pasted in full and unchanged: Firm N's facts page (what it does and for whom, three lines of proof, three things it never says, a two-page checklist to read, Dana as sender), Prospect P with two dated facts and a leave-out line, the ask (permission to send the checklist, later a 20-minute call), four notes on days 0, 4, 10 and 21, and one voice sample. No word limit, freshness limit or booking route was supplied.

The instruction block from the template came first, followed by the output format, as the template directs.

## What came out

The full pack, as returned.

```
OUTREACH SEQUENCE: Prospect P, operations manager
Status: Drafts for Dana. Not sent. Dana decides whether, to whom and when,
and sends each note.

ANGLE
Level: company. Two dated facts were supplied.
Facts used:
  Fact 1: job posting, "Accounts payable and job-cost clerk" (company
    careers page, 26 October 2026), both quotations.
Facts not used:
  Fact 2: the second service territory (company news page, 2 September
    2026): usable, but it does not serve the ask, which is about the
    month-end close.
Guess, stated nowhere as fact: a company advertising for a clerk to help
  get the close under ten working days may find that matching supplier
  invoices to jobs is what slows it. Not known. It appears only as the
  question in Note 2.
Shape: something small to read first: the checklist exists and is
  current, and the ask for Note 1 is permission to send it. No link in
  Note 1.
Voice: from the sample supplied. "Hi" and a first name, short sentences,
  a direct question, "Thanks," then "Dana".
Defaults used: 120-word limit (none was set). The later ask, a 20-minute
  call, was given no note; proposed: Note 3. Note 2 was left without an
  ask; proposed: a reply to a question. No freshness limit was set. No
  booking route was supplied, so the call is asked for by reply.

NOTE 1, day 0
Subject: Month-end close

Hi Lee,

Your posting for an accounts payable and job-cost clerk says the job is
to help get month-end close under ten working days.

Firm N keeps the books for specialty trade contractors with 20 to 100
employees: job costing, payables and the month-end close. Every client's
month closes on a written checklist the client can read.

We have a two-page version, "The 14-point month-end checklist for trade
contractors". Can I send it to you?

Thanks,
Dana
[identification line]
[opt-out line]

NOTE 2, day 4. Adds: the second task in the posting. Use only if there
has been no reply.
Subject: Supplier invoices and job numbers

Hi Lee,

Your posting for an accounts payable and job-cost clerk also lists
reconciling supplier invoices to job numbers.

Job costing and payables are part of the books Firm N keeps for
specialty trade contractors.

Is matching invoices to jobs what takes the days in your month-end
close, or is it something else?

Thanks,
Dana
[identification line]
[opt-out line]

NOTE 3, day 10. Adds: the founder ran a contractor's back office for nine
years. Use only if there has been no reply.
Subject: Back-office work at a trade contractor

Hi Lee,

Before starting Firm N I ran the back office of an electrical contractor
for nine years. Firm N keeps the books for specialty trade contractors
with 20 to 100 employees: job costing, payables and the month-end close.

Would a 20-minute call on how we run a month-end close be useful? Reply
with a time that suits and I'll confirm.

Thanks,
Dana
[identification line]
[opt-out line]

NOTE 4, day 21. The close. Use only if there has been no reply.
Subject: Month-end close: last note

Hi Lee,

This is my last note on this.

The two-page month-end checklist is still yours if you want it. Reply
and I'll send it.

Good luck with the hire.

Thanks,
Dana
[identification line]
[opt-out line]

WHAT ENDS THE SEQUENCE
Any reply or booking: the remaining notes stop, on every channel.
A yes: Lee gets what was offered (the checklist, or the call) and nothing
  more.
"Not now": stop until the date Lee gives.
"Leave me alone": permanent.
An away message: pause.
A bounce: stop. No other address is sought.

GROUNDING
"Your posting for an accounts payable and job-cost clerk says the job is
  to help get month-end close under ten working days" (Note 1): Fact 1,
  first quotation, 26 October 2026.
"Firm N keeps the books for specialty trade contractors with 20 to 100
  employees: job costing, payables and the month-end close" (Notes 1 and
  3): facts page, "What we do, and for whom".
"Every client's month closes on a written checklist the client can read"
  (Note 1): proof 1.
"a two-page version, 'The 14-point month-end checklist for trade
  contractors'" (Notes 1 and 4): facts page, "Something to read".
"Your posting ... also lists reconciling supplier invoices to job
  numbers" (Note 2): Fact 1, second quotation.
"Job costing and payables are part of the books Firm N keeps for
  specialty trade contractors" (Note 2): facts page, "What we do, and for
  whom".
"Before starting Firm N I ran the back office of an electrical
  contractor for nine years" (Note 3): proof 3.
"Good luck with the hire" (Note 4): Fact 1, the posting.
The asks: the checklist (Note 1, supplied), a reply to a question
  (Note 2, proposed) and a 20-minute call (Note 3, supplied as "later",
  the note proposed). Note 4 asks for nothing new.

READ BEFORE SENDING
Notes 1 and 2 quote the posting. Check the careers page on the day each
  goes; if the posting has changed or gone, the opening is no longer true.
Note 2's question is the guess put as a question. It says nothing about
  how Prospect P's close runs.
Note 4 wishes Lee luck with the hire. By day 21 the job may be filled.
No freshness limit was set. The oldest fact used is the posting of
  26 October 2026.
The asks in Notes 2 and 3 are proposed, not supplied note by note.
Note 3 asks for a time by reply because no booking route was supplied.
  If Dana has one, it is the only link the note should carry.

SLOTS FOR DANA
The identification line and the opt-out line. What the law requires where
  Lee is, including whether a note may be sent at all, is Dana's to
  settle.
The mailbox each note goes from.
A booking route for the call, if she wants one in place of a reply.
The checklist itself, sent only after Lee says yes.

LEFT OUT ON PURPOSE
Client names, any figure for time or money saved, prices, the second
territory and its name, and anything from the owner's personal posts.
```

## What was observed

**Every part of the output format was produced.** The status line, the angle with all seven lines, four notes on the supplied days, each with a subject, what ends the sequence, the grounding, the lines to read before sending, the slots and what was left out. Note 1 is 77 words from greeting to sign-off, inside the 120-word limit, and no follow-up is longer than it (55, 63 and 32 words). No note carries a link, an attachment or tracking. Nothing told the run to stop: the facts page was present, nobody asked for a figure, a client name, a deadline or sending, and the prospect was not marked "do not contact".

**Against the template's review checklist.** Items 1 to 7 hold on reading. Every claim about Prospect P and about Firm N appears under Grounding. The guess appears once, as Note 2's question. Each note before the close has one ask and the close asks for nothing new. Each follow-up adds one new thing and is no longer than the first note, and the last says it is the last. Nothing the leave-out line names is present. Items 8, 9 and 10 (the identification and opt-out lines, whether each fact is still true on the day, and the sending) are the sender's and were not done here.

**Where the instructions still leave a choice.**

1. **Which follow-up takes the later ask.** The instructions now say to propose one note for it and mark it proposed. They do not say which. This run chose Note 3, so that Note 2 could ask the easier question first.
2. **Which kind of new thing each follow-up adds.** Three kinds are allowed. Nothing says which to prefer or in what order. This run used a detail about the prospect in Note 2 and a line of proof in Note 3.
3. **Whether to use a usable fact.** The instructions now say it may be left out when it does not serve the ask. That is a judgement, and another run could keep the second territory.

## Differences from the published example

- The run and the example agree on the level, the shape, the days, the fact used and the fact left out, the ask in each note, what each follow-up adds, the sign-off, the slots and what is kept out.
- The example writes "trade contractors your size" and "the accounting software you already use", turning the facts page toward the reader, and flags both for checking. This run kept the facts page's own wording, which is safer and stiffer.
- The example uses proof 2 (the client's own software, nothing migrated) in Notes 1 and 3. This run did not use it at all.
- The example names the checklist as "a two-page version of that checklist"; this run gives its title. The example's subjects are lower case and shorter.
- The example's close reads more like a person: "it is yours for the asking". This run's is flatter.
- The example sets the pack out with headings and lists; this run returned it as plain text in the shape of the output format.

## Shortcomings of this run's output

Notes 1 and 3 repeat the same sentence about what Firm N does. That follows from writing each note to make sense on its own, but read in a row it is repetitive, and a sender would want to vary it. Proof 2, one of three lines of proof supplied, went unused. The notes are correct and grounded, and plainer than the published example. They need the sender's edit before they sound like a person, which is what the template says will happen.

## The earlier run, and what was changed after it

The first run that day used the first draft of the instructions. It produced every part of the format, but its Note 2 and Note 3 each added a line of Firm N's proof and asked for the call, which made them more about the sender than the example's are, and it used the second territory in Note 3. It recorded eight places where it had to guess. Each led to a change in the template, still numbered 0.1.0 because nothing had been released:

1. **Which later note carries which ask, and whether the close has one.** Changed: an ask given as "later" is proposed for one note, any note left without an ask gets a question to reply to, both are marked proposed, and the closing note needs no new ask.
2. **Whether a usable fact must be used.** Changed: a usable fact that does not serve the ask may be left out and is listed under "Facts not used" with that reason.
3. **What a follow-up may add.** The first draft, in both the procedure and the instruction block, allowed only something from the sender's facts page, while the published example's Note 2 added a second detail from the posting and closed on the guess put as a question. Changed: a follow-up may add a line from the facts page, one more supplied fact or detail about the prospect, or the guess put as a question.
4. **The closing note had no subject line in the output format.** Changed: it has one.
5. **Whether the subject rule covers the close.** Changed: it does, and the example's closing subject now names the reader's work.
6. **Limits the instruction block did not carry.** Changed: the block now carries the freshness limit, the "congratulations on old news" tell, and a booking as something that ends the sequence. With no freshness limit set, the date of the oldest fact used is given under "Read before sending".
7. **The word limit covered only the first note.** Changed: no follow-up is longer than the first note.
8. **A call with no way to book it.** Changed: a booking route is an optional input under the ask; without one, the note asks for a reply with a time.

The first run also showed four places where the published example did not follow the template. The example was corrected: it now signs "Thanks," and "Dana" as the voice sample does, carries a "Defaults used" line, lists every claim under Grounding, and flags "trade contractors your size" for checking. One sentence of the procedure was reworded at the same time, with no change in meaning.
