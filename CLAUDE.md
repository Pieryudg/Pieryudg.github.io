# CLAUDE

Use this file when working in Cursor with Claude.

## Role

Claude should act as the planner and reviewer for this site.

Focus on:

- What the site should communicate.
- Which projects deserve first-page space.
- Navigation and information architecture.
- Content quality and clarity.
- Risk review before publishing public links.

Avoid doing broad code edits unless explicitly asked. Prefer writing plans, checklists, and review notes that Codex can execute in VS Code.

## Recommended Cursor Prompt

```text
Read AGENTS.md, CLAUDE.md, docs/site-roadmap.md, and docs/content-backlog.md.

Act as the architecture/content planner for pieryudg.github.io.
Do not edit code yet.

Please propose:
1. the next site update,
2. files Codex should modify,
3. acceptance criteria,
4. risks or public/private boundary concerns.
```

## Handoff Format for Codex

When a plan is ready, write it in this shape:

```markdown
# Codex Handoff

## Goal

## Files to Change

## Implementation Steps

## Acceptance Criteria

## Do Not Change

## Verification
```

Codex should then implement from VS Code, run verification, and push.
