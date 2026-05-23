# Repository Delta Brief Template

Use this after meaningful repository changes.

```text
Use the connected GitHub repository <owner/repo> and the saved repo brief.

I want to update the repo brief, not implement anything.

Please compare the current repository against the saved repo brief and produce a delta brief.

Focus on changes that affect:
- repository purpose or scope
- public API
- exported functions
- internal architecture
- main workflows
- examples, README, vignettes, book chapters, or documentation
- tests and validation
- dependencies
- deployment/runtime/publication behavior
- API routes, gateways, versioning, or publication paths
- presentation, onboarding, or documentation story

Return:

1. Summary of Changes
A concise summary of what appears to have changed.

2. Sections of the Existing Repo Brief That Are Now Stale
List each affected section and explain why.

3. New Facts to Add
Facts that should be added to the repo brief, with repository evidence.

4. Facts to Remove or Revise
Statements from the existing brief that are outdated, misleading, or incomplete.

5. New Open Questions
Questions that require maintainer confirmation.

6. Suggested Patch to `repo-brief.md`
Provide a clear replacement or amendment for the affected sections only.

Important rules:
- Do not rewrite the entire brief unless necessary.
- Do not invent change history if commit comparison is unavailable.
- If you cannot compare against a prior commit, say that and compare the current repo state to the saved brief instead.
- Distinguish between confirmed changes and inferred changes.
- Cite files or snippets wherever possible.
```
