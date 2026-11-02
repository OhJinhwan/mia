# Project update rules

- Show the current version as MAJOR.MINOR in the small centered home-only footer in index.html (#site-version). Initial release: 1.0.
- For every subsequent user-requested site update, bump the version once for the completed update, not for each file edit, test, retry, or commit. Text fixes, answer revisions, styling, and small features increment MINOR (1.0 -> 1.1). Large changes to the game structure, main workflow, or substantial feature redesign increment MAJOR and reset MINOR (1.9 -> 2.0). Treat the two parts as integers (1.9 -> 1.10 for another minor release).
- Keep the visible version and its aria-label synchronized. Do not bump for read-only questions or documentation-only changes.
- Keep 정답지.txt synchronized whenever questions, equipment requirements, correct answers, or explanations change.
- Refresh 보건게임-사진포함.zip after site updates, including index.html and assets/ at the archive root.
- The user has authorized committing updates to main and pushing to origin for the existing GitHub Pages site. Preserve unrelated work and remote history.
