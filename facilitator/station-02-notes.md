
## Organizer note — not part of the initial participant card

Version 1 analysis table and fallback figure are built under `materials/`. There are 60 synthetic researchers, 30 per group. Use the exported participant ZIP, not this combined organizer file.

The table contains one row per researcher:

- `researcher_id`: unique identifier.
- `coffee_group`: caffeinated or decaffeinated.
- `days`: days from randomization to first manuscript acceptance, or 365 if none was observed.
- `accepted`: 1 if acceptance occurred at that time; 0 if observation ended without acceptance.

Time origin = randomization; event = first manuscript acceptance, not publication
online or in print. Follow-up ends administratively at 365 days. Event code takes
priority when acceptance occurs exactly on day 365. No additional endpoint is
introduced. Existing music-study data must not be relabelled as coffee data.

The conventional display is S(t), still awaiting acceptance. A team may request
1 − S(t), estimated proportion with acceptance; then the axis label and direction
must change together. Avoid describing censored records as failures or exclusions.

Technical check: [GraphPad's survival-analysis instructions](https://www.graphpad.com/guides/prism/latest/statistics/stat_howto_survival.htm)
and [censoring explanation](https://www.graphpad.com/guides/prism/latest/statistics/stat_censored_data.htm).
Source guidance checked 17 September 2026. Reference analysis verified for version 1; no human timed trial yet.


## Check slip: Check the analysis · release at 14:00

1. Look at the code or calculations behind the figure. Did the agent use the event indicator and handle censoring correctly?

2. Which analysis or presentation choice most influences the conclusion? Would you keep it or change it?

## Facilitation and delayed reflection

A Kaplan–Meier figure is the anticipated route, not a method named in the initial
participant brief. If a team needs methodological help, offer it when asked or
when they cannot proceed: “How could you represent time to acceptance while
retaining people still waiting?” A specific Kaplan–Meier hint can follow.
For that display, check confidence intervals, censoring marks, risk counts and
axis direction. Other defensible displays can be discussed rather than forced
into a predetermined answer. Record any facilitator guidance in the reflection.

At 14:10, use `delegation-reflection.md` for a two-minute look back and then select
the station report. Keep the first output available; distinguish choices the
agent made initially from changes the group requested or consciously accepted.
The initial card ends at the separator above. Give the check slip later and
keep organizer/reflection material out of the starting pack.
