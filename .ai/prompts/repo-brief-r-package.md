# R Package Repository Brief Prompt

Use this for R package repositories.

```text
Use the connected GitHub repository <owner/repo>.

I am not asking you to implement changes. I want a reusable repository briefing that I can save as a source in a ChatGPT Project.

This repository contains an R package. Analyze it as a package, user-facing tool, documentation system, and maintainable codebase.

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
Explain what this R package does, what problem it solves, and why it exists.

3. Intended Users and Use Cases
Identify likely users, maintainers, downstream packages, analysts, researchers, or systems.

4. Package Purpose and Conceptual Model
Explain the package’s main conceptual model. What does the package help users do? What is the typical workflow?

5. Package Structure
Analyze important files and folders, including where relevant:
- DESCRIPTION
- NAMESPACE
- R/
- man/
- vignettes/
- tests/
- inst/
- data/
- README
- pkgdown configuration
- GitHub Actions

6. Exported Function Surface
Identify exported functions and organize them into function families. For each major function or family, explain:
- purpose
- likely user
- inputs
- outputs
- relationship to other functions
- evidence from documentation, examples, or tests

7. Internal Architecture
Identify important internal helpers, object structures, conventions, or workflows.

8. Main User Workflows
Describe the most important package workflows from installation to first useful result.

9. Data Inputs and Outputs
Describe expected data structures, external data dependencies, returned objects, files, or side effects.

10. Dependencies and External Systems
Analyze package dependencies and what they imply about the package’s behavior.

11. Documentation, Examples, and Vignettes
Explain what the README, vignettes, examples, and man pages teach about intended usage.

12. Testing, Validation, and Quality Signals
Summarize test coverage, CI checks, package checks, examples, and quality gaps visible from the repo.

13. Release, Versioning, and Maintenance Context
Analyze versioning, NEWS/changelog, package metadata, release patterns, and maintainer assumptions if visible.

14. Presentation-Relevant Story
Explain how this package could be presented to an audience. Include possible storylines, demos, and slide sections.

15. Risks, Gaps, and Open Questions
Separate content/documentation gaps, technical gaps, testing gaps, and maintainer questions.

16. Source Evidence
List important files consulted and what each file supported.

Important rules:
- Do not invent details.
- Distinguish visible facts from inferences.
- Cite repository files or snippets wherever possible.
- If something is uncertain, say so.
- Do not suggest implementation changes unless they are relevant as risks, open questions, or maintenance recommendations.
```
