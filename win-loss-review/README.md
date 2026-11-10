# Win-loss review

Once a quarter your sales lead sees, from the deals you closed, where the losses ended, which kinds of deal you win and lose, what the largest deals show, and which findings rest on enough deals to act on. Actions are proposed in proportion to the evidence, and nothing in your sales system is changed.

*Capability template · Sales · version 0.1.0 · [Capabilities Directory](https://fullypowered.ai/capabilities/win-loss-review/)*

## The outcome

The sales lead plans the next quarter from what the closed deals actually show, instead of from the two losses everyone still remembers. Win rates are laid out by lead source, deal type, segment and size, with the number of deals behind each, so a striking rate built on four deals is visible as exactly that. Every loss is placed at the stage where it ended, and every reason is counted as your record gives it.

Each finding carries a plain label. Firm means enough deals stand behind it to act on. Thin means it is worth watching, and the review says which test it misses: too few deals in the quarter, too few showing the finding, or a group too small to compare. Firm findings can lead to a change in how you sell. Thin ones lead only to recording something new or looking again next quarter, so the team does not rebuild its process on luck.

Where a note in the buyer's own words tells a different story from the reason in the record, the review shows both and proposes a correction for the person who keeps the record. It never ranks salespeople and never claims to know why a deal was lost; every finding comes with a question for the person who can find out.

## Who starts the work, and when

The sales lead or revenue lead runs it once a quarter, after the quarter's deals are closed in the record and before the next quarter's plan is set. The person who keeps the deal record can prepare the export and notes.

The sales lead reads the review and decides which of the proposed actions to take, and who owns each one. The person who keeps the record makes any correction. The AI assistant sends nothing and changes nothing.

## What they supply

- **Your closed-deal export.** One row per deal, from your sales system or spreadsheet: segment, deal type, lead source, amount, the dates it opened and closed, its outcome, the last stage it reached, the reason it was lost and any competitor named.
- **Your facts.** The period, your stages in order, your size bands, your list of reasons for losing with what each means, who reads the review, and the minimums for a firm finding if you want to set your own.
- **Your deal notes.** Call notes and emails for the largest won and lost deals, each with the deal and the date, pasted as they are.
- **Last quarter's review,** so the actions you agreed then are checked against what the record now holds.

## What comes out

One review in a fixed order:

1. **Coverage.** How many deals were read, which rows were not and why.
2. **Headline.** At most two sentences on the firm findings, or a plain statement that none is firm this quarter.
3. **Win rates,** overall and by each cut, with the counts behind every percentage and no percentage where a group is too small.
4. **Where the losses ended,** stage by stage.
5. **Time and amounts:** how long won and lost deals took, and what they were worth.
6. **Why you lost,** reason by reason as the record gives it, with the buyer's own words where a note has them, and the competitors named.
7. **The largest deals,** one line each from the record and the notes.
8. **What the wins share,** where the notes of several won deals say the same thing.
9. **Findings,** each firm or thin, each with a question for a named role.
10. **Proposed actions,** each with its kind, its owner and the finding it comes from, and last quarter's actions carried forward.
11. **At odds, gaps and corrections:** where the notes and the record disagree, what the record leaves blank, and the corrections to propose.

A good review is one the sales lead can take into the quarterly planning meeting and defend number by number, because every figure recomputes from the export.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Sales](https://fullypowered.ai/functions/sales/): the quarterly look back at what was won and lost, done the same careful way every time.
- [Analytics and reporting](https://fullypowered.ai/functions/analytics-and-reporting/): counts and rates from your own export, each with its sample size, and no claim beyond what the counts show.
- [Professional services](https://fullypowered.ai/industries/professional-services/): a firm closes a few dozen engagements a quarter, exactly the scale where a pattern and a coincidence look alike.
- [Software technology](https://fullypowered.ai/industries/software-technology/): deals come from several lead sources and buyer types, and the cuts show which ones close.
- [Manufacturing](https://fullypowered.ai/industries/manufacturing/): an order can be lost on lead time or capacity even when the record says price.
- [Engineering firms](https://fullypowered.ai/industries/engineering-firms/): bids won and lost are few and large, so knowing how many deals stand behind a finding matters.
- [Established businesses](https://fullypowered.ai/situations/established-businesses/): a company with a few years of closed deals and a sales process worth checking against them.

It sits beside [Stalled-deal review](https://fullypowered.ai/capabilities/stalled-deal-review/), which reads the open pipeline every week, [Objection answers and sales one-pager](https://fullypowered.ai/capabilities/objection-answers-and-sales-one-pager/), which prepares answers to the reasons buyers give, and [Sales call preparation brief](https://fullypowered.ai/capabilities/sales-call-preparation-brief/), which carries what the review teaches into the next call.

## What has to change for your company

- **Your reason list.** Write down each reason a deal can be lost for and what it means, so the record and the review use the same words. The review counts reasons exactly as recorded.
- **Your stages and size bands.** Name your stages in order and set the size bands that matter to you.
- **Your export.** Agree the columns once. If your sales system names them differently, write the mapping down; the assistant stops and asks rather than guess.
- **Your minimums.** The defaults ask for twenty deals in the quarter, ten in any group compared and five behind a firm finding. A company that closes hundreds of deals a quarter can raise them.
- **Your notes habit.** A dated note with the buyer's own words is what lets the review check a recorded reason.
- **Your platform.** The instructions are written to be pasted into ChatGPT, Claude, Copilot or Gemini. It works from files and notes you supply and needs no connection to your sales system.

## What has been checked

Fully Powered AI wrote this capability template. It was editorially reviewed on 9 November 2026. It was tried on its invented example on 9 November 2026 in two runs; the record of the second is published with it. The first run saw part of the example's answer before writing its own, and the session that ran the second had not seen it. The record lists the small edits made afterward that have not been run again. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on a past quarter your sales lead remembers well, plus hard cases written in advance, each with its expected behavior: an export whose column names differ, a quarter with too few deals, a recorded reason a buyer's note contradicts, a small group with a striking win rate, a lost deal with no stage or reason. The sales lead recomputes the figures from the export before anyone relies on them. [Pilot acceptance-test preparation](https://fullypowered.ai/capabilities/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

- Written by Fully Powered AI.
- Sources and rights reviewed.
- Editorially reviewed on 9 November 2026.
- Package format checked by script on every release.
- Tried once on its invented example in Claude on 9 November 2026. The record is in [TRIAL.md](TRIAL.md).
- Not yet tested in a client environment.

## What is in this folder

- [TEMPLATE.md](TEMPLATE.md): the complete capability template. Roles, inputs, the procedure, exceptions and stop conditions, the output format, a reviewer checklist, acceptance tests, the instructions for an AI assistant and what to customize.
- [EXAMPLE.md](EXAMPLE.md): a worked example with invented data.
- [TRIAL.md](TRIAL.md): what came out when the template was tried on its example.
- [SKILL.md](SKILL.md): the technical file, for AI products that load packaged instructions from a folder.
- [SOURCES.md](SOURCES.md): what the capability drew on, with licences.
- [LICENSE](LICENSE): MIT. Use it, change it, make it yours.

## Start using it

1. Read [EXAMPLE.md](EXAMPLE.md) to see what a good result looks like.
2. Open [TEMPLATE.md](TEMPLATE.md) and set every item under "What to customize" to your own rules, roles and limits.
3. Give your AI assistant the instruction block and the output format from the template, with your own limits in place of the ones the instructions leave open in square brackets. Paste them in as custom instructions in ChatGPT, Claude, Copilot or Gemini, or copy this whole folder into a product that loads `SKILL.md` packages. This folder stands alone; you do not need the rest of the repository.
4. Run it on past work first, using the reviewer checklist and acceptance tests in the template, before anyone relies on it.

## Related capabilities

- [Stalled-deal review](../stalled-deal-review/)
- [Objection answers and sales one-pager](../objection-answers-and-sales-one-pager/)
- [Sales call preparation brief](../sales-call-preparation-brief/)

## Make it yours

This is the starting version. Fully Powered AI adapts capabilities to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
