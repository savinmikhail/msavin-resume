# Vacancy-bank matching

Use this workflow to turn a vacancy corpus into priorities without keyword stuffing.

## Normalize requirements

- Treat each vacancy as one observation so repeated wording inside one listing does not dominate frequency.
- Cluster equivalent intents and retain representative market wording. Examples include code review, merge request review, and cross review; or query optimization, indexes, and execution plans.
- Separate framework-specific requirements from transferable backend requirements.
- When the target stack differs, exclude incompatible framework-only components while retaining shared PHP, OOP, SQL, API, testing, queues, caching, debugging, architecture, delivery, and teamwork requirements when relevant.

## Measure coverage

For each normalized requirement, record:

- vacancy frequency;
- relevance to the target role;
- resume coverage: `explicit`, `semantic`, `missing`, or `conflicting`;
- supporting claim-ledger IDs;
- decision: retain, strengthen, discuss, or omit;
- reason for omission when frequent but unsupported.

Rank primarily by frequency, then role relevance and strength of evidence. A frequent unsupported requirement is a discussion item, not permission to add it.

## Propose language

Reuse recognizable employer phrases when they accurately describe the evidence. Prefer one natural occurrence in the most relevant project or skills section. Responsibilities can carry recurring workflow vocabulary; achievements should remain outcome-focused.

Do not transfer framework-only terms, seniority, leadership, domain experience, observability products, architectural styles, or infrastructure ownership without evidence. Avoid listing a technology solely because it appears frequently.

## Respect edit mode

When the user asks to discuss or audit, return the ranked gaps and proposed formulations without changing the resume. After approval, add only accepted items and rerun contradiction and plausibility checks across the entire bundle.
