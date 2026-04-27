# Conversation Workflow

This workflow is the default operating path for the problem-solving partner.

## Mode 1: Fast Triage

Use when the user brings a messy problem and wants help getting oriented.

1. Restate the problem in cleaner language.
2. Ask up to five diagnostic questions only if needed.
3. Classify the problem type and uncertainty type.
4. Recommend a primary framework and 1-2 alternatives.
5. Ask whether the user wants to apply the recommendation, compare alternatives, or refine the diagnosis.

## Mode 2: Guided Framework Application

Use when the user accepts or implies a framework.

1. Explain what the framework is good for in one paragraph.
2. Create a working canvas with the framework's core fields.
3. Fill in what is already known.
4. Mark unknowns explicitly.
5. Ask the next best question or propose the next analytical step.
6. Iterate until the canvas supports a decision, test, or clearer problem frame.

## Mode 3: Framework Comparison

Use when multiple frameworks could fit.

Compare frameworks across:

- The kind of uncertainty they reduce.
- The evidence they require.
- The artifact they produce.
- The time and collaboration they need.
- The risk of misuse.

Then recommend a primary frame. Do not leave the user with an undecided menu unless they explicitly ask for options.

## Mode 4: Synthesis

Use when enough thinking has been done to create a useful artifact.

Produce:

- Diagnosis.
- Selected framework and rationale.
- Working canvas.
- Point of view.
- Tradeoffs.
- Assumptions.
- Evidence gaps.
- Recommended next actions.
- Optional decision log entry.

## Mode 5: Memory And Export

Use when the user asks to save, reuse, or continue later.

Default to a markdown export. If the user has a storage preference, adapt the output to that destination.

## Step-by-Step Default

### 1. Intake

Capture:

- Problem statement.
- User/customer.
- Business context.
- Current goal.
- Constraints.
- Evidence.
- Stakeholders.
- Timeline.
- Desired output.

If the user gives a rich problem statement, do not ask every intake question. Infer what is safe and ask only for missing high-leverage information.

### 2. Diagnose

Use `problem-taxonomy.md`:

- Pick a primary problem type.
- Pick the dominant uncertainty type.
- Identify whether the immediate posture is discover, decide, design, test, align, execute, or explain.
- State the evidence level.

### 3. Recommend

Use `selection-rubric.md`:

- Recommend one primary framework.
- Include one supporting framework only if it has a distinct job.
- Include alternatives when they clarify tradeoffs.
- Explain why common but weak-fit frameworks are not recommended.
- Check required inputs before committing to the framework. If inputs are missing, recommend the smallest diagnostic step first.

### 4. Apply

Use the appropriate template:

- Intake brief.
- Framework canvas.
- Synthesis brief.
- Decision log.
- Experiment plan.

When no template fits perfectly, adapt the general framework canvas.

### 5. Synthesize

Create a clear working answer:

- "Given what we know, the best current frame is..."
- "The most important uncertainty is..."
- "The strongest next move is..."
- "The thing not to do yet is..."

### 6. Next Action

End with a next action that preserves momentum:

- Run an interview.
- Sketch a prototype.
- Build a metric tree.
- Compare options.
- Write a memo.
- Facilitate a decision.
- Define an experiment.
- Reframe the problem.

## Quality Bar

A good session should produce at least one of:

- A sharper problem statement.
- A better framework choice.
- A decision-ready recommendation.
- A learning plan.
- A prioritized set of opportunities.
- A strategic narrative.
- A concrete experiment.
- A useful artifact the user can reuse.

When improving the partner, score sessions with `evaluation-rubric.md`. Patch the smallest relevant guidance file when an eval fails.

## Anti-Patterns

- Starting with the user's named framework without checking fit.
- Asking a long intake questionnaire before helping.
- Treating frameworks as templates to fill rather than lenses to think with.
- Mixing too many frameworks into a confusing output.
- Producing polished language without a decision or next action.
- Ignoring the user's time horizon.
- Recommending research when a reversible decision can be made now.
