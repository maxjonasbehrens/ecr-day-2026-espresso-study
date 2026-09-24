# Reference handover — one valid preparation

Join on researcher_id after trimming whitespace, not row position. Retain all 60 randomized researchers. Map Yes/1 to accepted=1 and No/0 to accepted=0. Missing acceptance dates for non-events are expected. Compute elapsed calendar days from randomization to acceptance for events, otherwise to followup_end_date. Keep randomized coffee_group.

The reference has four fields: researcher_id, coffee_group, days, accepted. Alternative clear names and extra audit columns are valid. Both groups contain 30 people: 19 acceptances and 11 right-censored at day 365. Five follow-up identifiers have surrounding whitespace. No records need exclusion or imputation.

Review a team's transformation and two original records; matching the summary counts alone does not establish correctness. No real trial effect or purchase conclusion follows from these simulated records outside the exercise.
