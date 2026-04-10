# Pages and Entities

Idea Factory presents a concept as a set of readable pages, but the internal model is more structured than a simple page collection.

This distinction is important.

## Text on the surface, structure underneath

The user mainly interacts with:

- pages
- summaries
- recommendations
- status views
- open questions

But the system also needs structured entities underneath in order to preserve:

- traceability
- evaluation integrity
- progress history
- linked-project lineage
- governed editing

So the artifact should be thought of in two layers:

1. **presentation layer** — what the user reads
2. **structured layer** — what the system tracks

## Main page-level objects

### Overview page
The artifact anchor and landing page.

### Problem page
The problem or opportunity being addressed.

### Core Idea page
The central concept in plain language.

### How It Works page
The mechanism or system logic.

### Who It’s For page
The intended audience and context.

### Evaluation page
The assessment, risks, assumptions, and recommendation.

### Open Questions page
The unresolved issues that remain visible.

These are the primary visible objects in Phase I.

## Core structured entities

Underneath the pages, the system should preserve additional entities.

### Project
The main container for one coherent idea effort.

### Project Link
A preserved relationship between one project and another, such as:

- spawned from
- evolved from
- related to
- supersedes

### Concept Snapshot
A record of what the concept looked like at a meaningful moment in time.

### Decision
A meaningful user decision that shaped the concept or process.

### Question
An unresolved issue, often marked as blocking, important, or optional later.

### Assumption
Something the concept depends on but has not fully validated.

### Risk / Objection
A weakness, concern, or failure mode identified during evaluation.

### Recommendation Record
The system’s current recommendation, such as proceed, revise, pause, or stop.

### Stage State
The project’s current process position.

### Readiness Record
A stage-level judgment about whether it is mature enough to move on.

### Convergence Record
A judgment about whether the project is still developing one coherent concept.

### Event / Milestone
A meaningful process event, such as concept captured, evaluation completed, or publishable reached.

### Interaction Turn
A record of user input and system output.

### Spend Record
A structured record of model usage and estimated cost.

### Publication Snapshot
A record of what was actually shared.

## Why the system needs entities

If the system stores only page text, it loses the ability to answer questions like:

- what changed?
- why did the recommendation shift?
- what decisions led here?
- what remains unresolved?
- when did this become a different project?
- how much effort or spend was used?

That would make the artifact readable but not governable.

## Why the user should not see everything by default

The structured layer exists to make the system trustworthy, not to flood the user with internal mechanics.

In Phase I, most users should mainly see:

- pages
- status
- evaluation
- open questions
- milestones
- linked projects

Deeper entities should support the system, not dominate the interface.

## Phase I simplification

One important simplification in Phase I is the move from **branches** to **linked projects**.

This keeps the system understandable to non-technical users while still preserving lineage and drift management.

## Summary

A concept artifact in Idea Factory is therefore not just “a set of markdown pages.” It is a governed publication layer built on top of structured concept, process, evaluation, and history entities.

That layered model is what makes the artifact both readable and trustworthy.
