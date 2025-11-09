# AI_PROMPTS.md

## Create a new tutorial
You are adding a new modular tutorial. Follow the project rules and tone.

Inputs:
- prefix, id, title, category, tags, dependencies list

Output:
- A Markdown file with frontmatter, Overview, Dependencies, Steps, Commands, Verification, Notes, Revisions

Template prompt:
```
Create a new tutorial file.
prefix: N8N
id: 090
title: Google Sheets Connector
category: n8n
tags: [n8n, google, sheets, oauth]
requires:
  - ../GCP/GCP-010_Create-Project.md
  - ../GCP/GCP-040_Create-OAuth-Credentials.md

Rules:
- Use the standard frontmatter
- Write short steps
- Include bash blocks if needed
- Include a Verification section
- End with a Revisions entry for today
```

## Update an existing tutorial
Goal: update for UI or version changes without rewriting unrelated parts.

Template prompt:
```
Update file N8N-090_Google-Sheets-Connector.md.
Change:
- New Google Cloud UI for OAuth
- Add Drive scope

Keep:
- File structure
- Dependencies list

Also:
- Update 'updated' date
- Add a new Revisions line
```

## Build a YouTube-ready outline
```
Create a recording outline for N8N-090.
Sections:
- Hook
- Prereqs
- Steps
- Demo
- Pitfalls
- CTA
```

## Generate a dependency map
```
Scan all *.md in repo.
Build a table: id, title, requires[].
Output Markdown.
```
