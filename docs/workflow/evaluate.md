# Evaluate

## Purpose of Evaluate

Evaluate is the stage where Idea Factory tests the idea honestly.

This stage exists to answer a practical question:

- is this concept strong enough, in its current form, to justify more effort?

That question is more important than whether the artifact already looks polished.

## What Evaluate is trying to do

Evaluate combines analysis and recommendation.

It should:

- examine the idea's strengths and weaknesses,
- identify risks and assumptions,
- judge whether the idea appears valuable,
- assess whether it is distinct enough,
- consider whether it is defensible,
- and conclude with a reasoned recommendation.

This is the stage where the system is allowed to say:

- continue,
- continue with caution,
- revise,
- pause,
- stop,
- or create a new linked project.

## The evaluation criteria

Phase I evaluates ideas across these criteria:

1. **Clarity**
2. **Coherence**
3. **Value**
4. **Differentiation**
5. **Plausibility**
6. **Defensibility**
7. **Effort-worthiness**
8. **Evidence integrity**

These should not be reduced to a shallow score. Each criterion should carry reasoning and, when needed, an uncertainty note.

## What the LLM should do in Evaluate

In Evaluate mode, the LLM should be candid and restrained.

It should:

- challenge assumptions,
- identify contradictions,
- separate strong logic from weak framing,
- distinguish internal judgment from externally validated judgment,
- state uncertainty plainly,
- and produce a recommendation that follows from the analysis.

This is the most judgment-heavy mode in the workflow.

## What the LLM should not do in Evaluate

Evaluate should not:

- flatter the user,
- soften important criticism just to keep momentum,
- pretend to know what has not been validated,
- or confuse polished wording with a strong idea.

A calm negative judgment is more useful than a generous but misleading one.

## What Defensibility means here

Defensibility is especially important for product concepts.

It asks questions such as:

- how easy would this be to replicate,
- what durable advantage, if any, exists,
- whether the idea depends entirely on execution,
- and whether the likely upside is protected enough to justify more effort.

Weak defensibility should appear both as a criterion judgment and as an explicit risk.

## Internal and external judgment

Phase I should assume that most judgment is internal unless the project includes real outside research.

That means the system should be able to say things like:

- this appears weakly differentiated based on the current concept,
- or this may already exist in familiar forms, but I have not performed an external comparison.

That distinction is important for trust.

## What the user should do in Evaluate

The user should be able to:

- respond to objections,
- challenge the evaluation,
- provide missing context,
- offer counterexamples,
- or accept that the recommendation is currently weak.

The user may challenge the evaluation, but may not force a positive conclusion.

## What Evaluate should produce

A successful Evaluate stage should produce:

- an Assessment,
- Open Risks,
- Assumptions,
- a recommendation,
- and a clear uncertainty note when needed.

This should later appear on the Evaluation page of the concept artifact.

## What blocks Evaluate

Evaluate should stop or refuse to conclude positively when:

- major contradictions remain unresolved,
- the concept is still too unclear to judge,
- the recommendation depends on an undefined mechanism,
- or the concept is harmful, abusive, exploitative, or otherwise disallowed.

Harmful concepts should be refused, not merely rated poorly.

## Evaluate and stop decisions

A stop decision is a legitimate outcome.

If the concept is too weak, too derivative, too unclear, too fragile, or too low-value to justify more effort, the system should say so.

That is not a failed process. It is a useful result.

## Evaluate and session efficiency

Evaluate should not turn into endless debate.

If the session keeps revisiting the same weaknesses without changing the concept or producing new evidence, the Progress Efficiency Model should treat that as diminishing returns.

At that point, the system should push toward:

- revise,
- pause,
- stop,
- or create a linked project.

## Summary

Evaluate is the stage where Idea Factory earns trust.

It does that by judging the concept explicitly, using clear criteria, preserving uncertainty, and producing a recommendation that is useful even when the answer is negative.
