
## Organizer note — keep out of the starting card

Version 1 materials are built under `materials/`: synthetic exports, guide and prepared fallback. Station 1 must not wait for another station; Station 2 gets
an independently prepared analysis table.

Supplied input: a participant/allocation export with randomization dates, and a
follow-up export with documented acceptance status, acceptance date where
applicable, and follow-up end date. Use synthetic data only. Definitions and
export conventions belong in the supplied guide, not in a surprise reveal.

The required event is first manuscript acceptance after randomization, not
submission or online publication. Observation ends at day 365 if no acceptance
is observed. Missing acceptance date for a documented non-event is expected;
a positive acceptance flag with missing date is a query, not permission to
invent a date. Do not create this latter case unless a clear handling route is
provided. Only a small number of routine formatting issues are needed.

The prepared reference table uses `researcher_id`, `coffee_group`, `days`
and `accepted`, consistent with Station 2. The dataset has 60 researchers, 30 per randomized group.

## Check slip: Check the prepared data · release at 14:00

1. In the original data files, choose a participant ID with a recorded manuscript acceptance. Find the same ID in your prepared table. Do the coffee group, days to acceptance and acceptance status match?

2. Now choose a participant ID with no recorded acceptance. Is that ID still in your prepared table, with 365 days and `accepted = 0`?

## Reflection · release at 14:10

Use `delegation-reflection.md`. If the team needs a concrete example, look at how
the agent joined records, handled missing dates, retained people and documented
assumptions. Separate prescribed study definitions from discretionary choices.
Do not frame inventing an event definition as a legitimate design freedom.

If the agent stalls, supply the prepared table from the facilitator pack and check two
records. Record that this fallback exercises review rather than live preparation.
