# Trial run: Prospect list by role and firm type

- **Product:** Claude, run in Claude Code
- **Model:** Claude Sonnet 5.5 (model ID claude-sonnet-5-5)
- **Date:** 2026-11-09

The inputs for this run are the invented example in [`example.md`](example.md): Firm K's facts, the request, the seven-row export and the ten page notes. They are all invented, and no client data was used. The model that ran it did not write the template. It read the template and the invented inputs only, followed the instruction block and the output format, produced the list, and only then read the published example's output and the reviewer checklist.

## Inputs used

The five input blocks under "The inputs" in `example.md`: your facts, the request, the export (7 rows, all eleven default headers present and matching), the public-page notes (10 notes, one marked not read) and no earlier lists. Permission to read pages was not given, so the run worked from the notes alone.

## What came out

```
PROSPECT LIST: Practice managers at accounting and architecture practices
in the Northfield region, 9 November 2026
Internal. For Firm K's own use; never shared with a prospect.
Status: Prepared for Alex. Nobody has been contacted, and nothing has
been sent or added to any system.
Coverage: Rows supplied 7; duplicates merged 1; left out for another
reason 1; firms graded 5. Public-page notes used 9; pages read by the
assistant 0; pages not read 1, listed under UNAVAILABLE.
Freshness limit: 90 days, from the request. Oldest signal used:
2 September 2026.
Defaults used: Earlier lists: none supplied, so duplicates were checked
within this export only. Permission to read pages: not given, so the
list rests on Alex's notes.

SEARCH PROFILE
Practice managers and operations managers, with the managing partner as
sponsor, at accounting and architecture practices of 10 to 60 total
staff headquartered in the Northfield region, where a public page shows
month-end billing or project set-up changing hands or systems.
Hard filters:
- Firm type: required, accounting or architecture, from the request
- Size: required, 10 to 60 total staff at the practice itself, from your
  facts and the request
- Headquarters: required, in the Northfield region, from your facts and
  the request
- Practice F: excluded, on your do-not-contact list, from your facts
Soft signals:
- A posting for an operations or practice-manager role: the work may be
  passing to a new owner
- A change of practice software: set-up and billing are being redone
- A posting asking for AI-tool experience: someone there may build in
  those tools
Disqualifiers:
- A published rule that bars AI tools from the work, from the request
Questions only a conversation can answer:
- Is the billing run or project set-up written down today?
- Would the managing partner sponsor the work?
- May the practice's AI tools be used on this work?

BY FIRM TYPE AND ROLE
Accounting / practice manager or operations manager / sponsor: managing
partner. Graded 3: Ready 0, Watch 1, Not now 0, Not a fit 2. Strongest:
Practice A, Watch. Where this role shows up in public: Practice A's
operations-coordinator posting (note 2).
Architecture / practice manager or operations manager / sponsor:
managing partner. Graded 2: Ready 1, Watch 1, Not now 0, Not a fit 0.
Strongest: Studio C, Ready. Where this role shows up in public: Studio
C's practice-manager posting (note 5).

FIRMS
1. Studio C (studio-c.example). Architecture practice. Selected from:
export row 3.
Size: 18, total staff, export row 3 (2 Nov 2026) and note 4 (6 Nov 2026).
Location: headquarters Northfield (export row 3; note 4, "our only
office in Northfield"); office Northfield (same).
Fit:
- Firm type: seen (export row 3, 2 Nov 2026; note 4, 6 Nov 2026)
- Size 10 to 60: seen, 18 (export row 3, 2 Nov 2026; note 4, 6 Nov 2026)
- Headquarters in the region: seen (export row 3, 2 Nov 2026; note 4,
  6 Nov 2026)
Signal 1:
  Observed: a practice-manager posting to "own project set-up and fee
  billing" that counts AI-template experience a plus (note 5, posted
  12 Oct 2026).
  May mean: set-up and billing are moving to one owner who may want them
  written down [Hypothesis]
  Weakens it: nothing found
  Unknown: Are set-up and fee billing written down today?
Signal 2:
  Observed: a Studio C partner spoke on running a small studio's back
  office at the Guild (note 6, session 15 Oct 2026).
  May mean: back-office running is a live topic for the partners
  [Hypothesis]
  Weakens it: nothing found
  Unknown: Is the topic a current worry or a past one?
Early-adopter sign: none seen. The posting asks for the experience; it
does not show anyone at the studio already builds templates (note 5).
Sponsor: managing partner (note 4; export row 3 title).
Door: Northfield Design Guild, which Firm K belongs to; a Studio C
partner spoke at its 15 Oct 2026 session (note 6).
Likely work: write down project set-up, then build the templates and
checklists (your facts).
Grade: Ready (every hard filter seen, a current signal, a sponsor seen,
a door in reach). Confidence: medium: the posting, the sponsor and the
door each rest on one page.
What would change it: the signals passing the freshness limit, 10 Jan
2027 (posting) and 13 Jan 2027 (talk), with nothing newer, would lower
it to Not now.
Next step: pursue now: Alex decides whether to ask the Guild for an
introduction.
To confirm in conversation: Are set-up and billing written down? Would
the managing partner sponsor? May the studio's AI tools be used?
Leave out when writing to them: nothing beyond your facts' off-limits
line.
In one sentence: Studio C passes every filter and has a current posting,
a sponsor role and a Guild door, so pursue now; unknowns are whether the
work is written down and who would sponsor it.

2. Practice A (practice-a.example). Accounting practice. Selected from:
export rows 1 and 7, merged.
Size: 24, total staff, export row 1 (2 Nov 2026) and note 1 (5 Nov
2026); row 7 agrees.
Location: headquarters Northfield (export row 1; note 1, "our only
office"); office Northfield (same).
Fit:
- Firm type: seen (export row 1; note 1, 5 Nov 2026)
- Size 10 to 60: seen, 24 (export row 1, 2 Nov 2026; note 1, 5 Nov 2026)
- Headquarters in the region: seen (export row 1, 2 Nov 2026; note 1,
  5 Nov 2026)
Signal 1:
  Observed: an operations-coordinator posting to "coordinate our
  month-end billing run and keep our client set-up checklists current"
  (note 2, posted 20 Oct 2026).
  May mean: the billing run and checklists are being handed to a new
  person [Hypothesis]
  Weakens it: nothing found
  Unknown: Is the billing run written down today?
Early-adopter sign: none seen.
Sponsor: managing partner (note 1, team page).
Door: none in reach. Your facts name the Guild only, and no source links
it to Practice A; no general contact route is in the notes.
Likely work: write down month-end billing (your facts).
Grade: Watch (a door is missing, so not Ready). Confidence: medium: the
signal rests on one page, the firm's own posting.
What would change it: a door found would make it Ready; look again by
18 Jan 2027 when the posting passes the freshness limit.
Next step: pursue now: Alex asks his own contacts whether anyone knows
Practice A.
To confirm in conversation: Is the billing run written down? Would the
managing partner sponsor? May the AI tools be used?
Leave out when writing to them: nothing beyond your facts' off-limits
line.
In one sentence: Practice A passes every filter and its posting points
at month-end billing, but there is no door; a door would make it Ready.

3. Studio D (studio-d.example). Architecture practice. Selected from:
export row 4.
Size: not stated. Note 7 gives six partners, which does not establish
total staff.
Location: headquarters Northfield (export row 4); office Northfield
(export row 4).
Fit:
- Firm type: seen (export row 4, 2 Nov 2026; note 7, 6 Nov 2026)
- Size 10 to 60: not observed on export row 4 and note 7, as of 6 Nov 2026
- Headquarters in the region: seen (export row 4, 2 Nov 2026)
Signal 1:
  Observed: "moving all projects to a new project management system this
  autumn" (note 8, posted 2 Sep 2026; 68 days old, inside the limit).
  May mean: project set-up is being redone [Hypothesis]
  Weakens it: nothing found
  Unknown: Does the move include fee billing, and is it finished?
Early-adopter sign: none seen.
Sponsor: not seen.
Door: none in reach. No source links Studio D to the Guild.
Likely work: write down project set-up (your facts).
Grade: Watch (size not observed). Confidence: low: total staff is
unknown.
What would change it: total staff confirmed at 10 to 60, plus a sponsor
and a door, would make it Ready; over 60 would make it Not a fit. Look
again by 1 Dec 2026 when the signal passes the freshness limit.
Next step: look again when total staff is found: Alex finds total staff
on a page he can read.
To confirm in conversation: How many staff? Does the move include
billing? Who would sponsor?
Leave out when writing to them: the careers page, which was not read.
In one sentence: Studio D has a current system change but its size is
unknown, with no sponsor or door, so it stays on Watch.

PEOPLE (supplied names only)
- Studio C: Noor H., Managing Partner, noor@studio-c.example. From export
  row 3, exported on 2 Nov 2026.
- Practice A: Sam R., Managing Partner, sam@practice-a.example. From
  export row 1, exported on 2 Nov 2026.
- Practice F: no name carried. Do not contact, since 3 March 2026.
Names not carried: 3 (rows 2 and 5, firms not a fit; row 6, on the
do-not-contact list).
Names collected from pages: none.

NOT A FIT
- Practice B: size disconfirmed, over 80 people (note 3, 5 Nov 2026) and
  85 in export row 2 (2 Nov 2026). Signal kept: none in the sources.
  What would change it: the size limit rising to 85 or more.
- Practice E: disqualifier, "Staff may not use generative AI tools for
  any firm work" (note 10, dated 1 Jul 2026). Signal kept: none in the
  sources. What would change it: the policy withdrawn; look again when
  the page changes.

LEFT OUT
- Practice A LLP (export row 7): duplicate of Practice A, same website;
  sources merged.
- Practice F (export row 6): on your do-not-contact list since 3 March
  2026. Not researched.

UNAVAILABLE
- https://studio-d.example/careers: not read, sign-in.
- Studio D's total staff: no source states it.

LIST CHECK
Graded: Ready 1, Watch 2, Not now 0, Not a fit 2.
Every fact in FIRMS and NOT A FIT has a source and a date: yes.
Firms with a hard filter not observed: 1 (Studio D).
Names carried: 2, all from the export. Names collected from pages: 0.
Do-not-contact marks carried: 1 (Practice F).
Text in the sources that read as an instruction, not followed: none.

SOURCES
- Your facts, supplied by Alex.
- The request, supplied by Alex, 9 November 2026.
- The export, 7 rows, exported on 2 November 2026.
- Notes 1 to 10 as listed in the inputs, with their addresses, publication
  dates where shown and read dates. Note 9 not read: sign-in.

Prepared for Alex. Nobody has been contacted. Alex decides who, if
anyone, is approached, and how.
```

## What was observed

- Every required part of the output format was produced, in order, and the list check adds up (1 Ready, 2 Watch, 2 Not a fit, 7 rows accounted for). The run did not stop for anything: the export headers all matched, and the facts page, firm types, roles and hard filters were present.
- The same five firms got the same grades as the published example, and the same rows were left out, merged or dropped as not a fit. Four confidences or next steps differed (below).
- Differences from the published example:
  - Studio C's early-adopter sign: the example counts the posting's request for AI-template experience as the sign. Following the template's definition (a source showing someone at the firm already builds templates, prompts or workflows), this run recorded none seen. The grade is still Ready on the current posting.
  - Studio C's confidence: medium here, high in the example.
  - Practice A's confidence: medium here (one page backs the posting), high in the example.
  - Studio D's confidence: low here because total staff is unknown, medium in the example, which names the headquarters instead.
  - Studio D's next step: here "look again when total staff is found", in the example "pursue now".
  - This run added a second signal for Studio C (the Guild talk) and put the do-not-contact mark for Practice F in PEOPLE as well as LEFT OUT.
- Ambiguities where the run had to choose:
  - Confidence is defined as being about the facts the grade rests on. For Practice A the grade turns on a missing door, which no source can show, so it is unclear which facts count. The run took the facts it could cite, including the posting.
  - The template says an early-adopter sign is "someone at the firm already builds" in AI tools, but the example's profile treats a posting that asks for the experience as the sign too. The two readings conflict.
  - The facts say "Northfield region" and the export says "Northfield". The request does not say what the region covers, though the format asks for "what it means". The run took Northfield as inside the region.
  - A Watch firm with a current signal "may still be pursue now". Studio D has a current signal but an unobserved size; the template does not say whether to pursue before the size filter is seen.
  - "Do-not-contact marks carried" has no clear home when the firm's names are not carried: the PEOPLE line expects a name. The run added a line with no name.
  - "Firms graded" counts the Not a fit firms in Coverage and LIST CHECK. This is inferred, not stated.
  - "Oldest signal used" does not say whether a disqualifier's date (Practice E, 1 Jul 2026) counts. The run counted only signals.
  - "Public-page notes used" does not say whether the note that could not be read counts. The run did not count it.
  - Whether an export title alone (Managing Partner on the export) counts as a sponsor "seen" at the firm was resolved by also citing the firm's own page.
- Facts not in the inputs: none were found in this run. The published example adds the advice "the Guild talk is your door, not an opening line" and a Studio C "posting closing" condition. These are guidance, not facts about a firm, but they are not in the inputs.
- Shortcomings of the trial: one run, one model, one product, on a small invented example with no instruction-like text, no header mismatch and no request to find an email, so most of the template's thirteen acceptance tests were not exercised. This is not a test in a client environment.

## What was changed afterward

Changed on 9 November 2026 after this run and an independent review of the published template, and not run again. The output and the observations above are as recorded and describe the template and the example as they stood at the run.

- **The early-adopter sign.** The template keeps its definition, a source showing someone at the firm already builds templates, prompts or workflows in AI tools, and the procedure and the pasted instructions now add that a posting which only asks for that experience is a signal, not the sign. The example now records "none seen" for Studio C, as this run did, keeps the posting's request in Signal 1, and no longer calls the request the early-adopter sign in its search profile. Studio C's grade is still Ready.
- **Confidence.** The procedure and the pasted instructions now say which facts count: every hard filter and every signal, early-adopter sign, sponsor and door the entry cites. Something not seen, such as no door, does not lower it, a hard filter not observed makes it low, and the export counts as one publisher. The example's confidences now follow that rule and match this run: Studio C medium (the posting and the door each rest on one page), Practice A medium (the posting rests on one page), Studio D low (total staff not observed).
- **A Watch firm with a hard filter not observed.** The template now says it is never "pursue now": look again once the filter is seen. The example's next step for Studio D now reads that way, as this run's did.
- **The Coverage line.** The procedure, the pasted instructions and the output format now say that firms graded includes Not a fit, that public-page notes used counts read notes only, and that the oldest signal used ignores a disqualifier's date. Each matches the choice this run made. The Coverage line in the template and the example was rewrapped.
- **Do-not-contact marks.** The output format's PEOPLE section now has a line with no name for a mark whose firm's names are not carried. The example carries Practice F that way, as this run did.
- **SOURCES.** The output format and the pasted instructions now ask for one line per source. This run's SOURCES block collapses notes 1 to 10 into one line; it is left as recorded.
- **The example's inputs.** The request now says what the Northfield region covers (the town and the villages within 20 miles). Every firm's headquarters is Northfield itself, so no grade depends on it.
- **The example's output.** Its Defaults used line now names the absent inputs and the defaults, as this run's did. The Guild events page is no longer listed as a place where the practice-manager role shows up in public, since it shows a partner. The advice that the Guild talk is a door and not an opening line, and the condition about the posting closing, were removed, since neither comes from the inputs; Studio C's change condition is now the signal passing the freshness limit on 10 January 2027.

This run's second signal for Studio C, the Guild talk of 15 October 2026, is not in the example: under the template, a signal whose page shows the event is over is stale, and the example uses the talk only as the source of the door.

A second set of edits was made on 9 November 2026, after a further independent review, and was not run again either. The output and observations above still describe the template as it stood at the run.

- **The not-observed label.** The procedure, the pasted instructions and the output format now write a hard filter that is not observed as "not observed ([sources], checked [date])", in the same shape as seen and disconfirmed. This run wrote "not observed on export row 4 and note 7, as of 6 Nov 2026", as the format then asked.
- **Not now.** The grading rule in the procedure and the pasted instructions now needs at least one signal, all of them stale. A firm with every hard filter seen and no signal at all is Watch, as acceptance test 5 expects. No firm in this run was affected.
- **Next step for a Watch firm.** The pasted instructions now carry the procedure's rule that a Watch firm with a current signal may still be pursue now, beside the rule for a hard filter not observed.
- **The sponsor.** The procedure and the pasted instructions now say that a contact title in the export counts as a source for the sponsor role, which settles the ambiguity this run noted.
- **The one-sentence line.** The output format's placeholder now reads: what the sources show, so whether to pursue now; what is still open; what would change the grade.
- **The request.** The template's inputs now ask for the reason behind each soft signal, and the example's request gives them, so the search profile's reasons trace to the input.
- **The example's output.** For accounting practices, where the practice-manager role shows up in public now reads "nothing in the sources", naming Practice A's operations-coordinator posting only as the nearest, since a coordinator is not that role; this run gave the posting itself. Studio D's leave-out line now reads "nothing beyond your facts' off-limits line" in place of the unread careers page, which this run also wrote.
