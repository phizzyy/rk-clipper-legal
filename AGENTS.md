# Change tracking and review authority

This repository is `phizzyy/rk-clipper-legal`, the public legal site for RK Stream Clipper.
It is a separate Git repository from `phizzyy/rk-stream-clipper`.

- Use a dedicated branch; preserve unrelated work. Validate changed pages and links.
- Commit and push intended changes and open or update a PR with validation results.
- Claude (the owner's Claude Code session for RK Stream Clipper) owns the code for both
  repositories (owner direction, 20 and 22 Nov 2026) and merges PRs into `main`. Log every
  merge in the clipper repository's REVIEW-LOG.md.
- Every change gets an independent review first: a separate reviewer agent that did not
  write it reads the diff, checks validation, and returns PASS or FAIL against the exact
  head SHA. Fix must-fix findings and review the new head again; new commits need another
  review. Passing checks, silence, or the author's own claim are not a review.
- Merge only the reviewed head SHA, rechecked immediately before merging. Record the verdict
  as a PR comment (not a formal GitHub approval on the account's own PR). Do not enable
  auto-merge, push directly to `main` or release branches, or weaken these rules.
- Do not publish private account details, local chat identifiers, credentials, cookies,
  or private clipper data in this public repository. Changes to privacy/terms must
  remain consistent with the service's actual data handling and owner instructions.
- Explicit owner instructions take precedence.
