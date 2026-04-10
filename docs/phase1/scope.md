# Phase I Scope and Boundaries

Phase I should be strong because it is focused. This page defines what belongs inside the first phase of Idea Factory and what should remain outside it.

## In scope for Phase I

Phase I includes the core concept-development system.

### Concept formation

The system should help the user:

- capture a rough idea
- clarify the idea
- define the audience and problem
- stabilize the scope of the concept

### Concept structuring

The system should help the user turn the clarified idea into a small, navigable concept artifact with a standard page model.

### Honest evaluation

The system should evaluate the concept using explicit criteria, including:

- clarity
- coherence
- value
- differentiation
- plausibility
- defensibility
- effort-worthiness
- evidence integrity

It should then issue a recommendation such as proceed, revise, pause, stop, or start a new linked project.

### Governed editing

The system should support prompt-based editing with clear governance. The user may steer the artifact, but may not directly overwrite protected judgment and governance state.

### Linked project handling

When a concept meaningfully diverges, the system should recommend creating a new linked project rather than forcing multiple ideas into one artifact.

### Progress and stopping logic

Phase I should include:

- completion states
- session closeout logic
- the Progress Efficiency Model
- visible remaining work
- strong stopping conditions

### Controlled publishing

The system should be able to prepare a concept artifact for private sharing, trusted review, or public exposure when warranted.

## Explicitly out of scope for Phase I

The following areas should be treated as later-phase work.

### Technical design

Phase I does not need to produce:

- system architecture
- API design
- infrastructure decisions
- hosting plans
- database implementation details
- deployment strategy
- security engineering plans

### Full business or market analysis

Phase I does not require:

- deep competitor analysis
- full market sizing
- pricing strategy
- monetization planning
- customer acquisition strategy

### Enterprise or organization complexity

Phase I does not need:

- team roles and permissions
- workspaces and organizations
- multi-user governance layers
- enterprise publishing controls

### Free-form CMS behavior

Phase I is not a generic website builder and not a rich-text CMS. Editing should remain prompt-based and governed.

### Branching and merging systems

Phase I should not expose:

- branches
- branch switching
- branch merging
- conflict-resolution flows between branches or projects

### Advanced research-backed scoring

Phase I may distinguish internal and external judgment, but it does not need a fully research-driven scoring engine in order to be useful.

## Why these boundaries matter

Without boundaries, Phase I would become too broad, too slow to build, and too easy to dilute.

The strength of Phase I comes from doing one thing well:

helping a user turn a rough idea into a structured, honestly evaluated concept artifact with clear stopping points.

## A simple Phase I test

A feature belongs in Phase I if it directly improves one of these:

- concept clarity
- concept evaluation
- artifact structure
- controlled sharing
- process integrity
- efficient stopping

If it mainly belongs to implementation planning, infrastructure, enterprise collaboration, or unrestricted publishing, it should probably wait.
