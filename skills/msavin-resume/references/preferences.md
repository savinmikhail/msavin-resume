# Mikhail's resume collaboration preferences

Use these as defaults unless Mikhail overrides them in the current request.

## Decision process

- Work through one achievement at a time. Discuss it, correct the facts, obtain acceptance, edit it, and commit it separately.
- Do not ask Mikhail to evaluate many achievements or a large rewrite simultaneously.
- When he says a formulation is good and asks to add or commit it, use that wording as the decision and proceed without reopening settled choices.
- Corrections from Mikhail override inferences from code, previous resumes, or earlier drafts.

## Audience and detail

- Treat ATS and LLM-based screening as first-class audiences. Technical detail and relevant terminology are useful when they make the achievement more searchable and more credible.
- Do not optimize mechanically for the shortest possible resume or an arbitrary one-page limit.
- Still support diagonal human reading: put the point of the achievement early, keep one coherent story per bullet, and remove details that do not prove the result.
- Prefer a detailed, technically defensible achievement over generic wording such as “настроил pipeline” or “ускорил deployment.”
- Use implicit STAR. The text should show what was wrong, what Mikhail changed, and what became better without sounding like a behavioral-interview template.

## Evidence and tone

- Recover exact measurements from Git history, CI runs, monitoring, benchmarks, or other primary evidence when available. Do not rely on remembered numbers if they can be checked.
- Preserve relevant constraints around a measurement—for example, execution time decreasing while checks or implementation complexity increased—because they often make an optimization more credible.
- Avoid inflated business impact, unsupported percentages, and ceremonial adjectives.
- Preserve concrete implementation constraints, unusual failure modes, and debugging discoveries when they distinguish the work from routine responsibilities.
- Keep the tone direct and professional rather than corporate or self-congratulatory.

## Relevance and privacy

- Let the target role and vacancy determine priority. Do not default to DevOps positioning.
- For PHP/backend resumes, treat product and domain ownership, architecture, APIs, databases, data consistency, asynchronous processing, performance, testing, and production reliability as core evidence rather than secondary implementation detail.
- Include CI/CD, infrastructure, observability, and incident debugging when they strengthen the intended positioning or show end-to-end ownership, not merely because they sound more operational.
- Avoid disclosing the specific interview-analysis project or its content. When needed, describe the safe functional domain, for example processing calls, and omit sensitive product identifiers.
- Preserve exact technology names confirmed by Mikhail. In the current body of work, OpenSearch must not be rewritten as Elasticsearch.

## Language

- Match the language of the resume. For a Russian resume, keep established technical terms when they are clearer or better for matching: pipeline, deployment, consumer, reconciliation, fallback transport, trace, query, cache, and similar terms.
- Do not translate technical vocabulary merely to make the text uniformly Russian when that reduces precision.
