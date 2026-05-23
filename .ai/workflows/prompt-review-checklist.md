# Prompt Review Checklist

Use this checklist before committing or reusing a prompt template.

## Purpose and scope

- Is the intended use clear?
- Is the target artifact clear?
- Does the prompt specify what not to do?
- Does it distinguish analysis, implementation, writing, review, and verification?

## Evidence and uncertainty

- Does the prompt require source evidence where appropriate?
- Does it tell the model not to invent details?
- Does it ask the model to separate visible facts from inferences?
- Does it require uncertainty to be flagged clearly?

## Reusability

- Can the prompt be reused outside the original chat?
- Are placeholders clear?
- Is it free of one-off context that belongs elsewhere?
- Is the output format durable enough to save as a Project source?

## Safety and privacy

- Does the prompt avoid requesting secrets, tokens, private URLs, or personal data?
- Does it warn against exposing sensitive information?
- Does it avoid asking for high-stakes conclusions without verification?

## Maintenance

- Is the prompt specific enough for the repo/task type?
- Should this be a new variant rather than an overloaded generic prompt?
- Does the commit message explain why the prompt changed?
