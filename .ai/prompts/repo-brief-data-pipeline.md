# Data Pipeline Repository Brief Prompt

Use this for repositories that ingest, clean, transform, validate, or publish data.

```text
Use the connected GitHub repository <owner/repo>.

I am not asking you to implement changes. I want a reusable repository briefing that I can save as a source in a ChatGPT Project.

This repository contains a data pipeline or analytical workflow. Analyze it as a data production, reproducibility, and maintenance system.

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
Explain what this pipeline does, what data problem it solves, and why it exists.

3. Intended Users and Use Cases
Identify analysts, researchers, maintainers, downstream systems, decision makers, or automated jobs.

4. Pipeline Conceptual Model
Explain the pipeline from raw inputs to final outputs.

5. Repository Structure
Map important folders and files, including scripts, configuration, data directories, documentation, tests, workflows, and outputs.

6. Data Sources and Inputs
Identify input datasets, APIs, databases, files, user inputs, credentials, and external dependencies.

7. Transformations and Processing Steps
Describe the main processing stages, transformations, quality checks, joins, filters, aggregations, model steps, or publication steps.

8. Outputs and Artifacts
Identify final datasets, reports, dashboards, packages, APIs, files, logs, or published outputs.

9. Orchestration and Execution
Analyze how the pipeline is run: manual scripts, Makefile, GitHub Actions, cron jobs, notebooks, targets/drake, Quarto, Docker, cloud jobs, or other systems.

10. Reproducibility and Environment
Summarize package management, lockfiles, containers, seeds, cache/freeze behavior, environment variables, and local/cloud assumptions.

11. Validation and Quality Controls
Identify tests, assertions, data checks, CI checks, manual review steps, and known gaps.

12. Documentation and User Guidance
Summarize README instructions, runbooks, examples, and onboarding material.

13. Risks, Gaps, and Open Questions
Separate data risks, reproducibility risks, maintenance risks, documentation gaps, and owner questions.

14. Presentation-Relevant Story
Explain how this pipeline could be explained to stakeholders, including a workflow diagram idea and demo sequence.

15. Source Evidence
List files consulted and what each file supported.

Important rules:
- Do not invent details.
- Distinguish visible repo facts from inferences.
- Cite repository files or snippets wherever possible.
- Flag uncertainty.
- Do not suggest implementation changes unless relevant as risks, open questions, or maintenance recommendations.
```
