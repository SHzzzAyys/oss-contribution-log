# Open Source Contribution Log

This repository tracks open-source contribution work around reproducible
research, Manubot-style manuscript workflows, citation metadata, and research
repository hygiene.

The purpose is to keep contributions accountable and easy to review. It is not a
claim of broad adoption, user count, or project impact.

## Contribution Principles

- Read the target repository's README, contribution guide, and open issues
  before commenting or opening a pull request.
- Prefer reproducible evidence: commands, environment details, logs, and links.
- Keep public comments concise and useful to maintainers.
- Avoid private contact information, private academic drafts, local workspace
  paths, tokens, and non-public review material.
- Do not use issues or pull requests for self-promotion.

## Primary Contribution Lane

Current focus: Manubot and reproducible research writing workflows.

Priority repositories:

| Repository | Contribution angle |
| --- | --- |
| [`manubot/rootstock`](https://github.com/manubot/rootstock) | Local build docs, generated tables, manuscript workflow documentation. |
| [`manubot/manubot`](https://github.com/manubot/manubot) | PubMed/PMC citation warnings, reference error reporting, metadata diagnostics. |
| [`manubot/manubot-ai-editor`](https://github.com/manubot/manubot-ai-editor) | Documentation structure, README clarity, prompt/config documentation. |

## Activity Log

| Date | Target | Type | Status | Evidence |
| --- | --- | --- | --- | --- |
| 2026-05-31 | [`SHzzzAyys/manubot-paper`](https://github.com/SHzzzAyys/manubot-paper) | Repository foundation | Released | `v0.1.1` release, CI pass, citation metadata, reproducibility docs, release/privacy checklist. |
| 2026-05-31 | [`manubot/rootstock#494`](https://github.com/manubot/rootstock/issues/494#issuecomment-4585651722) | Issue triage | Commented | Generated tables and Manubot manuscript workflow notes. |
| 2026-05-31 | [`manubot/manubot#374`](https://github.com/manubot/manubot/issues/374#issuecomment-4585651793) | Reproduction note | Commented | Windows/Manubot 0.6.1 PubMed citation failure behavior. |
| 2026-05-31 | [`manubot/manubot-ai-editor#76`](https://github.com/manubot/manubot-ai-editor/issues/76#issuecomment-4585651861) | Documentation note | Commented | Documentation website structure and discoverability. |

### 2026-05-31 - SHzzzAyys/manubot-paper

- Type: Repository foundation and release.
- Summary: Merged open-source readiness improvements and published `v0.1.1`.
- Evidence: https://github.com/SHzzzAyys/manubot-paper/releases/tag/v0.1.1
- Verification: GitHub Actions Manubot workflow passed on `main`.
- Maintainer feedback: Self-maintained repository.
- Follow-up: Use the repository as a public example when discussing Manubot
  workflow documentation, without claiming broad adoption.

### 2026-05-31 - manubot/rootstock#494

- Type: Issue triage and workflow note.
- Summary: Added a conservative generated-table workflow framing for Manubot
  manuscripts and offered to help draft documentation if maintainers agree.
- Evidence: https://github.com/manubot/rootstock/issues/494#issuecomment-4585651722
- Verification: Compared the issue discussion with a public generated-table
  workflow in `manubot-paper`.
- Maintainer feedback: Pending.
- Follow-up: Wait for maintainer direction before opening a documentation PR.

### 2026-05-31 - manubot/manubot#374

- Type: Reproduction note.
- Summary: Tested `manubot cite pubmed:28559793` in a fresh Windows Python 3.11
  environment with Manubot 0.6.1; observed empty CSL output with connection
  warnings while direct EFetch requests succeeded.
- Evidence: https://github.com/manubot/manubot/issues/374#issuecomment-4585651793
- Verification: Five Manubot CLI runs and three direct EFetch requests.
- Maintainer feedback: Pending.
- Follow-up: If maintainers confirm scope, investigate retry/reporting behavior
  or citation diagnostics related to `manubot/manubot#336`.

### 2026-05-31 - manubot/manubot-ai-editor#76

- Type: Documentation structure note.
- Summary: Suggested a minimal docsite structure that keeps the README short and
  moves deeper concepts, config reference, operations, and developer docs into
  navigable documentation.
- Evidence: https://github.com/manubot/manubot-ai-editor/issues/76#issuecomment-4585651861
- Verification: Reviewed the issue request and current documentation goal.
- Maintainer feedback: Pending.
- Follow-up: Offer a documentation inventory PR if maintainers prefer that
  direction.

## Update Format

Use this format when recording a contribution:

```markdown
### YYYY-MM-DD - owner/repo#issue-or-pr

- Type:
- Summary:
- Evidence:
- Verification:
- Maintainer feedback:
- Follow-up:
```
