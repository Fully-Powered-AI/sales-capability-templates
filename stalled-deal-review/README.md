# Stalled-deal review

Your sales lead sees, from the record alone, which open deals have stopped moving, what each one's stage still lacks and whose move it is, and where every recent no ended and why. Nothing in your sales system is changed; corrections are proposed for a person to make.

*Workflow template · Sales · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/stalled-deal-review/)*

## The outcome

Every week the sales lead knows exactly which deals have gone quiet and why. Each stalled deal is read against the exit you wrote for its stage, so the review names the one thing still missing instead of a vague sense that a deal feels cold. It says whose move it is: the buyer's, yours, or a colleague's inside the company, such as a finance director who has not yet approved the terms. And it hands you one question that would get the deal moving again, addressed to the person who can answer it.

The same page keeps an honest log of every no in the period: the stage it ended at, the reason in the buyer's own words where anyone wrote them down, and what would bring the buyer back, if they said. Promises with no date are listed as exactly that, so they stop hiding. Where your notes and your sales system disagree, the review shows both and lets you decide.

## Who starts the work, and when

The sales lead, the owner, or whoever keeps the deal record runs it once a week, or the morning before a pipeline meeting. It is also worth running after a run of losses, to see where each one ended before anyone draws a lesson from them.

The sales lead reads the review and decides what happens to each deal. The deal's owner makes any correction to the record. The AI assistant sends nothing and changes nothing.

## What they supply

- **Your deal export.** One row per open and recently closed deal, from your sales system or spreadsheet, with the stage, the date it entered that stage, the next step with its owner and date, the last activity, and for closed deals the outcome and the reason.
- **Your facts.** The review date, the period for closed deals, who reads the review, and your stages in order, each with what must be true for a deal to leave it and how many days it should take.
- **Your deal notes.** Call notes and emails, each with the deal and the date, pasted as they are.
- **Last week's review,** so no deal quietly drops out of sight.

## What comes out

One review in a fixed order:

1. **Coverage.** How many deals were read, any that could not be, and any deal open last week that has vanished from the export.
2. **Stalled deals.** For each: the stage it stalled at, what that stage still lacks, whose move it is, why it counts as stalled, what the record shows, and the question that would settle it.
3. **Moving deals,** one line each.
4. **Promises with no date set,** deals waiting on the buyer, with your check date, and deals waiting on a colleague inside the company, with the decision they need.
5. **Where the noes ended.** Each lost deal under the stage it closed at, with the reason as the record gives it, whose call it was and what would reopen it.
6. **Deals won** in the period.
7. **At odds, gaps and corrections.** Where the notes and the export disagree, what the record does not show, and the corrections to propose, each with the note it comes from.

A good review is one the sales lead can take into the pipeline meeting and defend line by line, because every line points back to the record.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Sales](https://fullypowered.ai/functions/sales/): the weekly look at what is stuck, done the same careful way every time.
- [Professional services](https://fullypowered.ai/industries/professional-services/): engagements wait on a partner's sign-off or a client's budget cycle, and a quiet deal is easy to miss.
- [Software technology](https://fullypowered.ai/industries/software-technology/): deals pass through several stages and several people on the buyer's side, each a place to stall.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/): buying decisions wait on capital budgets and plant schedules, so knowing whose move it is matters.
- [Engineering firms](https://fullypowered.ai/industries/engineering-firms/): proposals sit with the client's board or funding body, and the firm needs to know which ones are still alive.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): the pipeline outgrows what the sales lead can hold in their head.

It sits beside [Sales call preparation brief](https://fullypowered.ai/workflows/sales-call-preparation-brief/), which prepares the meeting where the stall's question gets asked, [Objection answers and sales one-pager](https://fullypowered.ai/workflows/objection-answers-and-sales-one-pager/), which prepares the answer when a stalled buyer pushes back, and [Sales proposal preparation](https://fullypowered.ai/workflows/sales-proposal-preparation/), which drafts the proposal a deal at the proposal stage is waiting on.

Two sales workflow templates read the same record for different questions. [Sales pipeline review](https://fullypowered.ai/workflows/sales-pipeline-review/) shows the whole open pipeline each week, its value, age and coverage; this review looks only at the deals that have stopped and asks why. [Win-loss review](https://fullypowered.ai/workflows/win-loss-review/) reads a quarter of closed deals for patterns that hold across many of them; this review logs each recent no on its own, before anyone draws a lesson.

## What has to change for your company

- **Your stages and their exits.** Write down, for each stage, what must be true for a deal to leave it, who usually owns it and how many days it should take. The review is only as sharp as these exits.
- **Your export.** Agree the columns once. If your sales system names them differently, write the mapping down; the assistant stops and asks rather than guess.
- **Your notes habit.** A dated note with the buyer's own words is what turns "reason not recorded" into a reason you can act on.
- **Who reads it and who corrects.** Name who reads the review, and who makes corrections to the record after reading it.
- **Your platform.** The instructions are written to be pasted into ChatGPT, Claude, Copilot or Gemini. It works from files and notes you supply and needs no connection to your sales system.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its invented example in Claude on 9 November 2026 in two runs, with the instructions revised between them; the record of the second run is published with it. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on past weeks your sales lead remembers well, plus hard cases written in advance, each with its expected behavior: an export whose column names differ, a next step with no date, a buyer who said they would come back later, a lost deal with no stage, a note that contradicts the recorded reason. The sales lead checks every line against the record before anyone relies on it. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

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

- [Sales call preparation brief](../sales-call-preparation-brief/)
- [Objection answers and sales one-pager](../objection-answers-and-sales-one-pager/)
- [Sales proposal preparation](../sales-proposal-preparation/)
- [Sales pipeline review](../sales-pipeline-review/)
- [Win-loss review](../win-loss-review/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
