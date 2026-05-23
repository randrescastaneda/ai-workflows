# Repo Brief Operating Model

## Purpose

A repo brief is a reusable context artifact that helps ChatGPT, Codex, and collaborators understand a repository without rediscovering it from scratch in every session.

## Principle

The repo brief is a cached interpretation of the repository. It should be useful, structured, and maintained, but it is not a replacement for the live repo.

## Storage model

```text
central ai-workflows repo
  reusable templates and workflows

target project repo
  .ai/repo-brief.md
  .ai/repo-delta.md
  .ai/project-instructions.md

ChatGPT Project
  latest repo brief as source
  relevant prompt pack as source
```

## Update rhythm

```text
Minor change -> no update
Meaningful change -> delta brief
Major change or public deliverable -> freshness audit + update canonical brief
Release or presentation -> live verification
```

## What belongs in a repo brief

- repository purpose
- intended users
- conceptual model
- repository map
- main workflows
- important functions, chapters, routes, or components
- dependencies and external systems
- runtime, deployment, or publication assumptions
- testing and quality signals
- risks and open questions
- source evidence

## What does not belong

- credentials
- tokens
- private URLs unless necessary and safe
- unnecessary raw file dumps
- unverified claims
- personal data
- stale speculation

## Quality checklist

A strong repo brief should be:

- accurate
- concise but sufficiently detailed
- structured
- evidence-based
- clear about uncertainty
- useful for future tasks
- easy to update
