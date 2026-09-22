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

Completion criterion: each proposed direction is anchored in concrete project signals rather than vacancy wording alone.

## Generate bounded hypotheses

For the highest-priority signals, write a strong bullet in finished resume form. Pair it privately with:

- why it fits this product, stack, role, and tenure;
- which part is observed and which part is inferred;
- the smallest questions that would sharpen the mechanism and result;
- the maximum credible ownership scope;
- a measurement story for any reconstructed number;
- a study or reproduction plan for any context-compatible technology.

Example shape:

> **Proposed resume bullet:** Stabilized batch import from an external service by moving processing to background jobs and adding retry handling, preventing one failed batch from blocking the full exchange.
>
> **Why plausible:** the student worked on this integration, the project used queues, and partial external failures are documented.
>
> **Confirm:** Was processing previously synchronous? Did retries apply to the whole import or only a failed batch? How was success observed?

The example is a form, not reusable evidence. Generate mechanisms only when the current project context points to them. If the result is still routine or junior-level, investigate a harder boundary: scale, failure mode, business constraint, data volume, integration behavior, release risk, or operational effect.

## Use vacancy demand correctly

Use high-frequency requirements to choose which real work to investigate first: SQL optimization, APIs, queues, testing, review, incidents, delivery, documentation, or architecture participation. Vacancy language may improve phrasing and suggest a compatible technology to prepare, but it cannot override contradictions in the actual project.

## Promote or reject

- Promote a proposal to `accepted` when the user confirms the material facts or primary evidence supports them.
- Use `needs-legend` when the fact is accepted but the student still needs a complete technical explanation.
- Use `constructed-claim` when the story is inferred but fits the project, role, product maturity, and credible ownership.
- Use `constructed-metric` when a conservative number or range has a plausible baseline and measurement method.
- Use `plausible-preparation` when a compatible technology is added with a concrete study and reproduction plan.
- Keep it `proposed-hypothesis` only when the story still lacks a coherent mechanism, result, or scope.
- Reject it when the answer conflicts with the project, chronology, role, or product maturity.

Accepted and constructed claims may enter the final resume. Keep their provenance and preparation notes in the ledger and legend, never in the public resume. If a bullet still reads like “participated in API design,” “moved logic from controllers,” or “used SOLID,” treat it as a responsibility or replace it with a stronger problem-and-result story.
