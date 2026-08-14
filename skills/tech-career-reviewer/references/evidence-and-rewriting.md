# Evidence and rewriting

## Claim ledger

Assign one status to every material claim:

| Status | Use |
|---|---|
| Supported | Explicitly present in a supplied source or observable artifact. |
| Candidate-confirmed | Added or clarified directly by the candidate during the conversation. |
| Inferred — confirm | Reasonable interpretation that must not be presented as fact yet. |
| Unsupported | No supplied basis; exclude from final copy. |
| Contradictory | Conflicts with another source; resolve before use. |

For an observable public artifact, distinguish what is directly visible from what would require runtime, business, or team context. A repository can demonstrate code and documentation; it usually cannot prove production scale or business results by itself.

## Evidence hierarchy

Prefer, in order:

1. Candidate-confirmed facts supported by an artifact or consistent source.
2. Specific facts consistently present across supplied materials.
3. A claim present in one candidate-controlled source.
4. A reasonable inference clearly labeled for confirmation.
5. Generic assumptions based on title or industry; never use these as candidate facts.

## Recovering impact

Do not demand revenue metrics for every role. Valid impact can include:

- time, cost, throughput, adoption, conversion, retention, or revenue;
- reliability, latency, defects, risk, security, accessibility, or compliance;
- decision quality, learning, cycle time, operational load, or team leverage;
- user comprehension, task success, satisfaction, or support reduction;
- delivery of a difficult capability under meaningful constraints.

Ask for the baseline and comparison period when a metric is provided. If a result was shared by a team, identify the candidate's contribution without claiming sole credit.

## Rewrite pattern

Use the smallest structure that makes the evidence clear:

`Action and ownership + scope or difficulty + outcome or reason it mattered`

Strong bullets do not need to follow one rigid formula. Lead with the most differentiating element and keep technology subordinate to the achievement unless the technology itself is the hiring signal.

### Safe transformation

Original:

> Worked on microservices and fixed production bugs.

Safe draft:

> Diagnosed and resolved production failures across `[confirm service count]` services, improving `[confirm reliability or recovery outcome]`.

Keep both placeholders until the candidate confirms them. If no measurable result exists, use a factual outcome:

> Diagnosed cross-service production failures and introduced a repeatable incident checklist for the support rotation.

Use that version only when the checklist is supported.

## LinkedIn rewriting

- Make the headline specific enough to communicate role and useful specialization.
- Use the About section to connect past evidence, current strength, and target direction.
- Keep experience entries evidence-rich and easier to scan than a narrative essay.
- Recommend Featured items only when they materially support the target.
- Avoid inflated identity claims such as "visionary," "guru," or "world-class" without extraordinary evidence.

## Portfolio and GitHub evidence

Evaluate:

- relevance of pinned or featured work;
- clarity of problem, users, constraints, decisions, and tradeoffs;
- README or case-study quality;
- evidence of the candidate's own contribution;
- tests, documentation, accessibility, maintainability, or decision records as appropriate;
- whether the artifact is safe and authorized to share.

Do not reward raw contribution volume without context. Do not recommend publishing confidential employer material.

## Voice and quality checks

- Preserve terminology the candidate can explain in an interview.
- Prefer concrete verbs and plain language.
- Remove repetition, filler summaries, and generic enthusiasm.
- Avoid overusing superlatives, em dashes, slogans, or symmetrical AI-style phrasing.
- Keep tense and capitalization consistent.
- Verify every number, named technology, and scope claim before marking copy final.
