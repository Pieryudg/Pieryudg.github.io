# AGENTS

This repository is the public GitHub Pages site for `https://pieryudg.github.io/`.

## Collaboration Model

- Cursor/Claude owns planning, information architecture, content strategy, and review.
- VS Code/Codex owns implementation, file edits, local verification, Git, and GitHub Pages publishing.
- GitHub is the source of truth for commits, Pages deployment, and public links.

## Codex Execution Rules

- Keep the site static unless there is a clear reason to add a build system.
- Preserve fast-loading plain HTML/CSS.
- Prefer small scoped commits: one content or layout change at a time.
- Do not add analytics, trackers, cookies, forms, or external scripts without explicit approval.
- Keep private NAS URLs out of public pages until the user confirms they are meant to be public.
- Run a local static preview before publishing meaningful visual changes:

```bash
python3 -m http.server 8080
```

- Check these before pushing:

```bash
git status --short
python3 -m http.server 8080
```

## Site Style

- Quiet, practical, and engineering-focused.
- Use restrained colors and clear project cards.
- Keep headings direct and avoid marketing fluff.
- Prioritize useful links, project context, and next actions.

## Publishing

GitHub Pages publishes from:

```text
main /
```

Public URL:

```text
https://pieryudg.github.io/
```
