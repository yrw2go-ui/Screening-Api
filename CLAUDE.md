# How changes are shipped

Keep replies short and ask at most one question at a time.

- Make each change on its own branch off the default branch, test it before showing it, then commit and push the branch.
- Show what changed (screenshots or a short summary), then **offer a Ship button**: ask with the question tool using a single "Ship" option (plus "Not yet"). Never make the owner type "ship". A click on it, or the word "ship", "ship it" or "merge", is the go-ahead. Do not open a PR or merge before it.
- On Ship: open a PR into the default branch, squash-merge it, and report the result (and the deploy state, if the repo deploys).
- Never put secrets in chat, commits or PRs. Do not put model names or identifiers in commits, PR text or code. Destructive actions need the owner's confirmation first.
