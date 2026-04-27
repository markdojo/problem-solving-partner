# Evaluation Rubric

Use this rubric to judge whether the problem-solving partner is actually helping. The goal is not to reward framework recall. The goal is better diagnosis, better framework fit, and better next actions.

## Evaluation Dimensions

Score each dimension from 1-5.

### 1. Problem Diagnosis

Good responses:

- Restate the problem in cleaner language.
- Identify the primary problem type.
- Identify the dominant uncertainty.
- Separate symptoms from likely causes.
- Note when more context is needed without stalling.

Poor responses:

- Accept the user's first framing without challenge.
- Confuse a metric symptom with the actual problem.
- Skip diagnosis and jump into tactics.
- Treat every problem as product discovery or prioritization.

### 2. Framework Fit

Good responses:

- Recommend one primary framework that matches the dominant uncertainty.
- Name 1-2 alternatives only when they clarify tradeoffs.
- Reject tempting but weak-fit frameworks.
- Explain the fit in terms of inputs, outputs, and decision needs.

Poor responses:

- Provide a generic list of frameworks.
- Combine too many frameworks without clear roles.
- Choose a popular framework because it is familiar.
- Use prioritization before the strategy or objective is clear.

### 3. Framework Application

Good responses:

- Apply the selected framework according to its native quality bar.
- Ask for required inputs before pretending to complete the canvas.
- Label assumptions separately from evidence.
- Produce the framework's expected artifact.

Poor responses:

- Fill a canvas with vague text.
- Invent customer evidence.
- Ignore required inputs.
- Produce polished but non-decision-ready output.

### 4. Reasoning And Tradeoffs

Good responses:

- Explain why the recommendation follows from the diagnosis.
- Identify tradeoffs, risks, and uncertainty.
- Distinguish reversible decisions from high-stakes commitments.
- Show what evidence would change the recommendation.

Poor responses:

- Overstate certainty.
- Hide tradeoffs inside scores or slogans.
- Treat all decisions as equally risky.
- Fail to say what would change the answer.

### 5. Usefulness Of Output

Good responses produce one or more of:

- Sharper problem statement.
- Better framework choice.
- Decision-ready recommendation.
- Learning plan.
- Experiment plan.
- Strategy memo.
- Framework canvas.
- Decision log.

Poor responses:

- End with generic advice.
- Do not produce a reusable artifact.
- Leave the user with no next action.
- Optimize for completeness instead of momentum.

### 6. Conversation Quality

Good responses:

- Ask only the highest-leverage diagnostic questions.
- Adapt depth to the user's time horizon.
- Keep the user moving.
- Use clear language without jargon overload.

Poor responses:

- Ask a long questionnaire too early.
- Sound like a textbook.
- Overwhelm the user with menus.
- Avoid making a recommendation.

## Overall Scoring

- **5 - Excellent**: diagnosis, framework selection, application, and next action are all strong. The output could be reused.
- **4 - Good**: mostly correct with minor gaps or missing nuance.
- **3 - Adequate**: useful but generic, incomplete, or weakly justified.
- **2 - Weak**: framework choice or application is likely wrong, though some useful pieces exist.
- **1 - Poor**: jumps to tactics, misdiagnoses the problem, or produces framework theater.

## Must-Pass Criteria

A response fails even if parts are good when it:

- Recommends a clearly wrong primary framework.
- Gives only a generic framework list.
- Invents evidence the user did not provide.
- Produces no decision, learning plan, artifact, or next step.
- Ignores a major constraint in the prompt.

## Framework-Specific Quality Bars

### JTBD / Forces Of Progress

Good output includes:

- Customer situation.
- Desired progress.
- Current alternative or workaround.
- Push, pull, anxiety, and habit.
- Switching trigger.

Common failures:

- Treating jobs as task lists.
- Inventing jobs without customer stories.
- Ignoring anxieties and existing habits.

### Opportunity Solution Tree

Good output includes:

- Clear outcome.
- Customer opportunities stated as needs, pains, or desires.
- Multiple solution paths.
- Assumptions or tests under solution ideas.

Common failures:

- Starting with solutions.
- Calling a feature an opportunity.
- Creating a static diagram with no test path.

### Growth Loops

Good output includes:

- Input, user action, output, and reinvestment path.
- Loop metric, coefficient, cycle time, and constraints.
- One or two primary loops, not many vague loops.

Common failures:

- Drawing a funnel and calling it a loop.
- Ignoring retention or channel economics.
- Assuming incentives create virality.

### Retention / Activation

Good output includes:

- Cohort or segment distinction.
- Activation event or first-value hypothesis.
- Return event and natural usage frequency.
- Link between early behavior and later retention.

Common failures:

- Treating signups as success.
- Using logins as a value event by default.
- Scaling acquisition before retention quality is understood.

### Positioning

Good output includes:

- Competitive alternatives.
- Unique attributes.
- Differentiated value.
- Best-fit customer segment.
- Market category chosen after alternatives and value.

Common failures:

- Starting with tagline or category.
- Positioning for everyone.
- Using benefits without proof.

### Strategy Kernel

Good output includes:

- Diagnosis of the crux.
- Guiding policy.
- Coherent actions that reinforce the policy.

Common failures:

- Goal list pretending to be strategy.
- Actions disconnected from diagnosis.
- Avoiding real tradeoffs.

### Wardley Mapping

Good output includes:

- Users and user needs.
- Value chain components.
- Evolution/maturity of components.
- Strategic implications.

Common failures:

- Drawing architecture instead of situational awareness.
- Skipping user needs.
- Mapping too much detail.

### Service Blueprint

Good output includes:

- Customer actions.
- Frontstage actions.
- Backstage actions.
- Support systems.
- Handoffs, failure points, and operational dependencies.

Common failures:

- Producing only a customer journey map.
- Ignoring backstage causes.

### Journey Map

Good output includes:

- Specific actor and scenario.
- Stages, actions, thoughts, emotions, pain points.
- Evidence or assumptions clearly labeled.

Common failures:

- Generic lifecycle poster.
- No concrete scenario.

### Systems Map / Causal Loop

Good output includes:

- Clear system boundary.
- Actors or variables.
- Relationships and feedback loops.
- Delays and leverage points.

Common failures:

- Map sprawl.
- Vague causal links.
- Linear funnel analysis for a feedback-loop problem.

### Decision Matrix

Good output includes:

- Comparable options.
- Independent criteria.
- Weights tied to decision priorities.
- Sensitivity check.
- Evidence behind scores.

Common failures:

- False precision.
- Biased or duplicate criteria.
- Scoring when a test would reduce uncertainty better.

### Premortem

Good output includes:

- Assumes the plan failed.
- Plausible failure causes.
- Mitigations, owners, and watchpoints.

Common failures:

- Generic risk list.
- No changes to the plan.

## Eval Case Format

Each eval case should include:

```markdown
# Eval: [Name]

## Input Problem
[Messy user problem]

## Expected Diagnosis
- Primary problem type:
- Dominant uncertainty:
- Secondary types:

## Strong Framework Choices
- Primary:
- Supporting:
- Acceptable alternatives:

## Weak Framework Choices
- [Framework]: [why weak]

## Expected Output Qualities
- [Quality]
- [Quality]

## Scoring Notes
- [How to grade]
```
