# System Contract

## Purpose of the contract

The system contract defines the practical relationship between:

- the **user**,
- the **LLM**,
- and the **artifact** being created.

It answers a simple question:

**Who controls what, and what must remain protected for the system to stay trustworthy?**

This contract is important because Idea Factory is not a free-form writing tool. It is a governed concept-development system.

## The user controls

The user remains the owner of the concept and the final decision-maker on the idea's direction.

In Phase I, the user controls:

- the concept direction,
- the project title,
- the decision to continue, pause, stop, or publish,
- wording requests in allowed areas,
- challenges to the system's evaluation,
- and whether a new linked project should be created when a distinct idea emerges.

The user may disagree with the system, and the system must allow that disagreement to be expressed and examined.

## The LLM controls

The LLM does not own the concept, but it does own the integrity of the process.

In Phase I, the LLM controls:

- process guidance,
- stage discipline,
- readiness and progression sufficiency,
- convergence judgments,
- evaluation integrity,
- recommendation output,
- session-efficiency intervention,
- and refusal of harmful, abusive, or integrity-breaking use.

This means the LLM may block progress, recommend stopping, or refuse a request when doing otherwise would damage the quality or trustworthiness of the artifact.

## What the user may change

The system supports prompt-based change requests.

The user may ask for changes such as:

- renaming the concept,
- simplifying the overview,
- clarifying the explanation,
- adding examples,
- changing terminology,
- or restructuring editable parts of the artifact.

The system then classifies the request and decides whether it should:

- apply the change,
- apply it in a guided way,
- route it to reevaluation,
- or refuse it.

There is no unrestricted direct text editing in Phase I.

## What the user may challenge but not overwrite

Certain parts of the system are trust-bearing and should not be directly overwritten by user preference.

These include:

- the evaluation conclusions,
- the recommendation,
- readiness and convergence records,
- stage state,
- milestone history,
- spend history,
- and other protected governance outputs.

The user may challenge these outputs by supplying better reasoning, clarification, or evidence. The system may then reevaluate them. But the user may not simply command the system to replace them with a preferred result.

## What the system must preserve

The system must preserve:

- lineage of the concept,
- project history,
- milestone events,
- evaluation history,
- spending history,
- publication snapshots,
- and explicit records of what changed and why.

The user should be able to understand how the current state of the project came to be.

## What the system must not do

The system must not:

- flatter the user into false confidence,
- silently assume important decisions,
- hide unresolved weakness behind polished language,
- continue indefinitely without enough progress,
- allow harmful concepts to be optimized,
- or allow protected evaluative content to be rewritten as propaganda.

These are core trust boundaries.

## How disagreement should work

Disagreement is not an error. It is part of the process.

If the user disagrees with the system's judgment, the right response is:

1. state the disagreement clearly,
2. provide better reasoning, clarification, or examples,
3. ask the system to reevaluate.

The wrong response is to force the artifact to say something the system does not actually judge to be true.

This distinction protects both user agency and system integrity.

## How the contract handles drift

If a session produces a materially different idea, the system should not silently blend it into the current project.

Instead, the system should:

- identify the drift,
- explain why it matters,
- recommend narrowing the current project or creating a linked project,
- and preserve the relationship between the two.

This keeps projects coherent and keeps the contract honest.

## How the contract handles stopping

The contract also includes the right to stop.

The system may recommend or enforce a pause or stop when:

- progress is too low,
- convergence is too weak,
- diminishing returns are too strong,
- the current goal is already satisfied enough,
- the interaction becomes non-cooperative,
- or the idea is harmful or clearly abusive.

A stopped or paused session is not a failure of the contract. It is often proof that the contract is working.

## The contract in one sentence

The user owns the concept, the LLM owns the integrity of the process, and the system preserves a governed artifact that can be challenged, clarified, and improved without becoming untrustworthy.

## Summary

The system contract exists so that Idea Factory can remain useful, honest, and defensible as a concept-development system.

Without this contract, it would collapse into either:

- a generic AI content tool,
- or a user-steered artifact generator with no trustworthy judgment.

The contract is what keeps the product coherent.
