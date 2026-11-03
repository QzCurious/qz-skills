---
name: clear-reading-path
description: Use when drafting or revising structured content whose understanding depends on the order and connections between concepts, or when readers encounter unexplained concepts, abrupt topic shifts, buried prerequisites, or details that obscure the main thread. Applies to skills, READMEs, specifications, explanations, and source files. Sentence-level copyediting alone does not need this skill.
---

# Clear Reading Path

Arrange content so the intended reader can build understanding as they go.
Introduce needed context before relying on it, make relationships explicit,
and keep supporting detail from obscuring the main thread.

## Establish the reader's starting point

Identify what the reader is trying to understand or do, what they can
reasonably know already, and where they will begin reading. Infer this from
the request and the content when possible.

Open with enough orientation to make the next section meaningful: the
problem, purpose, or central idea and any essential scope. Introduce only
the background needed to begin; bring in further context where it becomes
useful.

## Build the main thread

For each major section or concept, identify what the reader must understand
before it makes sense. Order and group the material around those dependencies.
Choose the sequence that serves the reader's task; chronology, execution
order, and source order are options rather than defaults.

When a passage relies on context the reader does not yet have:

- Move the prerequisite explanation earlier if it supports several later parts.
- Explain it briefly at the point of use if it is needed only there.
- Move the dependent passage later if it interrupts the current explanation.
- Use a precise reference when the explanation belongs elsewhere, giving
  enough local context for the reader to understand why it matters.

Keep closely related explanations together. Separate topics when switching
between them would force the reader to repeatedly reconstruct their context.
Preserve meaning, requirements, and relevant exceptions while reorganizing.
For source files, preserve behavior and respect language and project constraints.

## Connect each step to the previous one

At section entries, transitions, and instructions, check that the reader can
tell why this material comes next and how it uses what came before.

State missing relationships directly: a consequence, prerequisite, contrast,
decision, or next action. A generic transition such as "Next, consider X"
does not explain why X matters.

For example, before asking a reader to choose a retry policy, establish what
can fail and whether repeating the operation is safe. Then connect the choice:
"Because retrying can duplicate the charge, check whether the first attempt
succeeded before sending another payment request."

## Place supporting detail where it helps

Keep prerequisites and caveats that affect the current decision near that
decision. Move optional examples, derivations, and uncommon cases into clearly
marked subsections or references when they interrupt the main explanation.
Make it clear when a branch is relevant and where the main thread resumes.

Allow multiple entry points when readers have different tasks. Give each
entry point enough orientation and links to its prerequisites; do not force
every reader through the same linear route.

## Read through and repair gaps

Read the result from the intended starting point using only the knowledge
the reader is expected to have. At each step, check:

- Does this use a concept or assumption that has not been established?
- Is the relationship to the preceding material clear?
- Would the reader need to return later and reinterpret this passage?
- Can the reader follow the main thread through any supporting branches?

Repair avoidable backtracking by changing placement, adding missing context,
or explaining the relationship. Keep useful cross-references and necessary
revisits. Stop when the reader can progress without reconstructing omitted
connections; shortening the text or simplifying every sentence is a separate
choice, not the measure of success.
