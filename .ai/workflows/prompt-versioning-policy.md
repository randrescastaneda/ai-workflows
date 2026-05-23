# Prompt Versioning Policy

## Purpose

Prompts in this repo should be treated as reusable workflow assets, not disposable chat text.

## Versioning principles

- Prefer small, clear changes over large unreviewable rewrites.
- Keep prompt purpose and boundaries explicit.
- Preserve tested prompts unless there is a clear reason to change them.
- Add project-specific variants rather than overloading one universal prompt.
- Record why a prompt changed in the commit message.

## Suggested version labels

Use simple date or semantic labels in prompt headings when helpful:

```text
Prompt name v1
Prompt name v1.1
Prompt name — updated 2026-05-23
```

## When to create a new prompt variant

Create a new prompt variant when the target differs materially by repository type or workflow, for example:

- R package
- Quarto book
- API service
- data pipeline
- Supabase RAG/Open Brain
- research project
- production readiness review
- presentation planning

## Review checklist

Before committing prompt changes, ask:

- Is the intended use clear?
- Are the boundaries clear?
- Does the prompt prevent invented details?
- Does it require source evidence where appropriate?
- Does it handle uncertainty?
- Is it reusable outside the original chat?
- Does it avoid private or sensitive information?
