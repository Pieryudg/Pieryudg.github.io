# Publishing Workflow

## Standard Flow

1. Cursor/Claude plans the update.
2. Save the accepted plan in `docs/` or paste it to Codex.
3. VS Code/Codex implements the change.
4. Codex runs a local preview.
5. Codex commits and pushes to `main`.
6. GitHub Pages publishes automatically.

## Local Preview

From the repo root:

```bash
python3 -m http.server 8080
```

Open:

```text
http://localhost:8080
```

## Publish

```bash
git status --short
git add .
git commit -m "Update site"
git push
```

## Live Site

```text
https://pieryudg.github.io/
```

## Verification

After push:

```bash
gh api repos/Pieryudg/Pieryudg.github.io/pages --jq '.status'
curl -I -L https://pieryudg.github.io/
```
