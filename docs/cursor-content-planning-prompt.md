# Cursor Content Planning Prompt

Use this prompt in Cursor with Claude.

```text
Read these files first:

- AGENTS.md
- CLAUDE.md
- docs/site-roadmap.md
- docs/content-backlog.md
- docs/publishing-workflow.md
- index.html

You are the content strategist and information architect for https://pieryudg.github.io/.

Goal:
Help plan useful website content for a personal engineering/software homepage. The site should present Pieryudg's public projects, tools, GitHub work, and future NAS/self-hosted services without exposing private infrastructure.

Do not edit files yet.

Please propose:

1. Homepage message
   - What should the site say in one sentence?
   - What should the visitor understand in the first 10 seconds?

2. Site sections
   - Which sections should exist now?
   - Which sections should wait?
   - What should stay off the public site?

3. Project cards
   - Which GitHub repositories should be highlighted?
   - For each highlighted project, write a short title, 1 sentence description, and status label.

4. Data Plot Chart Analyzer page
   - What should a dedicated project page include?
   - What screenshots, examples, and download/build links would be useful?

5. NAS/self-hosted content
   - How should the site mention future NAS services safely?
   - What wording avoids revealing private URLs or infrastructure?

6. Next update for Codex
   - Give a small implementation plan for VS Code/Codex.
   - Include files to change, exact content to add, acceptance criteria, and what not to change.

Output format:

# Content Plan

## Homepage Message

## Recommended Site Structure

## Project Cards

## Data Plot Chart Analyzer Page Plan

## NAS/Self-hosted Wording

## Codex Handoff

### Goal

### Files to Change

### Implementation Steps

### Acceptance Criteria

### Do Not Change
```

