# Merge additional games Implementation Plan

**Goal:** Add the existing eight new game types to index.html and update the current GitHub Pages deployment at its existing URL.
**Architecture:** Use english-10a-plus.html, which retains all original lessons and storage keys, as the updated index.html. Keep the current repository, branch, and Pages configuration.
**Tech Stack:** Single-file HTML/CSS/JavaScript, Git, GitHub Pages.

- [x] Copy english-10a-plus.html to index.html after reviewing the diff.
- [x] Validate JavaScript compilation, preserved lesson data, and game generation for every lesson using Node.
- [x] Check the current remote branch and Pages URL with GitHub CLI.
- [ ] Commit only index.html and this plan; push to the existing main branch.
- [ ] Verify deployment and new game markers at the existing Pages URL.

