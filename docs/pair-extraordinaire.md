# Pair Extraordinaire

Awarded for a coauthored commit in a merged pull request.

## Tiers

| Tier | Coauthored merged PRs |
| --- | --- |
| Base | 1 |
| Bronze (x2) | 10 |
| Silver (x3) | 24 |
| Gold (x4) | 48 |

## Live test log, this repo

1. Attempt 1: co-author trailer pointing at an email with no GitHub account behind it. Merged 2026-08-25. No badge, as suspected.
2. Attempt 2: owner authored, collaborator co-authored via account-linked noreply address, merge commit. Merged 2026-08-27. No badge after a week.
3. Attempt 3: collaborator authored via web UI, owner co-authored via account-linked noreply address, merge commit. Merged 2026-08-30. No badge after four days.
4. Attempt 4, this PR: same valid trailer, squash merged. Squash rebuilds the commit at merge time and is the variant most community reports describe as reliably working.

## Notes

- The commit needs a `Co-authored-by: Name <email>` trailer, separated from the body by a blank line, in a merged PR.
- Use the co-author's GitHub noreply address (ID+username@users.noreply.github.com).
- If attempt 4 also fails, the remaining explanation is a stuck grant pipeline, and the path is a GitHub Support ticket, which is routine for missing achievements.

Sources: community-maintained criteria list plus live tests in this repo; updated 2026-09-03.
