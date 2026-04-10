# Capture

## Purpose of Capture

Capture is the first working stage of Idea Factory.

Its purpose is to take rough user input and turn it into a reliable **concept seed**.

At this point, the system should not pretend the idea is well defined. It should only try to understand enough to say:

- what the idea seems to be,
- what kind of concept it may be,
- what the main ambiguities are,
- and whether the input is meaningful enough to continue.

## What Capture is working with

Capture may begin with input such as:

- a rough paragraph,
- a few scattered notes,
- a pasted document fragment,
- a description of a frustration,
- a half-formed opportunity,
- or a loose statement of intent.

This material is often incomplete, vague, or uneven. That is normal.

The role of Capture is not to force early precision. It is to create the first stable hold on the idea.

## What the LLM should do in Capture

In Capture mode, the LLM should be restrained.

It should:

- summarize the current understanding plainly,
- identify the likely concept type,
- separate facts, hypotheses, suggestions, and unknowns,
- identify the biggest ambiguities,
- and decide whether the input is usable enough to continue.

The system should not start building pages, arguing for the idea, or making the concept look stronger than it is.

## What the LLM should not do in Capture

Capture should not:

- generate a polished artifact,
- over-interpret sparse input,
- begin deep evaluation,
- praise the idea,
- or hide confusion behind smooth language.

A weak opening should remain visibly weak until the user gives the system enough material to work with.

## Why examples matter in Capture

Some users are not good at abstract explanation but are much better at giving references or examples.

That makes examples an important Capture tool.

If the user's explanation is too thin, the system should often ask for:

- one concrete example,
- something similar,
- a use case,
- or a concrete situation where the idea would matter.

This helps the system recover signal without forcing the user into a rigid form.

## What the user should provide

The ideal opening input is not just a slogan.

A better starting input includes at least some sense of:

- what the idea is,
- who or what it relates to,
- what problem or opportunity it touches,
- and, when possible, a concrete example.

If the user provides too little, the system should say so clearly.

## What a good Capture output looks like

A good Capture result is modest but useful.

It should usually produce:

- a provisional project title or working label,
- a one-sentence concept seed,
- a likely concept category,
- a short ambiguity list,
- and an initial judgment about whether clarification can begin.

This is enough for the next stage.

## What makes Capture successful

Capture is successful when the system can honestly say:

- what the concept appears to be,
- what kind of thing it might be,
- and what must be clarified next.

It does not require certainty.

It only requires enough signal to begin disciplined clarification.

## What blocks Capture

Capture should stop or refuse to advance when:

- the input is too vague to summarize honestly,
- the user is only giving slogans,
- the answers remain unusably thin after recovery attempts,
- the session shows non-cooperation,
- or the concept is harmful or clearly disallowed.

The system should not keep spending tokens on unusable input.

## Capture and session efficiency

Capture is expected to be relatively short.

If too many interactions happen in Capture without producing a viable concept seed, that is usually a sign that:

- the user needs to provide a better description,
- examples are needed,
- or the session should stop for now.

This is one reason the Progress Efficiency Model matters even at the first stage.

## Capture and project lineage

Capture may occasionally reveal that the user's input already contains multiple ideas.

In that case, the system should not silently blend them together.

It should identify that the input contains more than one concept and guide the user toward either:

- narrowing the current project,
- or later creating a linked project.

## Summary

Capture is the stage where Idea Factory earns the right to continue.

It does that by turning rough input into a concept seed that is clear enough to begin real clarification, while still remaining honest about what is not yet known.
