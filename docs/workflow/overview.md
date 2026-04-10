# Workflow Overview

## Purpose of the workflow

The workflow is the operating backbone of Idea Factory.

Its job is to move a project from rough thought to a clearer and more governed state without allowing the process to collapse into:

- endless exploration,
- premature artifact production,
- weak evaluation,
- or uncontrolled drift.

The workflow is stage-based on purpose. Each stage exists to do a specific kind of work, and each stage should only continue while it is still producing useful progress.

## The six stages

Phase I uses six core stages:

1. **Capture**
2. **Clarify**
3. **Structure**
4. **Evaluate**
5. **Compile**
6. **Publish**

These are not merely labels for UI organization. They describe different kinds of conceptual work and different operating modes for the LLM.

## Why the stages are ordered this way

The order matters.

Idea Factory is designed to resist a common failure pattern in AI-assisted work:

1. the user starts with an ambiguous idea,
2. the system generates polished text too early,
3. the idea looks stronger than it is,
4. the user keeps going because progress feels visible,
5. and weak thinking gets preserved inside a good-looking artifact.

The stage order is meant to interrupt that pattern.

In Idea Factory, the system should try to:

1. understand the idea,
2. make the idea clearer,
3. organize the idea,
4. judge the idea,
5. and only then compile or expose the artifact.

## What each stage is trying to produce

### Capture

Capture turns rough user input into a reliable first concept seed.

The system tries to understand what the user is actually trying to describe and what is still too vague to trust.

### Clarify

Clarify gives the idea a stable center.

The system works to define:

- what the concept is,
- who it is for,
- what problem it addresses,
- how it works at a concept level,
- and what is outside its scope.

### Structure

Structure turns a clarified idea into a navigable concept model.

This is where the future concept site begins to appear, but still as a structured concept rather than polished publication.

### Evaluate

Evaluate tests whether the idea is coherent, valuable, differentiated, plausible, defensible, and worth more effort.

This stage includes the recommendation layer.

### Compile

Compile turns the concept into a readable artifact without hiding unresolved weakness.

The goal is clarity, not cosmetic uplift.

### Publish

Publish determines whether the artifact is fit for a chosen audience and, if so, records and preserves what was exposed.

## What changes from stage to stage

The LLM keeps the same mentor character throughout the workflow, but its operating mode changes.

For example:

- in **Capture**, it should interpret cautiously,
- in **Clarify**, it should ask focused questions,
- in **Structure**, it should organize,
- in **Evaluate**, it should judge honestly,
- in **Compile**, it should write with discipline,
- and in **Publish**, it should be conservative about exposure.

This is important because the user should feel that different kinds of work are happening at different points in the process.

## What the workflow does not allow

The workflow is designed to reject several patterns.

It should not allow:

- direct jumps from a vague idea to a polished site,
- endless clarification with no convergence,
- evaluation-free publishing,
- silent concept mutation,
- or forced positive conclusions.

The workflow exists to constrain those failures.

## What determines movement between stages

A project should not move forward only because the user wants motion.

Movement depends on whether the current stage has done enough useful work.

The system uses several signals to judge that:

- stage-specific sufficiency,
- convergence,
- the current project goal,
- completion state,
- and the Progress Efficiency Model.

This means the LLM may say:

- the stage is not ready to move on,
- the concept needs more clarification,
- the current project is already complete enough for now,
- or a different project should be created from an emerging idea.

## What valid outcomes look like

The workflow is not built to force every project toward publication.

A healthy project may validly end in:

- a clearer concept,
- a structured artifact,
- a recommendation to continue,
- a recommendation to revise,
- a pause,
- a stop,
- or a new linked project.

These are all legitimate outcomes.

## Why this workflow matters

Without a defined workflow, the system would become either:

- a free-form chat that never converges,
- or a content generator that produces artifacts without earning them.

The workflow is what keeps Idea Factory disciplined.

It provides:

- ordered conceptual progress,
- visible stopping points,
- evaluation before publication,
- and a more trustworthy relationship between the user, the LLM, and the artifact.

## Summary

The Idea Factory workflow is a stage-based process that moves a project from rough input to clearer understanding, evaluation, structure, and controlled publication.

Its purpose is not to maximize activity. Its purpose is to produce honest conceptual progress with visible stopping conditions and a governed artifact.
