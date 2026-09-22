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
- `constructed-claim`: a marketable claim reconstructed from compatible project signals and prepared as an interview story;
- `constructed-metric`: a conservative local metric or range reconstructed from a plausible baseline, result, and measurement method;
- `plausible-preparation`: a context-compatible technology or practice the student must be able to reproduce before interviews;
- `inference`: derived from several sources but not directly stated.

Decision statuses:

- `proposed-hypothesis`: an early candidate that is not coherent enough for the resume yet;
- `accepted`: supported and plausibly scoped;
- `needs-legend`: usable only after recording a coherent technical explanation;
- `constructed-claim`: usable when it passes the context, scope, strength, and defensibility gates;
- `constructed-metric`: usable when its baseline, result, scope, and measurement story are plausible;
- `plausible-preparation`: usable when the technology fits the project and the student receives a concrete preparation plan;
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
- approximate tenure when known; do not guess or transfer exact dates into the resume;
- team size and division of responsibilities;
- the number and complexity of other claimed achievements;
- technology release dates and the architecture known for that period.

A strong claim that could be true but cannot fit the available time or authority must be scoped down or rejected. Missing exact dates alone do not weaken a claim.

## Hypothesis gate

When commercial experience is real but underspecified, infer possible achievements only from concrete project signals: observed responsibilities, product flows, stack capabilities, recurring incidents, bottlenecks, manual work, integrations, releases, or code evidence.

Write each possibility in finished resume language. Attach discriminating questions about the original problem, candidate action, observable result, and measurement, but do not let unanswered questions automatically flatten the draft.

Prefer meaningful mid-level ownership of a bounded subsystem, flow, integration, performance problem, or reliability problem. A contextual hypothesis may introduce a compatible technology or reconstructed local metric when the project signals support it and the student can prepare a coherent explanation. It must not introduce formal leadership, a foundational product feature, a company-wide migration, or externally falsifiable scale without evidence.

## Technology gate

Classify technology claims as:

- confirmed by the student or source material;
- context-compatible and suitable for preparation;
- conflicting with the architecture, chronology, company, or known stack.

A context-compatible technology may enter the resume when it is a natural mechanism for the claimed work, does not contradict known facts, and the student gets a concrete reproduction plan: what to study, what small project or benchmark to build, and which interview questions to answer. Reject only conflicting or implausibly owned technology, not every technology missing from the original resume.

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

Use this order:

1. preserve an exact metric found in student, donor, interview, repository, benchmark, or monitoring evidence when it fits the project;
2. reconstruct a conservative metric or range from a plausible baseline, result, and measurement method when the mechanism and scope are clear;
3. use a concrete count, latency band, throughput range, frequency change, or operational effect when a percentage would be artificial;
4. fall back to a qualitative result only when no honest scale can be reconstructed.

A reconstructed metric must be local enough to defend: a report, endpoint, batch, release cycle, error-diagnosis flow, or bounded module. Record it as `constructed-metric` and add a legend section explaining how it could have been measured. Do not fabricate revenue, user count, market share, company-wide availability, or other externally falsifiable business figures.

## Defensibility gate

For each accepted claim, the legend must support:

1. the original problem or constraint;
2. the candidate's specific actions;
3. the relevant implementation details;
4. at least one tradeoff or rejected alternative;
5. how the result was validated;
6. the boundary of what the candidate did not own.

If these cannot be stated consistently, scope the claim down or reject it.
