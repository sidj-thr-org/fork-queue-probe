# fork-queue-probe

Merge-queue replica for **QVAC-23431**. Reproduces `tetherto/qvac`'s
merge-blocking logic so queue behaviour can be observed rather than inferred.

This is round 2. Round 1's history is tagged `round-1-final`.

- Plan, test case matrix and checkpoints:
  `main-repos/openspec/changes/qvac-merge-queue-validation/`
- Results: `tether-obsidian/tickets/QVAC-23431-test-matrix.md`

Nothing here builds or tests anything real. Only the control flow that gates a
merge is reproduced.

## Accounts

| Account | Role |
|---|---|
| `sidj-thr` | org owner, codeowner, `fork-ci` reviewer |
| `sidj-ubq` | read-only, opens fork pull requests |
