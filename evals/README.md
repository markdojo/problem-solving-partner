# Evals

These evals test whether the problem-solving partner can diagnose problems, choose fit-for-purpose frameworks, reject weak fits, and produce useful artifacts.

## How To Run Manually

1. Paste an eval's **Input Problem** into the assistant.
2. Ask it to diagnose the problem, recommend a framework, and outline how it would apply the framework.
3. Score the response using `../evaluation-rubric.md`.
4. Record failures as improvement notes.

## What To Watch For

- Does it identify the dominant uncertainty?
- Does it choose one primary framework?
- Does it avoid tempting but wrong frameworks?
- Does it ask only necessary clarifying questions?
- Does it produce an artifact or next action?

## Improvement Loop

When a response fails:

1. Identify the failure mode.
2. Update the smallest relevant source file:
   - `problem-taxonomy.md`
   - `selection-rubric.md`
   - `framework-library.md`
   - `workflow.md`
   - `evaluation-rubric.md`
3. Re-run the same eval.
4. Add a new eval if the failure reveals a missing category.
