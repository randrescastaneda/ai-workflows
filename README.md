# AI Workflows

Reusable prompts, templates, and operating procedures for working with ChatGPT, Codex, GitHub, Supabase, Telegram, and project-specific AI context.

## Purpose

This repository is the central source of truth for reusable AI workflow material. It is meant to support:

- repository briefing workflows
- ChatGPT Project source management
- Codex read-only repository analysis
- prompt versioning
- Supabase/RAG/Open Brain system analysis
- project onboarding and documentation workflows

## Core idea

Do not ask ChatGPT or Codex to rediscover the same repository from scratch every time. Instead, create a reusable `repo-brief.md` for each important repository, keep that brief in the project repo, and also add it to the relevant ChatGPT Project as a source.

## Recommended pattern

```text
central ai-workflows repo
  reusable prompts, templates, policies, operating procedures

individual project repo
  .ai/repo-brief.md
  .ai/repo-delta.md
  .ai/project-instructions.md

ChatGPT Project
  saved prompt pack
  saved repo brief
  saved project-specific instructions
```

## Folder structure

```text
.ai/
  prompts/
  project-sources/
  workflows/
  examples/
```

## Operating rule

```text
Minor change -> no update
Meaningful change -> delta brief
Major change or public deliverable -> freshness audit + update canonical brief
Release or presentation -> live repo verification
```

## Important boundary

A repo brief is a cached interpretation of a repository. It is not a replacement for the live repository. Use it for orientation, synthesis, presentations, planning, and documentation. Verify against the live repo before making important technical, public, financial, legal, operational, or high-stakes claims.
