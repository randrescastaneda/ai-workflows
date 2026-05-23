# Codex Read-Only Repository Analyst Prompt

Use this in Codex when you want repository understanding, not implementation.

```text
Do not edit files.
Do not create commits.
Do not create a branch.
Do not open a pull request.
Do not modify the repository.

I want a repository intelligence brief for planning, documentation, presentation, and architectural understanding.

Analyze this repository and produce a structured brief with:

1. Repository purpose
2. Intended users and use cases
3. Repository structure
4. Main workflows
5. Main exported functions, modules, scripts, routes, chapters, or components
6. Internal architecture, content architecture, or data flow
7. Important dependencies and external systems
8. Documentation, examples, vignettes, book chapters, tests, CI, render, or publication signals
9. Deployment, publication, or runtime assumptions
10. Presentation-worthy storylines and demo ideas
11. Risks, unclear areas, and maintainer questions
12. Files consulted and what each file supports

Important:
- Separate facts from inferences.
- Include file paths as evidence.
- Flag uncertainty.
- Prioritize understanding over recommendations.
- Only suggest implementation changes if they are relevant as risks or open questions.
```
