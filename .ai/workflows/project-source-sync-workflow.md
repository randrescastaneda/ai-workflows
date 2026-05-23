# ChatGPT Project Source Sync Workflow

## Purpose

Use this workflow to keep ChatGPT Project sources aligned with version-controlled AI workflow files in GitHub.

## Recommended pattern

GitHub should be the source of truth for reusable prompts and project-specific repo briefs. ChatGPT Project sources should be the working context layer.

## Sync steps

1. Update the relevant Markdown file in GitHub.
2. Copy the updated content into the corresponding ChatGPT Project source.
3. In the ChatGPT Project, ask for a short sanity check:

```text
Review the updated Project source below. Identify any stale, duplicated, ambiguous, or overly broad instructions. Do not rewrite unless needed.
```

4. If the source is project-specific, confirm whether it needs a delta brief or freshness audit.
5. Commit the final source in GitHub.

## When to sync

- after updating a prompt template
- after updating a repo brief
- before starting a major new ChatGPT Project conversation
- before a presentation, release, or public-facing output
- after a significant repo change

## Avoid

- keeping only a ChatGPT copy with no version control
- adding too many stale sources to a Project
- mixing reusable prompts with project-specific facts in the same source
- copying private credentials or personal data into Project sources
