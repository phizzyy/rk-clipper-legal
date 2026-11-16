# Change tracking and review authority

This repository is `phizzyy/rk-clipper-legal`, the public legal site for RK Stream Clipper.
It is a separate Git repository from `phizzyy/rk-stream-clipper`.

- Use a dedicated branch; preserve unrelated work. Validate changed pages and links.
- Commit and push intended changes and open or update a PR with validation results.
- The owner's designated Codex chat **Configure centralized PR review** is the single
  PR Reviewer and merge authority for both repositories. Other agents must submit
  their work to that reviewer, not assume the role themselves.
- Submit the repository, PR URL, branch, exact head commit SHA, change summary,
  validation results, and any risks or blockers. In the owner's local workspace,
  read `D:\Dev\AGENTS.md` for the exact review chat ID and routing instructions.
  Send the handoff there when authorized chat messaging is available; otherwise
  include it in the final response for the owner to bring to the reviewer.
- Implementation agents must not self-approve, merge, enable auto-merge, push to
  `main` or release branches, or weaken these rules to bypass review.
- Wait for an explicit reviewer decision tied to the exact head SHA. New commits
  require another review. Passing checks, silence, and submission are not approval.
- Only the designated reviewer manages routine merges within the owner's delegated
  scope and any narrower current instruction. The reviewer must inspect the diff,
  check validation, record a SHA-specific verdict on the PR, and recheck the expected
  head SHA before merging. If using the author's GitHub account, record a PR comment
  rather than claiming a formal approving review on that account's own PR.
- Do not publish private account details, local chat identifiers, credentials, cookies,
  or private clipper data in this public repository. Changes to privacy/terms must
  remain consistent with the service's actual data handling and owner instructions.
- Explicit owner instructions take precedence. Agents must not reassign the reviewer.

This is an instruction-based review process, not a GitHub-enforced merge restriction
or an automatic review service. Existing chats must read the updated instructions;
do not claim a handoff was delivered unless it was actually sent.
