# Sales call scorecard

After a sales call, your sales lead sees how it went against your team's own criteria, each point backed by the words actually said, where the call left the deal, and one focus for the next call. It reviews a call, never a person, and gives no score for anyone's file.

*Workflow template · Sales · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflow templates/sales-call-scorecard/)*

## The outcome

Coaching starts from what was said on the call rather than from memory or impression. For every criterion your team has written down, the sales lead sees whether the call showed it, showed part of it, missed it, or cannot be judged from what was recorded, with the exact words behind each mark and the time they were said.

The scorecard keeps two things apart that are easy to blur. What the buyer actually said, in their own words, sits in one place. What your salesperson said about the buyer's situation, and the buyer only nodded along to, sits in another. When your salesperson names a figure and the buyer answers "probably", the scorecard records whose figure it was.

It ends with a few things that went well, a few to work on, each with a specific line to try next time, and a single focus for the next conversation with this buyer. There is no overall score, no grade and no ranking. It is a tool for a coaching conversation, and it says so on the page.

## Who starts the work, and when

The sales lead starts it after a call worth coaching on: a new salesperson's early discovery calls, a demo that went quiet afterwards, a pricing conversation the team can learn from. A salesperson can also run it on their own call before sitting down with the sales lead.

The sales lead reads the draft, decides what to share and holds the conversation. The salesperson owns the focus for the next call and updates the deal record if anything should change. The AI assistant sends nothing and changes nothing.

## What they supply

- **The call.** A transcript from your meeting tool, with timestamps and speaker names, or the salesperson's own notes when there is no recording.
- **Your criteria.** Your team's list of what a good call of each type includes, each written as something a listener could hear. A starter list is included for teams that have not written one yet.
- **Who was on the call.** Each person's side and role, so every line is placed correctly.
- **The call facts.** The date, the account and the type of call.
- **The goal and the last focus,** if you have them: what the salesperson set out to achieve, and what you agreed to work on after the last call you reviewed together.

## What comes out

One scorecard in a fixed order:

1. **The header,** with the source, any gaps in the recording, and how many criteria landed in each mark.
2. **A headline** of two sentences: what stood out, and where the call left the deal.
3. **Each criterion,** marked with its evidence and what was missing.
4. **The goal for the call,** part by part.
5. **Talk balance,** as an estimate from a transcript, never guessed from notes.
6. **Where the call left the deal:** the next step and what each side promised, with dates.
7. **What the buyer said,** in their words, kept apart from what your side asserted.
8. **The coaching note,** with one focus for the next call and a check on the last one.
9. **The limits** of what one call can show.

A good scorecard is one the salesperson reads and recognizes, because every mark points to a line they can find in the call.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Sales](https://fullypowered.ai/functions/sales/): coaching on real calls, done the same way every time and against the same written standard.
- [Customer success and account management](https://fullypowered.ai/functions/customer-success-and-account-management/): account reviews and renewal conversations deserve the same careful look as new business.
- [Software technology](https://fullypowered.ai/industries/software-technology/): discovery calls and demos run every week, and every one can be recorded and reviewed.
- [Professional services](https://fullypowered.ai/industries/professional-services/): partners and business developers learn faster from their own conversations than from a training deck.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/): agencies pitching new clients can see whether the brief they needed was actually heard.
- [Insurance](https://fullypowered.ai/industries/insurance/): brokers and account teams talk to clients constantly, and good questions decide what gets placed.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): when new salespeople join faster than the sales lead can sit in on their calls.

It sits beside [Sales call preparation brief](https://fullypowered.ai/workflows/sales-call-preparation-brief/), which sets the goal the scorecard checks, [Stalled-deal review](https://fullypowered.ai/workflows/stalled-deal-review/), which looks at deals that stop moving, and [Objection answers and sales one-pager](https://fullypowered.ai/workflows/objection-answers-and-sales-one-pager/), which prepares answers for the concerns the scorecard finds.

## What has to change for your company

- **Your criteria.** Write each one as something a listener could check from the words alone, and keep the list short enough to coach from. The scorecard marks only what your criteria ask for.
- **Your call types,** and which criteria belong to each.
- **Calibration.** Have two sales leads mark the same few calls separately, compare their marks criterion by criterion, and tighten the wording wherever they disagree.
- **Who sees it.** Decide when the salesperson receives the scorecard and where scorecards are kept.
- **Your recording policy.** The workflow template reads a transcript you supply; whether calls are recorded and who may read them is your company's own rule.
- **Your platform.** The instructions are written to be pasted into ChatGPT, Claude, Copilot or Gemini. It works from files you supply and needs no connection to your call recorder or sales system.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried once on its invented example in Claude on 9 November 2026; the record of that run is published with it, and lists the clarifications made afterward that have not been run again. That run did not reach the stop conditions or the path for notes without a transcript. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a few past calls your sales lead remembers well, plus hard cases written in advance, each with its expected behavior: a transcript with generic speaker labels, an answer lost in an inaudible stretch, notes that say nothing about the next step, a salesperson who supplies the buyer's cost, a request for a score out of ten. The sales lead checks every quotation against the call before anyone relies on the scorecard. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

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
- [Stalled-deal review](../stalled-deal-review/)
- [Objection answers and sales one-pager](../objection-answers-and-sales-one-pager/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
