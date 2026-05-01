# AGENTS.md

## Project summary

Sheet Magic is a Chrome extension and related static documentation for turning Google Sheets data into Google Slides-based PDF or PPT outputs.

Primary goals:
- preserve accurate privacy and permission claims
- keep changes small, reviewable, and low risk
- maintain a simple user-facing docs surface

## Working style

Prefer the smallest safe change.
Do not make broad refactors unless explicitly requested.
Keep edits tightly scoped to the task.
When uncertain, choose the safer and more conservative option.

## Priority order

1. Correctness
2. Privacy and security
3. Minimal diff
4. Documentation accuracy
5. Readability

## What you may change

- README.md
- privacy-policy.html
- other small static documentation files added to this repository
- copy, formatting, and structure directly related to the requested task

## What you must not change without explicit approval

- OAuth scopes or requested permissions
- privacy promises about data collection, storage, or transmission
- analytics or tracking behavior
- external service integrations
- release or store listing claims that need legal or product review
- any future credentials, secrets, or environment configuration

## Commands

This repository currently appears to be documentation-only and does not define an automated build or test workflow.

For doc-only changes:
- verify the changed text carefully
- keep HTML valid
- preserve working links

If code is added later, document install, test, and build commands here before making larger changes.

## Task expectations

For changes in this repository:
- explain what changed in simple language
- keep diffs small
- do not over-claim product behavior
- if privacy, permissions, or data flow wording changes, keep the README and privacy-policy.html consistent

## Frontend expectations

- preserve the current lightweight static-page style
- keep pages readable on desktop and mobile
- avoid unnecessary visual redesign

## Privacy expectations

Because this project makes explicit privacy claims, treat wording as high-sensitivity product copy.
Do not introduce or imply data collection, server-side processing, analytics, or tracking unless explicitly requested and reflected consistently across the repo.

## When blocked

If the repository lacks enough context, or a requested change could affect privacy, permissions, or user trust:
- say exactly what is unclear
- propose the smallest safe next step
- do not guess
