# Progress and Completeness Visibility

Idea Factory should not overwhelm the user with metrics. It should show only the most relevant signals by default while keeping deeper process information available when needed.

The visibility model should make the process feel:

- clear
- finite
- disciplined
- explainable

## Core principle

The system should not rely on a single global percentage.

Instead, it should show:

- current stage
- stage status
- session progress
- current goal
- main blocker or recommendation
- remaining work
- the next step

This is more honest and more useful than a vague readiness number.

## Three layers of visibility

### Layer 1: primary status

Always visible.

This should answer:

- where am I?
- is this going well?
- what is blocking me?
- what should happen next?

Recommended default fields:

- **Current stage**
- **Stage status**
- **Session progress**
- **Current goal**
- **Main blocker** or **Main recommendation**
- **The next step is...**

### Layer 2: context panel

Changes with the current stage.

Examples:

#### In Capture / Clarify

Show:

- current understanding of the idea
- top ambiguities
- blocking unknowns

#### In Structure

Show:

- proposed sections/pages
- missing conceptual pieces
- assumptions emerging
- open questions

#### In Evaluate

Show:

- recommendation
- strongest strength
- strongest concern
- criteria summary
- unresolved risks

#### In Compile

Show:

- draft artifact status
- existing pages
- pages still needing work
- visible limitations

#### In Publish

Show:

- intended audience
- publishability
- known limitations
- visibility mode

### Layer 3: deep inspector / ledger

Available when the user wants more detail.

This can include:

- milestones
- recommendation history
- convergence history
- spend history
- linked projects
- edit history
- reasoning history

This supports trust, but should not be the default surface.

## Completion Map

The system should always show a scoped **Completion Map** for the current goal.

It should contain three classes of remaining work:

### Completed

What is already done.

### Required now

What blocks the current goal.

### Important next

What should happen soon, but does not block immediate completion.

### Optional later

What belongs in later sessions or later phases.

## Example

**Current goal:** Prepare for trusted sharing

**Completed**
- concept defined
- audience defined
- evaluation completed

**Required now**
- compile first concept draft

**Important next**
- add examples
- tighten terminology

**Optional later**
- technical direction
- deeper external validation

This is the kind of map that makes the process feel finite.

## Session state vs project state

These should be visible, but not confused.

### Session state

What is happening right now?

Examples:

- Making strong progress
- Progress is slowing
- Session is stalled
- Session should stop or pause

### Project state

What is the overall condition of the project?

Examples:

- In progress
- Complete enough for now
- Paused
- Stopped
- Publishable
- Published

A session can stall even while the project remains healthy overall. This distinction matters.

## What should replace a giant readiness percentage

Instead of showing something like “94% ready,” the system should say things like:

- Clarify is strong enough to move on
- Two required items remain before this project is complete enough for trusted sharing
- The current goal has already been met well enough for now

This is much easier to trust.

## Portfolio-level visibility

When the user has multiple projects, the system should surface a compact portfolio view.

Suggested fields:

- project title
- current goal
- current stage
- recommendation
- priority label
- strongest concern
- project state

This gives the user a useful portfolio view without turning the product into a metric dashboard.

## Why this model matters

Without a good visibility model, the user may feel:

- lost
- over-measured
- unclear about what remains
- unsure whether the session is still helping

With a good visibility model, the system can stay disciplined while still feeling humane and understandable.
