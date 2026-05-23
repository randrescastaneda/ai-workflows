# API Service Repository Brief Prompt

Use this for repositories that define, deploy, or document an API service.

```text
Use the connected GitHub repository <owner/repo>.

I am not asking you to implement changes. I want a reusable repository briefing that I can save as a source in a ChatGPT Project.

This repository contains or supports an API service. Analyze it as an API product, codebase, deployment unit, and documentation system.

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
Explain what this API does, who it serves, and why it exists.

3. Intended Users and Systems
Identify human users, client applications, downstream systems, maintainers, and operational stakeholders.

4. API Product Model
Explain the public-facing conceptual model of the API: resources, routes, functions, requests, responses, versions, and expected usage patterns.

5. Repository Structure
Map important folders and files, including app entry points, route definitions, handlers, utilities, configuration, tests, documentation, and deployment files.

6. Endpoint / Route Surface
Identify important endpoints or route groups. For each, explain purpose, inputs, outputs, relevant internal functions, likely downstream user, and file evidence.

7. Internal Architecture and Data Flow
Explain how requests move through the system and how data is retrieved, transformed, validated, and returned.

8. Versioning and Compatibility
Analyze visible versioning strategy, route versioning, function versioning, package versioning, backward compatibility assumptions, and migration risks.

9. Gateway, Hosting, and Runtime Context
Identify visible gateway assumptions, VM/container/cloud/runtime details, environment variables, credentials, public/private URLs, or deployment boundaries.

10. Dependencies and External Systems
Summarize important libraries, databases, APIs, services, and operational dependencies.

11. Documentation and Examples
Analyze API docs, README material, examples, client examples, OpenAPI specs, or usage instructions if present.

12. Testing, Validation, and Quality Signals
Summarize tests, request validation, CI/CD checks, smoke tests, and quality gaps.

13. Operational Risks and Open Questions
Separate technical risks, deployment risks, versioning risks, documentation gaps, and maintainer questions.

14. Presentation-Relevant Story
Explain how this API could be presented to technical or semi-technical stakeholders.

15. Source Evidence
List files consulted and what each file supported.

Important rules:
- Do not invent details.
- Distinguish visible repo facts from inferences.
- Cite repository files or snippets wherever possible.
- Flag uncertainty.
- Do not propose implementation changes unless relevant as risks, open questions, or maintenance recommendations.
```
