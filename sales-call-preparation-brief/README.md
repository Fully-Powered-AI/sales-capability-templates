# Sales call preparation brief

Your salesperson, partner or account manager walks into every meeting with a brief they can read in five minutes: who will be there, what has been said and promised so far, what is still open, and a plan for the call. Every line traces to your own notes or a public page, and anything inferred is labelled.

*Workflow template · Sales · version 0.1.0 · [Workflows Directory](https://fullypowered.ai/workflows/sales-call-preparation-brief/)*

## The outcome

Nobody opens a meeting by asking the buyer to repeat themselves. The person leading the call knows who is new, which promise is still unkept on either side, which question the buyer asked that nobody answered, and the one result they want from this meeting.

The brief is built from what you hand it: your notes, your emails and the public pages you name. It works with no sales system connected. A fact with no source does not go in, a guess is labelled as one, and what could not be checked is listed so you know where the brief is thin. The person leading the call reads it, corrects it and decides what to say.

## Who starts the work, and when

The person leading the meeting starts it: a salesperson, a partner or an account manager. Run it a day or two before a first meeting, a follow-up, a pricing conversation or a client review, and again if the attendee list changes.

That person owns the result. Questions about price and terms that the brief turns up go to whoever owns them in your company, usually the sales lead. The AI assistant sends nothing, books nothing and updates no record.

## What they supply

- **The meeting.** The company, the date and time, who is invited and what the invite says it is for.
- **Your own notes.** Notes or transcripts from earlier calls and the emails that matter, pasted or uploaded. For a first meeting, none.
- **Public pages.** The company’s own pages and recent news, as pasted text or as addresses the assistant is allowed to open.
- **Your facts.** A few lines on what you sell, your call stages, and the approved material you can have ready.

## What comes out

A brief you can read in five minutes, about a page when the history is short, in a fixed order:

1.  **Before the call.** Anything overdue or awkward that should be dealt with first.
2.  **The company.** A few sourced lines, with recent dated news.
3.  **Who will be there.** Each attendee’s role, what they have said they care about, and who is new.
4.  **History.** The dated record, shortest form.
5.  **Promises and questions.** What you owe, what they owe, what is done, and questions somebody asked that nobody has answered.
6.  **Call plan.** The objective, three to five questions, the objections already raised and what to have ready.
7.  **Not verified,** and any requests found inside the material, set out for you to deal with; the assistant carries none of them out.

Good looks like this: you can check any line against its source in under a minute, and nothing in the meeting surprises you that was already in your own notes.

See the worked example with invented data in [EXAMPLE.md](EXAMPLE.md).

## Where it fits

- [Sales](https://fullypowered.ai/functions/sales/): preparation before every buyer conversation, from first meeting to decision.
- [Customer success and account management](https://fullypowered.ai/functions/customer-success-and-account-management/): reviews and renewals where the client expects you to remember everything.
- [Professional services](https://fullypowered.ai/industries/professional-services/): partners who sell and deliver, with little time between meetings.
- [Software technology](https://fullypowered.ai/industries/software-technology/): several people on the buyer’s side, each with a different question.
- [Marketing and advertising](https://fullypowered.ai/industries/marketing-and-advertising/): pitches and client reviews that turn on what was promised last time.
- [Engineering firms](https://fullypowered.ai/industries/engineering-firms/): long pursuits where months pass between conversations.
- [Growth & scaling](https://fullypowered.ai/situations/growth-and-scaling/): more meetings than your senior people can prepare for by hand.

## What has to change for your company

- **Where notes live.** Decide which call notes and emails count, and get them written down within a day of each call. The brief is only as good as the notes.
- **Your facts page.** What you sell, your call stages and the approved material a person can have ready. The assistant says nothing about your product, price or terms that this page does not say.
- **How far back to look.** The period of news worth reading, and how old a note can be before it is marked as old.
- **What may be said about people.** Work roles and what attendees said in meetings. Nothing about private lives, and no guessed titles.
- **Who answers the hard questions.** The role that owns price and terms, and the role that answers technical questions such as logins and where data is kept, so an open question has somewhere to go.
- **Your platform.** It runs in ChatGPT, Claude, Copilot or Gemini. Decide which files and web pages the assistant may read for this work.

## What has been checked

Fully Powered AI wrote this workflow template. It was editorially reviewed on 9 November 2026. It was tried on its own invented example on 9 November 2026. The recorded run was one of several that day, and the record describes the earlier ones and lists what worked and what did not. It has not yet been tested in a client environment. It has not yet been tested as a packaged version in ChatGPT, Claude, Copilot or Gemini.

Testing in your environment means running it on meetings you have already had, plus hard cases written in advance, each with its expected behavior: an attendee nobody has met, a promise your side forgot, a public page that disagrees with your notes, an email that asks the assistant to send something. [Pilot acceptance-test preparation](https://fullypowered.ai/workflows/pilot-acceptance-test-preparation/) builds that test set, and [What we test before we call an AI workflow ready](https://fullypowered.ai/insights/what-we-test-before-a-workflow-is-ready/) shows the record.

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
- [Account handoff](https://fullypowered.ai/workflows/account-handoff/)
- [Client-status update preparation](https://fullypowered.ai/workflows/client-status-update-preparation/)

## Make it yours

This is the starting version. Fully Powered AI adapts workflow templates to how your company works, proves them on real work and rolls them out to the roles that use them. [Talk with us](https://fullypowered.ai/contact/).
