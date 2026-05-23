# Quarto Book Repository Brief Prompt

Use this for repositories containing a Quarto book.

```text
Use the connected GitHub repository <owner/repo>.

I am not asking you to implement changes. I want a reusable repository briefing that I can save as a source in a ChatGPT Project.

This repository contains a Quarto book. Analyze it as a content, documentation, research, and publishing project — not primarily as a software package.

Your job is to produce a structured repo brief that will help with future reasoning, planning, editing, presentation-building, documentation strategy, publication workflows, and content development.

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
Explain what this Quarto book is, what it appears to be trying to accomplish, and why the repository exists.

3. Intended Audience and Use Cases
Identify the likely readers or users of the book. Consider technical users, non-technical users, analysts, researchers, students, internal teams, external stakeholders, maintainers, and contributors.

4. Book Thesis and Conceptual Purpose
Infer the central purpose of the book. Distinguish visible facts, reasonable inferences, and unclear claims. If the book has no explicit thesis, say so and propose the implied thesis.

5. Book Structure and Reader Journey
Analyze `_quarto.yml`, `index.qmd`, chapter `.qmd` files, appendix files, references, bibliography files, and chapter order. Explain the chapter sequence, how the book develops, and whether the structure is linear, modular, reference-oriented, tutorial-oriented, or mixed.

6. Chapter Map
For each chapter, include file name, apparent title, main purpose, key topics, likely reader need addressed, dependencies on earlier chapters, and open questions or possible weaknesses.

7. Content Architecture
Explain how the content is organized conceptually. Look for repeated concepts, conceptual progression, instructional patterns, examples, warnings, exercises, external tools, and the balance between practical and conceptual material.

8. Quarto Configuration and Build System
Analyze `_quarto.yml`, `_brand.yml`, custom CSS, `_extensions/`, profiles, freeze settings, bibliography settings, output formats, project type, and preview/render settings. Explain build assumptions and what contributors must know before rendering the book.

9. Code Execution and Reproducibility
If the book contains executable code chunks, analyze execution engines, `execute` settings, `freeze`, cache behavior, required packages, data dependencies, reproducibility, and whether code is illustrative or essential. If mostly prose, say so.

10. Data, Figures, Tables, and Assets
Identify important images, diagrams, tables, datasets, screenshots, custom stylesheets, scripts, generated outputs, and static assets. Explain their role.

11. Citations, Bibliography, and Source Strategy
Analyze `.bib` files, citation syntax, references chapters, external links, footnotes, and source notes. Explain whether citations are central or occasional and where citation coverage may need review. Do not judge citation accuracy unless the repo provides enough evidence.

12. Editorial Status and Content Maturity
Assess maturity using TODOs, placeholders, incomplete chapters, inconsistent headings, missing cross-references, broken-looking links, rough notes, uneven chapter depth, duplicated material, comments, or draft markers. Classify as early draft, working draft, mature draft, near-publication, or unclear.

13. Publication and Deployment Context
Analyze how the book appears to be rendered, previewed, published, or deployed. Look for GitHub Actions, `docs/`, `_site/`, `gh-pages`, Netlify, Vercel, Posit Connect, README instructions, render scripts, and deployment files.

14. Contributor and Maintenance Model
Explain how someone should add/edit chapters, update references, add images/assets, preview/render, what files should not be edited casually, and what should be verified before publishing.

15. Presentation-Relevant Story
Explain how this Quarto book could be presented to an audience. Include possible presentation thesis, narrative angle, key chapters, demo ideas, screenshots/visuals, and what the audience should understand.

16. Strengths
Identify what the repo/book already does well: structure, clarity, technical organization, pedagogical flow, reproducibility, design, and usefulness to readers.

17. Risks, Gaps, and Open Questions
Separate content gaps, structural gaps, technical/rendering gaps, citation/source gaps, publication/deployment gaps, and maintainer questions.

18. Suggested Future Uses of This Brief
Explain how this repo brief can be reused inside a ChatGPT Project.

19. Source Evidence
List the most important files consulted and what each file supported.

Important rules:
- Do not invent details.
- Distinguish clearly between visible repo facts and your inferences.
- Cite repository files or snippets wherever possible.
- If something is uncertain, say so.
- Do not suggest implementation changes unless they are directly relevant as risks, open questions, or maintenance recommendations.
- Treat this as a reusable knowledge artifact, not a one-time answer.
```

## Optional add-on for technical guideline books

```text
Additional project-specific priorities:

This book appears to be a technical guideline or internal knowledge base. Pay special attention to:

- whether chapters are tutorial-oriented, reference-oriented, policy/process-oriented, or mixed
- whether the book helps new team members become productive
- whether chapter order supports onboarding
- whether setup chapters come before workflow chapters
- whether code, tools, and procedures are explained at the right level
- whether the book distinguishes required procedures from optional tips
- whether there are duplicated or overlapping instructions
- whether the book has enough cross-references between related chapters
- whether the book can support presentations, training sessions, and onboarding
- whether naming, heading structure, and chapter sequence are consistent
- whether there are clear entry points for different reader types
```
