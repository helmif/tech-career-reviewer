# Tech Career Reviewer

An evidence-based Agent Skill for reviewing CVs, LinkedIn profiles, portfolios, and target-job alignment across software engineering, quality assurance, product management, and product design.

The reviewer improves how real experience is presented. It does not invent achievements, metrics, credentials, or responsibilities.

## What it does

- Simulates a fast recruiter scan.
- Builds a source-linked evidence map.
- Distinguishes presentation, evidence, qualification, and consistency gaps.
- Evaluates materials with role-specific rubrics.
- Asks focused questions to recover missing achievements.
- Suggests claim-safe rewrites with provenance.
- Recommends GitHub, portfolio, or case-study proof when wording is not enough.

## Install in Claude Code

Add this repository as a marketplace, then install the plugin:

```text
/plugin marketplace add helmif/tech-career-reviewer
/plugin install tech-career-reviewer@tech-career-reviewer
```

Invoke it explicitly with:

```text
/tech-career-reviewer:tech-career-reviewer Review my CV for a senior backend engineer role.
```

For local development:

```bash
claude --plugin-dir ./plugins/tech-career-reviewer
```

## Install in Codex

Add the Git marketplace and install the plugin:

```bash
codex plugin marketplace add helmif/tech-career-reviewer
codex plugin add tech-career-reviewer@tech-career-reviewer
```

Then start a new session and invoke `$tech-career-reviewer`, or ask for a CV, LinkedIn, portfolio, or technology-career review and let the skill trigger automatically.

## Suggested inputs

Provide as many as are available:

- CV or resume
- LinkedIn export or pasted profile text
- Target role and seniority
- Job description
- GitHub profile or portfolio
- Location or job market when relevant

The skill still produces a best-effort review when some inputs are missing and clearly labels uncertain conclusions.

## Example prompts

```text
Review my CV and LinkedIn profile for senior frontend engineer roles. Do not rewrite unsupported claims.
```

```text
Compare my experience with this QA automation job and identify demonstrated, transferable, unverified, and missing requirements.
```

```text
Interview me to recover measurable product-management achievements before rewriting my experience section.
```

```text
Audit my product design portfolio as a recruiter. Prioritize the three case-study changes most likely to improve my evidence.
```

## Repository structure

```text
.
├── .agents/plugins/       Codex marketplace
├── .claude-plugin/        Claude marketplace
└── plugins/
    └── tech-career-reviewer/
        ├── .claude-plugin/  Claude manifest
        ├── .codex-plugin/   Codex manifest
        └── skills/
            └── tech-career-reviewer/
                ├── SKILL.md       Portable workflow
                ├── agents/        Host-facing metadata
                └── references/    Evaluation and role rubrics
```

## Privacy and integrity

- Use user-provided exports, files, pasted text, or explicitly authorized tools.
- Remove unnecessary personal data before sharing documents.
- Do not publish confidential employer work as portfolio evidence.
- Verify every metric and substantive claim before using a proposed rewrite.

## License

[MIT](LICENSE)
