# Editability Model

Idea Factory Phase I is **not** a free-form CMS. The user does not directly edit raw page text. Instead, the user steers the artifact through prompt-based requests, and the system decides whether the request should be applied, guided, challenged, or refused.

## Why this model exists

This model protects four things:

- evaluation integrity
- process traceability
- artifact clarity
- lower UI and security complexity

A user should be able to shape the concept, but should not be able to silently rewrite protected judgment or governance state.

## Editing method

All changes happen through **prompt-based editing**.

Examples:

- “Shorten the overview.”
- “Use the term ‘concept site’ everywhere.”
- “Add an example for policy teams.”
- “I disagree with the evaluation because you missed X.”

The system then classifies the request and responds with one of four outcomes:

- applied
- partially applied
- routed to reevaluation
- refused

Every change request should produce an explicit change report.

## Editability classes

### Prompt-editable

The user can request direct wording or framing changes.

Typical examples:

- project title
- overview wording
- core idea wording
- examples
- glossary wording

### Guided prompt-editable

The user can request edits, but the system preserves the role and structure of the content.

Typical examples:

- problem framing
- how it works
- who it’s for
- open questions
- assumptions
- optional supporting pages

### Challenge-only

The user cannot directly rewrite the content, but may challenge it and trigger reevaluation.

Typical examples:

- evaluation conclusions
- recommendation
- value assessment
- differentiation assessment
- defensibility assessment

### Protected / system-only

The user may inspect these, but may not directly alter them.

Typical examples:

- readiness state
- convergence state
- stage state
- milestone history
- spend history
- trace history
- integrity classifications

## Page-level policy in Phase I

### Overview

Prompt-editable.

### Problem

Guided prompt-editable.

### Core Idea

Prompt-editable.

### How It Works

Guided prompt-editable.

### Who It’s For

Guided prompt-editable.

### Evaluation

Challenge-only. The user may respond to the system’s judgment, but cannot simply overwrite it.

### Open Questions

Guided prompt-editable. The user may help refine, add, or resolve questions, but the system may resist removing a truly blocking question without explanation.

## Why free-form editing is excluded in Phase I

Free-form editing would weaken the product in three ways:

1. it would make the artifact easier to manipulate
2. it would blur which parts are trustworthy
3. it would turn Idea Factory into a generic editor instead of a governed concept system

Prompt-based editing keeps the workflow simpler and the artifact more trustworthy.

## User authority vs system authority

The user owns:

- concept direction
- strategic decisions
- naming and framing requests in allowed areas
- whether to continue, pause, or publish
- challenges to the system’s evaluation

The system owns:

- protected evaluation state
- recommendation integrity
- readiness and convergence state
- process history
- refusal of integrity-breaking override requests

## Change reports

Every meaningful edit should tell the user:

- what changed
- what did not change
- what was refused
- whether reevaluation happened
- what the next step is

This keeps editing legible and maintains trust.
