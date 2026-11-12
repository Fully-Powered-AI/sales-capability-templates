# Sales pipeline review: an invented example

*Illustrative example with invented data.* The company, its accounts, its people, the deals, the dates and the amounts below are all invented. The seller is an invented 30-person company that designs, installs and services warehouse racking and conveyor systems. Its sales team is a sales lead and two account managers, and the managing director commits the quarterly forecast. First come the inputs the sales lead supplied, in full, then the review the workflow template returned.

## The inputs

### 1. Your facts (typed by the sales lead)

```
Review date: Monday 9 November 2026
This week's export taken: Monday 9 November 2026
Last week's export taken: Monday 2 November 2026
Period: 1 October 2026 to 31 December 2026
Target for the period: $600,000 won
Coverage bar: 3.0
Stages, in order (weight; limit in days):
1. Qualified (10%; 21)
2. Site survey (25%; 14)
3. Quote sent (50%; 21)
4. Negotiation (75%; 14)
Quiet after: 14 days
Movement threshold: $25,000 and 20%
Closed deals needed for a rate: 20
Baseline window: the 180 days before the review date
Reads it: Sales lead
Commits the forecast: Managing director
```

### 2. This week's export (9 November 2026)

```
deal_id,account,owner,stage,amount,close_date,created_date,stage_entered,next_step,next_step_date,last_activity,status,closed_date
R-201,Account A,Account manager 1,Negotiation,84000,2026-11-20,2026-08-03,2026-10-27,Final terms call,2026-11-12,2026-11-05,open,
R-202,Account B,Account manager 2,Quote sent,126000,2026-12-15,2026-09-01,2026-10-12,Quote review with the operations director,2026-11-03,2026-10-20,open,
R-203,Account C,Account manager 1,Quote sent,58000,2026-11-27,2026-09-14,2026-10-26,Follow-up call,2026-11-13,2026-11-04,open,
R-204,Account D,Account manager 2,Site survey,210000,2026-12-18,2026-10-05,2026-10-16,,,2026-10-23,open,
R-205,Account E,Account manager 1,Site survey,47000,2027-01-29,2026-10-21,2026-11-03,Survey visit,2026-11-16,2026-11-03,open,
R-206,Account F,Account manager 2,Qualified,95000,2027-02-26,2026-10-28,2026-10-28,Discovery call,2026-11-11,2026-11-06,open,
R-207,Account G,Account manager 1,Qualified,,2027-03-31,2026-11-03,2026-11-03,Intro meeting,2026-11-18,2026-11-03,open,
R-208,Account H,Account manager 1,Negotiation,66000,2026-10-30,2026-07-20,2026-10-09,Send revised quote,2026-11-10,2026-11-02,open,
R-209,Account J,Account manager 1,Quote sent,38000,2026-12-04,2026-09-21,2026-11-03,Walk through the quote,2026-11-12,2026-11-05,open,
R-190,Account K,Account manager 1,Negotiation,112000,2026-10-14,2026-06-08,2026-09-21,,,2026-10-14,won,2026-10-14
R-194,Account L,Account manager 2,Negotiation,73000,2026-11-04,2026-07-27,2026-10-12,,,2026-11-04,won,2026-11-04
R-196,Account M,Account manager 2,Quote sent,41000,2026-11-06,2026-08-24,2026-10-05,,,2026-11-06,lost,2026-11-06
R-172,Account N,Account manager 1,Negotiation,64000,2026-06-12,2026-03-02,2026-05-25,,,2026-06-12,won,2026-06-12
R-175,Account P,Account manager 2,Quote sent,88000,2026-07-03,2026-04-13,2026-06-01,,,2026-07-03,lost,2026-07-03
R-178,Account Q,Account manager 1,Negotiation,52000,2026-08-21,2026-05-18,2026-08-03,,,2026-08-21,won,2026-08-21
R-181,Account R,Account manager 2,Site survey,30000,2026-09-09,2026-07-06,2026-08-10,,,2026-09-09,lost,2026-09-09
```

### 3. Last week's export (2 November 2026, open rows)

Only last week's open rows are shown, because the review reads only those.

```
deal_id,account,owner,stage,amount,close_date,created_date,stage_entered,next_step,next_step_date,last_activity,status,closed_date
R-201,Account A,Account manager 1,Negotiation,84000,2026-11-20,2026-08-03,2026-10-27,Final terms call,2026-11-12,2026-10-30,open,
R-202,Account B,Account manager 2,Quote sent,126000,2026-11-30,2026-09-01,2026-10-12,Quote review with the operations director,2026-11-03,2026-10-20,open,
R-203,Account C,Account manager 1,Quote sent,64000,2026-11-27,2026-09-14,2026-10-26,Send revised quote,2026-11-02,2026-10-29,open,
R-204,Account D,Account manager 2,Site survey,210000,2026-12-18,2026-10-05,2026-10-16,,,2026-10-23,open,
R-205,Account E,Account manager 1,Qualified,47000,2027-01-29,2026-10-21,2026-10-21,Book the survey,2026-11-03,2026-10-28,open,
R-206,Account F,Account manager 2,Qualified,95000,2027-02-26,2026-10-28,2026-10-28,Discovery call,2026-11-11,2026-10-28,open,
R-208,Account H,Account manager 1,Negotiation,66000,2026-10-30,2026-07-20,2026-10-09,Send revised quote,2026-11-10,2026-11-02,open,
R-209,Account J,Account manager 1,Site survey,38000,2026-12-04,2026-09-21,2026-10-19,Survey visit,2026-10-30,2026-10-30,open,
R-194,Account L,Account manager 2,Negotiation,73000,2026-11-04,2026-07-27,2026-10-12,Signature,2026-11-04,2026-10-30,open,
R-196,Account M,Account manager 2,Quote sent,41000,2026-11-20,2026-08-24,2026-10-05,Quote decision,2026-11-06,2026-10-27,open,
R-199,Account S,Account manager 2,Qualified,54000,2027-01-15,2026-10-07,2026-10-07,Discovery call,2026-10-30,2026-10-14,open,
```

## The output

**SALES PIPELINE REVIEW: Monday 9 November 2026**

**For:** Sales lead. **Forecast committed by:** Managing director. **Period:** 1 October 2026 to 31 December 2026. **From:** this week's export of 9 November 2026, 16 rows; last week's export of 2 November 2026, 11 open rows (exports 7 days apart). **Stages:** 4; weights Qualified 10%, Site survey 25%, Quote sent 50%, Negotiation 75%; limits in days Qualified 21, Site survey 14, Quote sent 21, Negotiation 14. **Quiet after** 14 days. **Movement threshold:** \$25,000 and 20%. **Rates need** 20 closed deals. **Defaults used:** none.

**Coverage:** Rows read: 16 (9 open; 2 won and 1 lost in the period; 4 closed earlier in the baseline window). Not read: none. Open last week and missing now, under Could not assess: R-199, Qualified, \$54,000. Outcome: partial: R-199 was open on 2 November and is not in this week's export.

**Headline:** 9 open deals, \$724,000 (1 amount blank); weighted \$297,250. Won in the period so far: 2, \$185,000. Deals at risk: 3, \$402,000. Coverage of the remaining target: 1.4 against your bar of 3.0.

**By stage:**

- **Qualified:** 2 open, \$95,000 (1 amount blank); last week 3, \$196,000 (moved: down \$101,000, 51.5%). Weighted \$9,500. Average 9 days in stage (limit 21). No next step: 0. Quiet 14+ days: 0. Over limit: 0.
- **Site survey:** 2 open, \$257,000; last week 2, \$248,000 (up \$9,000, 3.6%: under the threshold). Weighted \$64,250. Average 15 days in stage (limit 14). No next step: 1. Quiet 14+ days: 1. Over limit: 1.
- **Quote sent:** 3 open, \$222,000; last week 3, \$231,000 (down \$9,000, 3.9%: under the threshold). Weighted \$111,000. Average 16 days in stage (limit 21). No next step: 0. Quiet 14+ days: 1. Over limit: 1.
- **Negotiation:** 2 open, \$150,000; last week 3, \$223,000 (moved: down \$73,000, 32.7%). Weighted \$112,500. Average 22 days in stage (limit 14). No next step: 0. Quiet 14+ days: 0. Over limit: 1.
- **Total:** 9 open, \$724,000; last week 11, \$898,000 (down \$174,000, 19.4%: under the threshold). Weighted \$297,250.

**Since last week:** exports 7 days apart.

- **New:** R-207, Qualified, amount blank.
- **Advanced:** R-205, from Qualified to Site survey; R-209, from Site survey to Quote sent.
- **Moved back:** none.
- **Close date changed:** R-202, from 30 November 2026 to 15 December 2026.
- **Amount changed:** R-203, from \$64,000 to \$58,000.
- **Won:** R-194, \$73,000, 4 November 2026.
- **Lost:** R-196, \$41,000, 6 November 2026.
- **Missing from this week's export:** R-199, Qualified, \$54,000.
- **Bridge:** \$898,000 + \$0 − \$73,000 − \$41,000 − \$54,000 − \$6,000 = \$724,000.

**This period (1 October 2026 to 31 December 2026):**

- **Won so far:** 2, \$185,000 (R-190, R-194). **Lost:** 1, \$41,000 (R-196).
- **Open with a close date in the period:** 6, \$582,000; by stage: Site survey, 1, \$210,000; Quote sent, 3, \$222,000; Negotiation, 2, \$150,000. Close date already passed: R-208.
- **Weighted:** \$276,000.
- **Target:** \$600,000. **Remaining:** \$415,000. **Coverage:** 1.4; weighted 0.7; below your bar of 3.0.

**Deals at risk: 3, \$402,000**

**R-204** · Account D · Account manager 2 · Site survey · \$210,000 · close 18 December 2026

- Flags: no next step; quiet 17 days (limit 14); in stage 24 days (limit 14).
- To ask Account manager 2: What is the next step with Account D, and on what date?

**R-202** · Account B · Account manager 2 · Quote sent · \$126,000 · close 15 December 2026

- Flags: close date moved later since last week, from 30 November 2026; next-step date passed on 3 November 2026; quiet 20 days (limit 14); in stage 28 days (limit 21).
- To ask Account manager 2: Has the quote review with the operations director taken place, and what moved the close date from 30 November to 15 December?

**R-208** · Account H · Account manager 1 · Negotiation · \$66,000 · close 30 October 2026

- Flags: close date passed on 30 October 2026; in stage 31 days (limit 14).
- To ask Account manager 1: Now that 30 October has passed, what close date should the record show, and is the revised quote still going out on 10 November?

**Closed-deal baseline (13 May 2026 to 8 November 2026):** 7 closed: 4 won, \$301,000; 3 lost, \$159,000. Rates not computed: 7 of 20 closed deals.

**For the forecast, for the Managing director to commit:**

Won so far \$185,000. Open closing in the period \$582,000 (6): at risk \$402,000 (3), not flagged \$180,000 (3). Weighted \$276,000. Remaining to target \$415,000.

Forecast committed: ________ by Managing director on ________. This review does not set a number.

**Where to look first:**

1. Set a dated next step on R-204, for Account manager 2, because it is the largest deal at risk closing in the period, at \$210,000, with no next step and 17 days quiet.
2. Decide how the remaining \$415,000 will be covered, for the sales lead, because coverage is 1.4 against your bar of 3.0.
3. Confirm what happened to R-199, for Account manager 2, because it was open last week at \$54,000 and is missing from this week's export.

**Gaps in the export:** R-207: amount blank.

Prepared from the exports of 9 November 2026 and 2 November 2026. Nothing has been sent, and no record has been changed.
