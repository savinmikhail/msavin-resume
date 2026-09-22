# Commercial-experience reconstruction

Use this branch when the student has real commercial experience but describes it as generic responsibilities or cannot immediately name strong achievements.

## Recover the work surface

Extract concrete signals from the student context, existing resume, repositories, interviews, tickets, or direct answers:

- product flows and business rules the student touched;
- recurring support work, defects, incidents, and operational pain;
- slow queries, endpoints, reports, imports, or background jobs;
- external integrations and their failure modes;
- manual work that was automated;
- data-model or migration work;
- test, release, review, debugging, and documentation practices;
- legacy areas that were made safer or easier to change;
- collaboration with QA, frontend, analysts, managers, or platform teams.

Do not require the student to begin with a polished “achievement.” Ordinary engineering work often contains a useful before/action/after story once the exact flow and failure mode are recovered.

Completion criterion: each proposed direction is anchored in at least one concrete project signal rather than vacancy wording alone.

## Generate bounded hypotheses

For the highest-priority signals, write a proposed bullet in finished resume form. Pair it with:

- why it fits this product, stack, role, and tenure;
- which part is observed and which part is inferred;
- the smallest questions that would confirm the mechanism and result;
- the maximum credible ownership scope;
- wording to avoid if the hypothesis remains unconfirmed.

Example shape:

> **Proposed resume bullet:** Stabilized batch import from an external service by moving processing to background jobs and adding retry handling, preventing one failed batch from blocking the full exchange.
>
> **Why plausible:** the student worked on this integration, the project used queues, and partial external failures are documented.
>
> **Confirm:** Was processing previously synchronous? Did retries apply to the whole import or only a failed batch? How was success observed?

The example is a form, not reusable evidence. Generate mechanisms only when the current project context points to them.

## Use vacancy demand correctly

Use high-frequency requirements to choose which real work to investigate first: SQL optimization, APIs, queues, testing, review, incidents, delivery, documentation, or architecture participation. Vacancy language may improve phrasing after the underlying work is plausible. It cannot manufacture a missing technology or responsibility.

## Promote or reject

- Promote a proposal to `accepted` when the user confirms the material facts or primary evidence supports them.
- Use `needs-legend` when the fact is accepted but the student still needs a complete technical explanation.
- Keep it `proposed-hypothesis` when it is only plausible.
- Reject it when the answer conflicts with the project, chronology, role, or product maturity.

Only promoted claims enter the final resume. Return unconfirmed proposals separately in resume-ready language so they can be reviewed efficiently.
