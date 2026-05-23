# `.ai` Workspace

This directory contains reusable AI workflow material for ChatGPT, Codex, GitHub-connected analysis, and project-source maintenance.

## Directories

```text
prompts/          Reusable prompt templates
project-sources/  Templates for ChatGPT Project source material
workflows/        Operating procedures and maintenance rules
examples/         Example repo briefs, deltas, and source documents
```

## How to use this repo

1. Pick the prompt template that matches the target repository type.
2. Generate a `repo-brief.md` for the target repo.
3. Save the brief in the target repo under `.ai/repo-brief.md`.
4. Add the brief to the relevant ChatGPT Project as a source.
5. Use delta briefs and freshness audits to keep the brief current.

## Rule of thumb

The central `ai-workflows` repo stores reusable templates. Individual project repos store their own current repo briefs.
