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

- Recover exact measurements from Git and CI history when available, especially before/after pipeline duration. Do not rely on remembered numbers if they can be checked.
- It is acceptable to say that checks or complexity increased while total execution time decreased; this often makes an optimization more credible.
- Avoid inflated business impact, unsupported percentages, and ceremonial adjectives.
- Preserve concrete implementation constraints, unusual failure modes, and debugging discoveries when they distinguish the work from routine DevOps responsibilities.
- Keep the tone direct and professional rather than corporate or self-congratulatory.

## Relevance and privacy

- For the DevOps resume, production delivery, infrastructure, observability, incident debugging, and reliability outrank application-only features.
- Data consistency or backend mechanisms can appear when they demonstrate operational reliability, but should not displace stronger DevOps/SRE achievements.
- Avoid disclosing the specific interview-analysis project or its content. When needed, describe the safe functional domain, for example processing calls, and omit sensitive product identifiers.
- Preserve exact technology names confirmed by Mikhail. In the current body of work, OpenSearch must not be rewritten as Elasticsearch.

## Language

- Match the language of the resume. For a Russian resume, keep established technical terms when they are clearer or better for matching: pipeline, deployment, runners, consumers, reconciliation, fallback transport, trace, and similar terms.
- Do not translate technical vocabulary merely to make the text uniformly Russian when that reduces precision.
