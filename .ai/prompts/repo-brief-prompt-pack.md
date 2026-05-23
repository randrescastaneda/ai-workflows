# Repository Brief Prompt Pack

This file is an index for the repo-brief prompt family.

## Purpose

Use these prompts to generate reusable `repo-brief.md` files for technical, documentation, research, and AI infrastructure repositories.

## Prompt selection

| Repo type | Prompt file |
|---|---|
| Unknown or mixed repo | `repo-brief-generic.md` |
| R package | `repo-brief-r-package.md` |
| Quarto book | `repo-brief-quarto-book.md` |
| Supabase RAG / Open Brain | `repo-brief-supabase-rag-open-brain.md` |
| Codex read-only analysis | `codex-read-only-repo-analyst.md` |
| Update after changes | `repo-delta-template.md` |
| Pre-deliverable check | `repo-freshness-audit-template.md` |

## Standard workflow

1. Classify the repository.
2. Select the closest repo-brief prompt.
3. Generate the first `repo-brief.md`.
4. Clean the brief into a durable Project source.
5. Save the brief in the target repo under `.ai/repo-brief.md`.
6. Add the same brief to the relevant ChatGPT Project as a source.
7. Update with delta briefs when the repo changes meaningfully.
8. Run a freshness audit before presentations, releases, public docs, or architecture decisions.

## Boundary

A repo brief is a cached interpretation, not the live repo. Verify important claims against the live repository before using them in public, operational, or high-stakes contexts.
