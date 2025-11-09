# PROJECT_INSTRUCTIONS.md

## Objective
Build a modular, versioned set of tutorials for deploying and maintaining n8n on GCP Free Tier.
Each file is a standalone tutorial with frontmatter, dependencies, steps, commands, and revisions.

## End Goals
- Clear, minimal, and actionable instructions
- Obsidian and MkDocs friendly
- Easy to record as YouTube videos
- No duplicated content across files

## Rules
1. One topic per file.
2. Use frontmatter on every file:
   ```yaml
   ---
   id: PREFIX-###
   title: Title text
   category: one of [gcp, sys, dock, n8n, mon, sec, upg]
   tags: [keyword1, keyword2]
   video: URL or empty
   updated: YYYY-MM-DD
   requires: [relative/links.md]
   ---
   ```
3. Use three letter prefixes:
   - GCP, SYS, DOCK, N8N, MON, SEC, UPG
4. Use numeric gaps: 010, 020, 030. Insert 015 or 025 when needed.
5. Keep commands in fenced bash blocks.
6. Use relative links only.
7. Add a Revisions section to every file.
8. Tone guidelines:
   - Short sentences
   - Active voice
   - No filler
   - Lists when helpful
   - No semicolons

## Working Style
- Master_Setup_Instructions.md is a hub with links.
- All content lives in grouped folders that match the prefix.
- Files reference dependencies instead of repeating steps.

## Reset Instructions
If context is lost:
1. Open `.meta/PROJECT_INSTRUCTIONS.md` and `.meta/CONTEXT.md`.
2. Say: Reload project context from these files.
3. Continue with the active task in `.meta/CONTEXT.md`.

## Ownership
Maintainer: Johnny Leuthard
Date: 2025-11-08
