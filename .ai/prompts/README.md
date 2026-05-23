# Prompt Templates

Reusable prompts for repository briefing, Codex analysis, ChatGPT Project source creation, delta updates, and freshness audits.

## Core prompts

- `repo-brief-generic.md` — for unclear or mixed repositories
- `repo-brief-r-package.md` — for R package repositories
- `repo-brief-quarto-book.md` — for Quarto book repositories
- `repo-brief-supabase-rag-open-brain.md` — for Supabase-backed RAG/Open Brain systems
- `codex-read-only-repo-analyst.md` — for Codex analysis without implementation
- `repo-delta-template.md` — for meaningful repo changes
- `repo-freshness-audit-template.md` — before presentations, releases, or decisions

## How to use

1. Select the closest template.
2. Replace `<owner/repo>` and any bracketed placeholders.
3. Run it in ChatGPT with GitHub access, Deep Research, or Codex.
4. Save the resulting `repo-brief.md` into the target repo and the relevant ChatGPT Project.

## Design principle

Tailor the prompt to the repository type. A Quarto book should be analyzed as a book and publishing system. An R package should be analyzed as a package and user-facing tool. A Supabase RAG/Open Brain repo should be analyzed as knowledge infrastructure.
