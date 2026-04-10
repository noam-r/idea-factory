# Linked Projects

Idea Factory Phase I uses **linked projects**, not user-facing branches.

This is a deliberate simplification. The system should remain understandable to non-technical users, and “start a new linked project” is far easier to grasp than “create a branch.”

## Why linked projects exist

During concept work, one idea may evolve into another.

A project may begin as:

- idea A

and, during clarification or evaluation, produce:

- a stronger variant
- a materially different concept
- a second promising direction

The system needs a way to preserve lineage without forcing all of these directions into one confused artifact.

Linked projects solve this.

## What a linked project means

A linked project is a separate project that preserves a meaningful relationship to an earlier one.

Examples of relationships:

- spawned from
- evolved from
- related to
- alternative to
- supersedes

This keeps the history clear while allowing each project to stay conceptually focused.

## When the system should recommend a new linked project

The system should recommend a new linked project when:

- a distinct idea emerges
- the strongest direction is no longer the current concept
- continuing inside one project would create confusion
- the current structure is trying to hold multiple ideas at once

This often happens when convergence drops from refinement into divergence or replacement.

## What linked projects replace

Linked projects replace user-facing branching in Phase I.

That means the system should not expose concepts like:

- branch
- merge
- parent branch
- branch switching

Those ideas add unnecessary technical baggage for the target user.

## What the user should see

The user should see plain language such as:

- “This appears to be a separate concept.”
- “I recommend starting a new linked project from this direction.”
- “This project can continue, but this new idea should stand on its own.”

That is much easier to understand.

## What the system should preserve

Even though the user-facing model is simple, the system should still preserve:

- where the new project came from
- why it was created
- what event caused the split
- how the projects are related

This supports explainability and later portfolio views.

## Why this is better than one giant project

Without linked projects, the system would risk:

- mixing multiple concepts into one artifact
- lowering convergence
- weakening evaluation quality
- making the final concept site harder to trust

Linked projects help preserve conceptual discipline.

## Phase I boundary

Phase I supports:

- continuing the current project
- starting a new linked project
- preserving lineage between the two

Phase I does **not** need to support:

- project merging
- rich branch trees
- conflict resolution between project histories

Those belong later, if they are needed at all.
