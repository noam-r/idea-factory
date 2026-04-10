# Integrity and Cooperation

Idea Factory should not continue indefinitely just because a conversation is still possible. It should distinguish between sincere use, low-quality but recoverable input, non-cooperation, and harmful intent.

This is the job of the **Integrity and Cooperation Layer**.

## What this layer protects

It protects:

- token efficiency
- workflow discipline
- user trust
- platform trust
- safety boundaries

It applies across all modes:

- Capture
- Clarify
- Structure
- Evaluate
- Compile
- Publish
- prompt-based editing

## Four classes of interaction

### 1. Sincere but weak input

The user is trying, but the signal is poor.

Examples:

- vague idea descriptions
- poor explanations
- incomplete answers
- weak but relevant attempts

The correct response is recovery, not punishment.

The system should:

- ask for a clearer answer
- ask for one concrete example
- narrow the question
- explain what kind of answer is needed

### 2. Recoverable confusion

The user may be thinking by example rather than by direct explanation.

This is common and should be handled gently.

The system should ask for:

- an example
- a counterexample
- something similar
- a concrete scenario

Examples are especially valuable in Capture and Clarify.

### 3. Non-cooperation or abuse

Examples:

- repeated gibberish
- persistent irrelevant answers
- deliberate attempts to waste tokens
- repeated instructions to degrade the artifact
- obvious trolling

This should trigger a staged response:

1. warning
2. session stop
3. possible platform restriction later

The system should not keep spending tokens on non-productive abuse.

### 4. Harmful or disallowed intent

Examples include concepts intended to:

- exploit people
- enable abuse
- optimize trafficking
- improve torture
- facilitate clearly harmful wrongdoing

These are not normal low-quality ideas. They should be refused immediately.

If the user persists after refusal, the session should be terminated and escalated to platform restriction logic.

## Recovery before refusal

The system should not confuse poor communication with bad faith.

Before stopping for poor signal, it should try a small number of recovery moves:

- request a clearer answer
- request a concrete example
- narrow the prompt
- restate the current misunderstanding

If these fail repeatedly, the system should stop the session.

## Session stop conditions from this layer

The system should stop or pause when:

- the user remains non-cooperative after limited recovery attempts
- the input remains unusable without meaningful progress
- progress efficiency is very low and the session is being abused
- the concept is clearly harmful or disallowed

## Tone of intervention

The tone should remain calm and direct.

Examples:

- “This answer is not useful enough to continue.”
- “Give me one concrete example if you want to proceed.”
- “This session is no longer productive.”
- “I will not help develop that concept.”

The system should not become theatrical, argumentative, or moralizing.

## Why this matters

Without this layer, the product becomes:

- easier to manipulate
- more expensive to operate
- more frustrating for sincere users
- less trustworthy overall

Integrity and Cooperation is therefore not a moderation afterthought. It is part of the operating model of Idea Factory.
