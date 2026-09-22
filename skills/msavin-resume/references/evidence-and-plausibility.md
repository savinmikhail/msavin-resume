# Evidence and plausibility gates

Apply these gates to every achievement, responsibility that implies ownership, and material technology claim.

## Provenance and status

Track provenance independently from decision status.

Useful provenance labels:

- `student-stated`: supplied or corrected directly for this student;
- `student-primary`: supported by the student's code, Git history, CI, monitoring, or documents;
- `contextual-hypothesis`: a bounded possibility derived from the student's real commercial and project context but not yet confirmed;
- `authorized-donor`: reconstructed from an allowlisted resume or interview;
- `public-context`: supported by a reliable public source about the company or product;
- `inference`: derived from several sources but not directly stated.

Decision statuses:

- `proposed-hypothesis`: resume-ready wording offered for validation, not yet eligible for the final resume;
- `accepted`: supported and plausibly scoped;
- `needs-legend`: usable only after recording a coherent technical explanation;
- `needs-confirmation`: a fact could materially change the wording;
- `rejected`: contradicted, oversized, chronologically impossible, or unsupported.

## Scope gate

Classify the blast radius:

- local: query, endpoint, job, component, integration, or bounded module;
- team: several modules, a service owned by the team, or a shared engineering practice;
- organization: product-wide architecture, platform migration, core company capability, or cross-team standard.

The burden of proof rises with blast radius. An organization-level claim requires direct evidence of authority and scope. Without it, identify the candidate's concrete contribution and rewrite at local or team level.

## Ownership gate

Use the strongest verb the evidence supports:

- `implemented` or `developed` for direct execution;
- `designed with the team` or `participated in design` for shared decisions;
- `led` only with evidence of coordination and decision authority;
- `owned` or `architected` only with sustained responsibility for the whole stated scope.

Team participation is not individual ownership. A donor's seniority or authority does not transfer to the student.

## Product-maturity gate

For a mature product, assume foundational capabilities predate the candidate unless evidence shows a new version, region, business line, rewrite, or previously missing bounded subsystem.

Claims such as creating the cart, authorization, payments, the whole reporting platform, or the migration from monolith to microservices are credible only when the project dossier establishes what was genuinely new and what the candidate personally changed. Otherwise describe the concrete flow or subsystem: for example recalculation rules, reservation handling, extraction of one service, or migration of one integration.

## Role and time gate

Check that the work fits:

- stated seniority and formal role;
- tenure and project dates;
- team size and division of responsibilities;
- the number and complexity of other claimed achievements;
- technology release dates and the architecture known for that period.

A strong claim that could be true but cannot fit the available time or authority remains rejected until clarified.

## Hypothesis gate

When commercial experience is real but underspecified, infer possible achievements only from concrete project signals: observed responsibilities, product flows, stack capabilities, recurring incidents, bottlenecks, manual work, integrations, releases, or code evidence.

Write each possibility in finished resume language so the user can evaluate it, but keep it marked `contextual-hypothesis` and `proposed-hypothesis`. Attach one or more discriminating questions about the original problem, candidate action, or observable result. Vacancy demand may prioritize which hypotheses to investigate; it may not supply the missing fact.

Prefer bounded, ordinary ownership that fits the role. A hypothesis must not introduce an unobserved technology, exact metric, leadership authority, architecture migration, or foundational product feature. Promote it only after confirmation; otherwise omit it from the final resume.

## Company and public fact-check gate

Fact-check when a claim is easy to falsify or unusually consequential, especially for:

- recognizable companies or public products;
- product-wide migrations or architecture claims;
- foundational product capabilities;
- large scale, revenue, user-count, latency, availability, or savings metrics;
- technologies or versions that may conflict with the employment dates;
- claims that contradict public engineering material or other interviews.

Prefer primary company engineering publications, official product history, source repositories, or contemporaneous evidence. Record the source and date in the ledger. Public plausibility is necessary but does not prove personal contribution.

## Metric gate

Record what was measured, baseline, resulting value, environment, period, and measurement method. Preserve the scope: an endpoint improvement is not an API-wide improvement; a test benchmark is not production impact.

When provenance is missing, use a qualitative result or flag the number for confirmation. Do not invent a measurement definition merely to retain a percentage.

## Defensibility gate

For each accepted claim, the legend must support:

1. the original problem or constraint;
2. the candidate's specific actions;
3. the relevant implementation details;
4. at least one tradeoff or rejected alternative;
5. how the result was validated;
6. the boundary of what the candidate did not own.

If these cannot be stated consistently, scope the claim down or reject it.
