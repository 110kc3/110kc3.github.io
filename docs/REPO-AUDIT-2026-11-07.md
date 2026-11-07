# Repository audit — 2026-11-07

Repository: `110kc3.github.io` · Agent: Codex

Audited source: [`3cc3fc7`](https://github.com/110kc3/110kc3.github.io/commit/3cc3fc7594625e71359cf56d72315844074287ba)

Evidence collected: 2026-11-06–2026-11-07. Chat item numbers: 18.

This dated report preserves the findings and feature suggestions already reported in chat.
The owner authorized recording, committing and pushing this documentation. The findings
remain unresolved, and the proposed features have not been selected for implementation.
This is an evidence report, not a second accepted work queue. Existing project decisions,
accepted tasks and owner-only blockers remain authoritative in [README.md](../README.md).

## Verification status

The evidence below describes the earlier audit, including its limitations. This documentation
change does not claim to fix the findings or repeat every runtime reproduction. No production
account, database or infrastructure was changed by those isolated reproductions.

Documentation push: CI verification pending. Check the exact resulting commit on the next
session using [Actions](https://github.com/110kc3/110kc3.github.io/actions?query=branch%3Amain);
no run was awaited for this documentation update. A repository without a workflow has no
CI result to claim.

## 18. Generate discovery files from one project manifest

Type: Feature proposal — not accepted. Estimated effort: Small.

Project facts are duplicated across the homepage, discovery JSON, llms files and sitemap.

**Evidence:** All inspected JSON/XML parsed and the exact-head Pages run passed; this is a maintenance proposal, not a confirmed runtime defect.

**Suggested change:** Introduce one curated project manifest and deterministic generation for the existing discovery surfaces.

**Acceptance if selected:** One project edit updates all relevant outputs; checks detect stale generated files; URLs and existing presentation remain correct.
