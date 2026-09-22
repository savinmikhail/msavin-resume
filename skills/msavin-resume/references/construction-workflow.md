# Student resume construction workflow

Use this workflow for a new resume or substantial reconstruction.

## 1. Inventory the inputs

Read every supplied artifact and record:

- the target role and desired positioning;
- the student's verified stack, repositories, employment facts, education, and stated constraints;
- the available company, product, project, role, team, and responsibility context for each real position; exact dates are optional and must not be guessed;
- the vacancy corpus and its target geography or seniority;
- whether the user wants direct experience reconstruction, donor-assisted reconstruction, or a hybrid;
- for donor-assisted work only, resume-bank access, an interview-count or query window, and the exact donor allowlist; do not preload all interview transcripts.

Completion criterion: every available source is classified and every input required by the selected branch is present.

## 2. Choose the source strategy

Use one or combine both:

- **Commercial-experience reconstruction:** infer bounded, technically plausible achievement candidates from the student's real project context, code, tasks, incidents, recurring pain, and responsibilities. Follow [experience-reconstruction.md](experience-reconstruction.md).
- **Donor-assisted reconstruction:** use allowlisted resumes and interviews to recover project shapes, terminology, and defensible stories that fit the student.

In a hybrid, start from real experience and use donors to fill vocabulary or story structure. Do not replace a known project context with a more attractive incompatible donor story.

Completion criterion: the claim ledger can distinguish direct evidence, contextual hypotheses, and donor-derived material.

## 3. Rank authorized donors when used

Use a funnel. Do not load every transcript for every donor into the working context.

1. **Cheap ranking pass:** for every allowlisted donor, obtain screening and technical-interview counts plus resume availability from an existing index, the supplied SQLite bank, or a read-only project query. When the surrounding repository exposes a safe wrapper such as `make prod-query`, use it according to that repository's instructions. Query only metadata needed for ranking.
2. **Selection pass:** choose the strongest primary donor, or at most two when relevance and interview depth are genuinely split. Record the ranking rationale.
3. **Deep evidence pass:** only then read the selected donor's resume versions and relevant technical interviews to recover explanations, mechanisms, tradeoffs, and metric stories.

Prioritize donors by:

1. number and depth of technical interviews in which the experience was questioned;
2. availability of explanations for implementation choices, tradeoffs, and metrics;
3. relevance to the student's target role and credible stack;
4. consistency across resume versions and interviews;
5. screening volume as secondary evidence of market response.

Record why the primary donor was selected and where secondary donors may safely fill gaps. Do not combine incompatible company, domain, timeline, or architecture facts into one project.

Completion criterion: each selected source has a documented purpose and belongs to the allowlist; non-selected donor transcripts were not bulk-loaded.

Skip this step when the source strategy has no donor branch.

## 4. Build a project dossier

Before writing achievements, establish for every proposed company or project:

- what the company and product do;
- whether the product was new, mature, legacy, or under a specific migration;
- the system shape and relevant architecture at that time;
- the candidate's role, seniority, tenure, and formal authority;
- team composition and ownership boundaries;
- which product capabilities already existed before the candidate joined;
- the concrete subsystem, module, integration, or workflow the candidate could plausibly change.

Use public primary sources when a claim depends on externally checkable company or product facts. Mark unresolved contradictions instead of smoothing them over.

Completion criterion: every proposed achievement has a project context against which its scope can be tested.

## 5. Generate and classify candidate claims

Use the evidence-ledger template. Add candidate facts, contextual hypotheses, authorized donor material, interview explanations, repository evidence, public context, and vacancy relevance. Separate provenance from confidence.

For weakly described commercial experience, generate a short list of resume-ready achievement candidates using [experience-reconstruction.md](experience-reconstruction.md). Each candidate must state what makes it plausible, what was reconstructed, and how the student can verify or prepare it. A coherent candidate may enter the working resume as `constructed-claim`, `constructed-metric`, or `plausible-preparation`; questions improve it but do not block drafting.

Run the plausibility gates in [evidence-and-plausibility.md](evidence-and-plausibility.md) and the strength gate in [achievement-strength.md](achievement-strength.md). Reject or scope down claims that exceed credible ownership; strengthen or replace claims that are true-sounding but too routine for a mid-level resume.

Completion criterion: every final-resume claim has status `accepted`, `needs-legend`, `constructed-claim`, `constructed-metric`, or `plausible-preparation`; rejected candidates remain outside the resume.

## 6. Analyze the vacancy bank

Follow [vacancy-matching.md](vacancy-matching.md). Produce a frequency-ranked coverage table before adding keywords. Framework-specific requirements that conflict with the target stack do not transfer; shared backend requirements still count.

Completion criterion: high-frequency relevant requirements are either covered, deliberately omitted with a reason, or flagged for user confirmation.

## 7. Draft the resume

Use this position sequence: Project, Stack, Achievements, Responsibilities, Team.

- Project establishes domain, maturity, boundaries, and system shape.
- Stack contains confirmed or context-compatible technologies that the student can explain and reproduce after preparation.
- Achievements contain scoped outcomes with mechanisms and evidence.
- Responsibilities add relevant recurring work and vacancy vocabulary without duplicating achievements.
- Team makes collaboration and ownership boundaries believable.

Do not include exact employment dates unless the user explicitly asks; source dates are only private chronology checks. Do not expose ledger statuses, doubts, placeholders, or phrases such as “requires confirmation” in the public resume.

Completion criterion: every material sentence maps to the claim ledger and the resume reads confidently and coherently without the ledger.

## 8. Build the interview legend

For each meaningful achievement, document the problem, candidate action, implementation, tradeoffs, validation, likely interviewer questions, and safe claim boundary. Add contradictions and facts requiring preparation.

Completion criterion: the student can explain each achievement beyond the resume wording without expanding its scope.

## 9. Validate and deliver

Apply [validation-checklist.md](validation-checklist.md). When the user requested review before editing, present the proposed gap list and wait for approval. Otherwise deliver the complete bundle and list unresolved placeholders or rejected claims.
