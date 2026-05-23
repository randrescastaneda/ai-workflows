# Generic Repository Brief Prompt

Use this when the repository type is unclear, mixed, or not yet classified.

```text
Use the connected GitHub repository <owner/repo>.

I am not asking you to implement changes. I want a reusable repository briefing that I can save as a source in a ChatGPT Project.

Your job is to analyze the repository as source material for future reasoning, planning, documentation, presentations, onboarding, architecture discussions, and strategic thinking.

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
Explain what this repository is, what problem it solves, and why it exists.

3. Audience and Use Cases
Identify likely users, maintainers, downstream systems, and practical use cases.

4. Repository Type and Role
Classify the repository. For example: R package, API service, data pipeline, documentation site, Quarto book, deployment repo, research workflow, mixed repo, etc.

5. Conceptual Model
Explain the mental model of how the repository works in plain but technically accurate language.

6. Repository Map
List the major folders and important files. For each one, explain its role.

7. Main Workflows
Describe the main workflows supported by the repo, from user-facing workflows to developer/maintainer workflows.

8. Main Functions, Modules, Routes, Chapters, or Components
Identify the most important public-facing and internal components. Adapt this section to the repo type.

9. Data Inputs and Outputs
Describe the main inputs, transformations, outputs, and artifacts.

10. Dependencies and External Systems
Identify important package dependencies, external APIs, databases, gateways, credentials, services, VMs, cloud systems, or deployment assumptions.

11. Documentation and Examples
Summarize what README files, vignettes, examples, tests, book chapters, tutorials, and documentation reveal about intended usage.

12. Testing, Validation, and Quality Signals
Summarize tests, CI, checks, validation patterns, render checks, and visible quality gaps.

13. Deployment, Publication, or Runtime Context
If applicable, describe how the repo is run, hosted, deployed, published, rendered, exposed, scheduled, or integrated with other systems.

14. Presentation-Relevant Story
Explain how this repository could be presented to a technical or semi-technical audience. Include possible narrative angles, demo ideas, and slide sections.

15. Open Questions
List things that are unclear from the repo and should be confirmed with the maintainer.

16. Source Evidence
List the most important files consulted. For each file, briefly state what it supported.

Important rules:
- Do not invent details.
- Distinguish clearly between facts visible in the repo and inferences.
- Cite repository files or snippets wherever possible.
- If something is uncertain, say so.
- Do not suggest code changes unless they are directly relevant as open questions, risks, or maintenance recommendations.
```
