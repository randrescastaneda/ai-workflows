# Supabase RAG / Open Brain Repository Brief Prompt

Use this for repositories that contain a Supabase-backed RAG system, personal/family knowledge base, Telegram bot, Codex integration layer, or related AI operating system infrastructure.

```text
Use the connected GitHub repository <owner/repo>.

I am not asking you to implement changes. I want a reusable repository briefing that I can save as a source in a ChatGPT Project.

This repository contains a Supabase-backed RAG / Open Brain system. Analyze it as a knowledge infrastructure project, database-backed application, AI integration layer, automation system, and operational workflow—not merely as a code repository.

Please produce a structured repo brief with the following sections:

1. Brief Metadata
- repository name
- branch analyzed, if visible
- commit SHA, if visible
- date analyzed
- access method
- confidence level
- known limitations

2. Executive Summary
Explain what this repository appears to do, what problem it solves, and why it exists.

3. System Purpose and Scope
Explain the purpose of the Open Brain / RAG system. Distinguish visible repo facts, reasonable inferences, and unclear or missing information. Clarify whether the system appears designed for personal knowledge management, family knowledge management, research memory, project memory, Telegram access, Codex access, ChatGPT/LLM-assisted retrieval, automation and decision tracking, or some combination of these.

4. Users, Roles, and Access Paths
Identify who or what interacts with the system: human users, Telegram users, Codex or coding agents, ChatGPT workflows, admin users, service roles, scheduled jobs, and external tools. Explain visible access paths and likely permissions model.

5. Repository Structure
Map the major folders and files. Pay special attention to Supabase configuration, SQL migrations, schema files, edge functions, API/server files, Telegram bot code, ingestion scripts, embedding scripts, retrieval/search logic, prompts or agent instructions, environment/config files, deployment files, documentation, and tests.

6. Database and Supabase Architecture
Analyze the Supabase/Postgres layer. Look for tables, views, functions, triggers, row-level security policies, storage buckets, auth configuration, migrations, seed data, vector extension usage, embedding tables, metadata columns, and audit logs. Explain the database model in plain English.

7. RAG Architecture and Retrieval Flow
Explain how information appears to move from source material to AI-usable context. Cover ingestion, chunking, metadata extraction, embedding generation, vector storage, keyword/full-text search, hybrid search, retrieval functions, reranking, prompt assembly, response generation, and citation/source handling if visible. If the RAG pipeline is incomplete or unclear, say so.

8. Knowledge Domains and Content Types
Identify what kinds of knowledge the system appears to store or retrieve, such as family decisions, research notes, project notes, documents, URLs, conversations, tasks, financial planning notes, travel planning notes, repository briefs, prompt packs, and audit logs. Do not infer sensitive content unless the repo clearly supports it.

9. Telegram Integration
If present, analyze the Telegram layer. Explain commands or interactions, user identification, triggered actions, message flow into/out of Supabase, approval/logging/permission behavior, and operational risks. If Telegram is not visible, say so.

10. Codex / ChatGPT / LLM Integration
Analyze how the repo supports AI-agent interaction. Look for prompts, tool instructions, agent files, Codex instructions, ChatGPT Project source material, API calls to OpenAI or other LLMs, retrieval endpoints used by agents, generated summaries or briefs, and approval workflows. Explain whether the repo is designed for human use, agent use, or both.

11. Automation and Workflow Model
Identify recurring, event-driven, or manual workflows. Look for scheduled jobs, webhooks, GitHub Actions, cron jobs, Supabase scheduled functions, Telegram-triggered workflows, approval flows, family decision workflows, research update workflows, and task creation/completion workflows.

12. Security, Privacy, and Access Control
Analyze visible security/privacy controls. Look for RLS policies, user-role tables, environment variables, service-role usage, secrets handling, personal/family data handling, audit logging, admin functions, and public/private API boundaries. Flag risks carefully without inventing vulnerabilities.

13. Data Lifecycle and Maintenance
Explain how data is created, updated, archived, deleted, or audited. Look for created_at/updated_at fields, source tracking, document versions, embedding refresh workflows, stale data handling, soft deletes, audit logs, and backup/restore assumptions.

14. External Dependencies and Services
Identify important dependencies: Supabase, Postgres extensions, OpenAI or other model APIs, Telegram Bot API, GitHub, deployment platforms, local scripts, package dependencies, and environment variables.

15. Documentation and Operator Guidance
Summarize the README, setup docs, runbooks, comments, and operational instructions. Explain what a future maintainer would need to know to run, debug, or extend the system.

16. Testing, Validation, and Quality Signals
Analyze tests, migration checks, type checks, linting, CI, SQL validation, or manual verification steps. Identify quality gaps or areas that require manual review.

17. System Diagram in Words
Describe the system as a simple architecture diagram in prose. Example: User → Telegram → Bot/API → Supabase → retrieval function → LLM → response → audit log. Use only components supported by repo evidence.

18. Presentation-Relevant Story
Explain how this repository could be presented to a technical or semi-technical audience. Include a possible thesis, 8–12 slide narrative angle, demo ideas, system diagram ideas, risks/boundaries to mention, and what the audience should understand.

19. Strengths
Identify what the system/repo already does well: database structure, retrieval design, workflow clarity, extensibility, auditability, user access model, maintainability, and AI-agent readiness.

20. Risks, Gaps, and Open Questions
Separate architecture gaps, database/schema gaps, RAG/retrieval gaps, security/privacy gaps, Telegram integration gaps, Codex/ChatGPT integration gaps, documentation gaps, and operational questions.

21. Suggested Future Uses of This Brief
Explain how this repo brief can be reused inside a ChatGPT Project, Codex session, or future automation.

22. Source Evidence
List the most important files consulted and what each file supported.

Important rules:
- Do not invent details.
- Distinguish visible repo facts from inferences.
- Cite repository files or snippets wherever possible.
- If something is uncertain, say so.
- Do not expose or repeat secrets, tokens, private URLs, or sensitive personal data.
- Do not suggest implementation changes unless they are directly relevant as risks, open questions, or maintenance recommendations.
- Treat this as a reusable knowledge artifact, not a one-time answer.
```
