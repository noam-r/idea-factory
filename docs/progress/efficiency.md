# Progress Efficiency Model

Idea Factory should not continue a session simply because more conversation is possible. It should continue only when continued interaction is still a good use of the user's attention and the platform's resources.

The **Progress Efficiency Model** measures whether a session is producing enough meaningful conceptual progress, relative to time, interaction count, and cost, to justify continued work.

## What this model prevents

The model exists to prevent:

- endless sessions
- token burn without conceptual progress
- repeated low-value clarification loops
- polishing beyond the point of useful return
- drift without explicit intervention

## The core question

The system should not ask:

- can we continue?

It should ask:

- is continuing still the highest-value use of this session?

## Main signals

### Progress velocity

How quickly is the session converting interaction into meaningful progress?

Meaningful progress includes events such as:

- ambiguity reduced
- boundary clarified
- structure approved
- evaluation completed
- recommendation clarified
- first artifact draft created

### Convergence

Is the session still working on one coherent idea?

A session can be active but inefficient if it is drifting across multiple unresolved directions.

### Completion state

Has the current goal already been satisfied enough?

If the answer is yes, the system should actively discourage unnecessary continuation.

### Interaction pressure

How many turns have occurred in the current stage or session without enough return?

Interaction count should trigger review, not decide continuation on its own.

### Budget pressure

Is spend rising without proportionate value?

Budget should influence pacing and intervention, not conceptual truth.

## Progress events

The model should treat these as meaningful events:

### Clarity events

- problem clarified
- audience clarified
- mechanism clarified
- scope narrowed

### Decision events

- framing chosen
- structure approved
- recommendation accepted or challenged
- project goal clarified

### Governance events

- drift recognized
- linked project recommended
- pause or stop accepted

### Artifact events

- first structure defined
- evaluation completed
- first concept draft produced
- publication decision made

## Diminishing returns detection

The model should detect when new interaction is no longer producing proportionate value.

Examples:

- the same ambiguity is being rephrased without resolution
- wording is being refined without conceptual improvement
- the session is still converging, but the gain from additional turns is small

This is important because a session can be coherent and still be low-value to continue.

## Session states

The user-facing output should be plain language, not formulas.

Recommended session progress states:

- Making strong progress
- Making steady progress
- Progress is slowing
- Session is stalled
- Session should stop or pause

Each should have a short explanation.

## Escalation pattern

When the model detects falling efficiency, the system should intervene in stages.

### Level 1: redirect

Examples:

- narrow the question
- ask for one concrete example
- identify the single main blocker

### Level 2: force a decision

Examples:

- continue with a narrower definition
- pause
- start a new linked project
- stop

### Level 3: session closeout

The system ends the session because progress is too low relative to effort and cost.

## Stage-sensitive expectations

### Capture

Should usually be short. If too many turns happen here, the input is likely too weak.

### Clarify

Can take longer, but should produce visible narrowing.

### Structure

Should stabilize into a small concept architecture without excessive looping.

### Evaluate

Should lead to a recommendation, not endless analysis.

### Compile

Should produce a draft, not infinite polishing.

### Publish

Should move quickly to a yes, no, or not yet judgment.

## Relationship to examples

Examples are a recovery tool.

When explanation quality is poor but cooperation seems sincere, the system should often ask for:

- an example
- a counterexample
- something similar
- a concrete scenario

This often restores useful progress without prolonging the session unnecessarily.

## Why this model matters

Without the Progress Efficiency Model, the system risks becoming:

- exhausting
- expensive
- over-talkative
- unclear about when to stop

With it, the system can say plainly:

- progress is slowing
- this session is stalled
- the current goal is already satisfied enough
- further work now would have diminishing returns
