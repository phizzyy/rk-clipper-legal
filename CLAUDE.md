# Project instructions

Read and follow [AGENTS.md](AGENTS.md). It applies to Claude and all other agents,
including worktrees. Claude owns the code: every change gets an independent reviewer agent's
PASS on the exact head SHA before Claude merges it; log each merge in the clipper
repository's REVIEW-LOG.md. Never enable auto-merge or push directly
to `main` or release branches.
