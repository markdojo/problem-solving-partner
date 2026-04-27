# Framework Selection Rubric

Use this rubric after diagnosing the problem. Recommend one primary framework, one supporting framework if useful, and one alternative only when it helps the user understand the tradeoff.

## Selection Sequence

1. **Name the job**: discovery, decision, design, test, align, execute, or explain.
2. **Name the uncertainty**: customer, value, usability, viability, feasibility, growth, market, alignment, or system.
3. **Check the output needed**: brief, canvas, roadmap, experiment, metric tree, narrative, or decision.
4. **Check required inputs**: do not choose a framework that needs evidence, data, or stakeholders the user cannot access.
5. **Choose the simplest strong fit**: do not combine frameworks unless each one has a distinct role.
6. **Reject weak fits**: explain what you are not using and why if it is an obvious candidate.

## Evidence And Input Checks

Before recommending a framework, check whether its prerequisites are available:

- **Customer frameworks** need customer stories, interviews, observed behavior, or explicit assumptions to test.
- **Growth frameworks** need a defined value event, lifecycle stage definitions, cohorts, or a plausible loop mechanism.
- **Strategy frameworks** need a strategic challenge, constraints, options, and willingness to make tradeoffs.
- **Positioning frameworks** need competitive alternatives, best-fit customer, unique attributes, and proof of value.
- **Systems frameworks** need actors, boundaries, relationships, recurring behavior, and suspected feedback loops.
- **Decision frameworks** need comparable options, criteria, reversibility, and a decision owner.

If the required inputs are missing, recommend a lighter diagnostic step first.

## Framework Matching Rules

### If The Problem Is Poorly Understood
- **Primary**: JTBD, Opportunity Solution Tree, Assumption Mapping.
- **Support with**: Research Plan or Customer Journey Map.
- **Avoid starting with**: RICE, OKRs, Growth Loops, roadmap planning.
- **Reason**: prioritization and execution frameworks create false confidence when the problem is not yet clear.

### If The User Is Asking "What Should We Build?"
- **Primary**: Opportunity Solution Tree.
- **Support with**: JTBD for customer demand, Assumption Mapping for risk, Design Sprint for fast validation.
- **Avoid**: roadmap scoring before opportunity quality is understood.

### If The User Is Asking "How Should This Product Grow?"
- **Primary**: Growth Loops or Growth Model.
- **Support with**: AARRR/AAARRR to locate bottlenecks, Retention Curve Analysis if retention is weak, North Star Framework for alignment.
- **Avoid**: generic growth hacks or channel lists without a mechanism.

### If The User Is Asking "Why Aren't Users Staying?"
- **Primary**: Retention Curve Analysis.
- **Support with**: Activation Framework, Engagement Loop, JTBD, HEART.
- **Avoid**: acquisition tactics until retention quality is understood.

### If The User Is Asking "Why Aren't Users Converting?"
- **Primary**: Activation Framework for first value, Monetization Ladder for paid conversion, or Journey Map for funnel friction.
- **Support with**: Cognitive Walkthrough, Value Proposition Canvas, Competitive Alternatives.
- **Avoid**: treating all conversion problems as copy problems.

### If The User Is Asking "How Do We Position This?"
- **Primary**: April Dunford Positioning.
- **Support with**: Competitive Alternatives, ICP Segmentation, Category Design, Geoffrey Moore statement.
- **Avoid**: tagline generation before the market frame is clear.

### If The User Is Asking "What Is Our Strategy?"
- **Primary**: Strategy Kernel.
- **Support with**: Playing To Win, Product Strategy Stack, Wardley Mapping, North Star Framework.
- **Avoid**: OKRs until the diagnosis and guiding policy are clear.

### If The User Is Asking "What Should We Prioritize?"
- **Primary**: RICE, Weighted Decision Matrix, or Cost Of Delay/WSJF depending on the nature of the options.
- **Support with**: One-Way/Two-Way Door, Assumption Mapping.
- **Avoid**: scoring when the objective is not explicit.

### If The User Is Asking For Ideas Before Evidence
- **Primary**: Research Plan, JTBD, or Problem Statement / How Might We depending on what is known.
- **Support with**: Personas/Segments only when grounded in behavior, Opportunity Solution Tree when an outcome exists.
- **Avoid**: SCAMPER, Crazy 8s, or feature brainstorming until the problem and customer evidence are clearer.

### If The User Is Asking About A Broken Service Experience
- **Primary**: Service Blueprint when backstage teams, policies, support, billing, or operations shape the experience.
- **Support with**: Customer Journey Map for the customer view, RACI for execution ownership.
- **Avoid**: Heuristic Evaluation as the primary framework when the UI is not the likely root cause.

### If The User Is Asking About Decision Gridlock
- **Primary**: DACI/RAPID for decision rights, Narrative Strategy Memo for complex argumentation.
- **Support with**: Premortem for risk, Decision Journal for later learning.
- **Avoid**: RACI as the primary decision model; RACI is for execution roles.

### If The User Is Asking About Pricing Or Packaging
- **Primary**: Pricing / Packaging / Value Metric or Monetization Ladder.
- **Support with**: Subscription Value Loop for subscription businesses, JTBD for willingness-to-pay context.
- **Avoid**: lifecycle messaging or growth experiments before value capture logic is diagnosed.

### If The User Is Asking About Mainstream Adoption After Early-Adopter Love
- **Primary**: Crossing The Chasm / Geoffrey Moore Positioning.
- **Support with**: ICP Segmentation, April Dunford Positioning, whole-product gap analysis.
- **Avoid**: Lean Canvas as primary if the product is already validated with early adopters.

### If The User Is Asking "Why Does This Keep Happening?"
- **Primary**: Systems Map or Causal Loop Diagram.
- **Support with**: Theory Of Constraints, Iceberg Model, Leverage Points.
- **Avoid**: linear funnel analysis unless the behavior is actually linear.

### If The User Is Asking "How Do We Align Stakeholders?"
- **Primary**: Narrative Strategy Memo or DACI/RAPID.
- **Support with**: Strategy Kernel, Decision Journal, Premortem.
- **Avoid**: more brainstorming when the blockage is ownership or tradeoffs.

### If The User Is Asking "How Do We Reduce Risk Quickly?"
- **Primary**: Assumption Mapping and Riskiest Assumption Test.
- **Support with**: Experiment Loop, Research Plan, Prototype Test.
- **Avoid**: building a full MVP when a smaller test can answer the question.

## Framework Scorecard

Score candidate frameworks from 1-5 on these dimensions:

- **Problem fit**: addresses the diagnosed problem type.
- **Uncertainty fit**: targets the dominant unknown.
- **Output fit**: produces the artifact the user needs.
- **Evidence fit**: works with available evidence or clarifies missing evidence.
- **Time fit**: usable in the user's timeline.
- **Actionability**: leads to a decision, test, or next step.

Pick the highest-scoring framework unless there is a strategic reason to use a lower-scoring one.

## Combination Patterns

Use these proven combinations when a single framework is not enough:

### Discovery To Test
1. JTBD or Journey Map to understand the struggle.
2. Opportunity Solution Tree to structure opportunities and solutions.
3. Assumption Mapping to identify the riskiest belief.
4. Experiment Loop to test it.

### Growth Diagnosis To Mechanism
1. AARRR/AAARRR to locate lifecycle bottlenecks.
2. Growth Accounting or Retention Curve Analysis to quantify quality.
3. Growth Loops to design a compounding mechanism.
4. North Star Framework to align the team.

### Strategy To Execution
1. Strategy Kernel to define diagnosis and guiding policy.
2. Playing To Win or Wardley Mapping to sharpen choices.
3. OKRs to translate into measurable focus.
4. DACI/RAPID to clarify ownership.

### Positioning To Go-To-Market
1. Competitive Alternatives to understand the customer's real choice set.
2. April Dunford Positioning to define differentiated value.
3. ICP Segmentation to choose where to focus.
4. Lifecycle/Sales/PLG motion map to operationalize the message.

### System Problem To Intervention
1. Systems Map to identify actors and loops.
2. Theory Of Constraints to find the limiting factor.
3. Leverage Points to choose interventions.
4. Premortem to surface risks.

## Rejection Rules

Reject a framework when:

- It answers a different question than the user asked.
- It requires data the user cannot get in the available time.
- It requires stakeholder access or a decision owner the user does not have.
- It creates a polished artifact without changing the decision.
- It lets stakeholders avoid the hard tradeoff.
- It is a measurement framework being used as a strategy.
- It is an ideation framework being used before problem diagnosis.
- It is a prioritization framework being used before objectives are clear.
- It is a facilitation framework being used to avoid naming decision rights.
- It is a customer-understanding framework being used without customer evidence or explicit assumptions.

## Recommendation Template

```markdown
## Recommended Frame

Primary framework: [framework]

Why this fits:
- [problem signal]
- [uncertainty signal]
- [output fit]

Alternatives considered:
- [framework]: [why it is less direct or when to use it instead]
- [framework]: [why it is less direct or when to use it instead]

How we will apply it:
1. [step]
2. [step]
3. [step]

What this will produce:
- [artifact]
- [decision or next action]
```
