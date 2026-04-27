# Framework Library

This library is intentionally broad. Prefer a few well-fit frameworks over exhaustive application. The library is strongest on product strategy, growth, and prioritization, with growing coverage of design, technology feasibility, and execution.

## Framework Card Format

- **Use when**: the problem conditions where the framework is strong.
- **Avoid when**: common weak-fit cases.
- **Inputs**: what the framework needs to be used well.
- **Output**: the artifact the user should get.
- **Good looks like**: quality signals for strong application.
- **Common failures**: misuse patterns to avoid.

Older cards may only include use/avoid/output. When improving the library, upgrade cards to this fuller format.

## Definition Of Good

A good framework recommendation is not the most sophisticated framework. It is the framework that best matches:

- The user's decision or artifact need.
- The dominant uncertainty.
- The available evidence.
- The time horizon.
- The required inputs.
- The next action the user can actually take.

Good application produces a working artifact and makes assumptions visible. Bad application produces a polished canvas that does not change the decision.

## Research-Backed Quality Signals

Use these as shortcuts when judging whether a framework is being applied well:

- **JTBD**: grounded in customer switch stories, alternatives, push/pull/anxiety/habit, and desired progress.
- **Opportunity Solution Tree**: starts with an outcome, states opportunities as customer needs or pain points, and connects solutions to assumption tests.
- **Positioning**: starts with competitive alternatives, then unique attributes, differentiated value, best-fit customers, and category.
- **Strategy Kernel**: includes diagnosis, guiding policy, and coherent actions. Goals alone are not strategy.
- **North Star**: reflects delivered customer value and has controllable input metrics. It is not a substitute for strategy.
- **Growth Loops**: defines input, user action, output, reinvestment, loop metric, cycle time, and constraint.
- **Retention/Activation**: uses cohorts, segments, first-value behavior, return behavior, and natural usage frequency.
- **Service Blueprint**: includes customer actions, frontstage, backstage, support systems, handoffs, and failure points.
- **Journey Map**: has a specific actor, scenario, stages, actions, thoughts, emotions, pain points, and evidence labels.
- **Systems/Causal Loops**: names system boundary, variables, relationships, feedback loops, delays, and leverage points.
- **Decision Matrix**: uses comparable options, independent criteria, weighted priorities, evidence-backed scores, and sensitivity checks.
- **Premortem**: assumes failure happened, works backward to plausible causes, and assigns mitigations.
- **Card Sorting and Tree Testing**: card sorting is generative and uses open or closed sorts to surface user mental models. Tree testing is evaluative and uses task-based findability tests on a labeled hierarchy. Both report stable clusters and first-click paths, not single perfect structures.
- **Norman Action Cycle**: names the seven stages from goal to evaluation. Identifies whether the breakdown is in the gulf of execution, where the user cannot figure out what to do, or the gulf of evaluation, where the user cannot tell what happened.
- **Microinteractions**: every microinteraction has a trigger, rules, feedback, and loops or modes. Good microinteractions reuse what is already on screen, prevent error states, and are calibrated to whether the event is critical or background.
- **UI State Inventory**: every screen or component has at minimum empty, loading, partial, success, error, and offline states. Each state has a clear next action when one is possible. Skeleton states preferred over spinners for content that has predictable shape.
- **Atomic Design**: components nest hierarchically from atoms through molecules, organisms, templates, and pages. Modern teams treat the labels as flexible and extend with design tokens for visual properties.
- **Design Tokens**: tokens live in three layers, primitive (raw values), semantic (intent), and component (specific use). Theming is a swap of the semantic layer; components should not reference primitives directly.
- **POUR**: accessible content is perceivable, operable, understandable, and robust. Each principle maps to a different class of human limitation and assistive technology compatibility.
- **Persona Spectrum**: maps a permanent disability to related temporary and situational mismatches, expanding the addressable benefit of inclusive design solutions.
- **Design Critique**: separates observation from judgment, and feedback from solution. Frameworks like LIWI (I Like, I Wish, What If) and SBI (Situation, Behavior, Impact) keep critique specific, balanced, and actionable.
- **Architecture Decision Record**: captures one significant decision in context, decision, status, and consequences. Append-only, lightweight, stored next to the code.
- **C4 Model**: describes software architecture at four zoom levels, context, container, component, code. Each level has an audience and a clear scope.

## Common Wrong Turns

- Do not use RICE when the strategic objective is unclear.
- Do not use Growth Loops when retention and repeat value are unproven.
- Do not use brainstorming tools before customer evidence or problem framing.
- Do not use a journey map when backstage operations are the likely cause; use a service blueprint.
- Do not use RACI to make a decision; use DACI or RAPID for decision rights.
- Do not use a North Star metric as a replacement for strategy.
- Do not use a decision matrix when the options are not comparable or when a small experiment would reduce uncertainty faster.
- Do not use positioning as tagline writing; positioning precedes messaging.
- Do not use card sorting to evaluate an existing structure. Use tree testing.
- Do not use tree testing to discover a new structure. Use card sorting.
- Do not jump to high-fidelity design before resolving information architecture. Layout protects bad structure.
- Do not design only the success state. Empty, loading, error, and edge cases reveal whether the design works in real conditions.
- Do not let component tokens reference primitive tokens directly. Theming will break and a rebrand will touch every component.
- Do not equate accessibility with WCAG conformance alone. Conformance is a floor, not a ceiling, and inclusive design extends past disability into temporary and situational use.
- Do not use a personas exercise as a substitute for talking to people with the abilities you are designing for.
- Do not use design critique to redesign the work in the room. Critique surfaces issues; redesign happens after.
- Do not write an architecture decision record after the fact for a decision no one would revisit. Reserve them for decisions that matter and will be challenged or reused.
- Do not draw one architecture diagram for all audiences. Match zoom level to who is reading.

## Product Discovery And Customer Understanding

### Jobs To Be Done
- **Use when**: the team needs to understand the progress a customer is trying to make, switching behavior, alternatives, or demand drivers.
- **Avoid when**: the problem is purely operational or the user segment is already deeply understood.
- **Output**: job statement, forces of progress, desired outcomes, struggling moments, alternatives, and opportunity areas.

### Forces Of Progress
- **Use when**: a customer is deciding whether to switch from an old behavior to a new product.
- **Avoid when**: there is no meaningful behavior change.
- **Output**: push, pull, anxiety, habit, and interventions to increase switching.

### Opportunity Solution Tree
- **Use when**: the team has an outcome and needs to discover which customer opportunities and solutions to pursue.
- **Avoid when**: the outcome is not agreed upon or there is no customer evidence.
- **Output**: outcome, opportunities, solution ideas, and experiments.

### Continuous Discovery Habits
- **Use when**: the team needs an ongoing system for customer learning rather than a one-off research project.
- **Avoid when**: the problem requires a single strategic decision with no ongoing product team.
- **Output**: cadence, interview plan, assumption tests, opportunity map, and decision rules.

### Customer Journey Map
- **Use when**: the problem spans multiple steps in a user experience or service.
- **Avoid when**: the issue is a narrow feature tradeoff.
- **Output**: journey stages, user goals, emotions, pain points, channels, backstage dependencies, and opportunities.

### Service Blueprint
- **Use when**: the customer experience depends on internal operations, support, policy, logistics, or handoffs.
- **Avoid when**: the product is mostly self-serve software with few operational dependencies.
- **Output**: frontstage actions, backstage actions, systems, handoffs, failure points, and improvements.

### Empathy Map
- **Use when**: the team needs to align around what a user says, thinks, does, feels, hears, and sees.
- **Avoid when**: used as a substitute for actual research.
- **Output**: user understanding snapshot and research gaps.

### Persona / Segment Profile
- **Use when**: the team must reason about distinct audiences with different needs, constraints, or buying behavior.
- **Avoid when**: personas become fictional averages with no behavioral grounding.
- **Output**: segment description, context, needs, triggers, objections, and success criteria.

### Problem Statement / How Might We
- **Use when**: the team needs to turn messy observations into a solvable prompt.
- **Avoid when**: the team has not gathered enough context to know the real problem.
- **Output**: concise problem statement and HMW prompts.

### Assumption Mapping
- **Use when**: the team has many beliefs and needs to identify the riskiest unknowns.
- **Avoid when**: there is no intent to test assumptions.
- **Output**: assumptions mapped by importance and uncertainty, with test priorities.

### Riskiest Assumption Test
- **Use when**: a solution direction exists but confidence is low.
- **Avoid when**: the team is still deciding which customer problem matters.
- **Output**: riskiest assumption, test method, success threshold, and next decision.

### Kano Model
- **Use when**: prioritizing features by expected customer satisfaction, delight, and basic expectations.
- **Avoid when**: feature satisfaction data cannot be gathered or the product is highly novel.
- **Output**: must-be, performance, delighter, indifferent, and reverse features.

### HEART
- **Use when**: evaluating UX quality across happiness, engagement, adoption, retention, and task success.
- **Avoid when**: the question is business model strategy rather than experience quality.
- **Output**: UX metric tree and measurement plan.

## Design Process

### Double Diamond
- **Use when**: the team needs a complete design process from problem discovery to solution delivery.
- **Avoid when**: the issue is a narrow prioritization or metric decision.
- **Output**: discover, define, develop, deliver plan.

### Design Sprint
- **Use when**: a team needs to align, prototype, and test a risky idea quickly.
- **Avoid when**: there is no access to customers or stakeholders for a focused sprint.
- **Output**: validated prototype learning and next decision.

### Design Thinking
- **Use when**: the team needs a human-centered process for empathizing, defining, ideating, prototyping, and testing.
- **Avoid when**: used generically without clear research or decision points.
- **Output**: research synthesis, problem frame, concepts, prototype, and test results.

### SCAMPER
- **Use when**: generating variations on an existing product, feature, or process.
- **Avoid when**: the problem needs customer diagnosis before ideation.
- **Output**: substitute, combine, adapt, modify, put to another use, eliminate, reverse ideas.

### Six Thinking Hats
- **Use when**: a group needs to separate facts, risks, benefits, feelings, creativity, and process.
- **Avoid when**: the issue requires data analysis more than group facilitation.
- **Output**: balanced discussion notes and decision prompts.

### Crazy 8s
- **Use when**: rapidly generating many UI or concept directions.
- **Avoid when**: the problem frame is still unclear.
- **Output**: divergent solution sketches.

### Storyboarding
- **Use when**: explaining a concept through a user situation, trigger, action, and outcome.
- **Avoid when**: the solution is infrastructure-heavy with little user-facing change.
- **Output**: narrative sequence and experience gaps.

### Value Proposition Canvas
- **Use when**: matching customer jobs, pains, and gains to product value.
- **Avoid when**: the team lacks a target customer.
- **Output**: customer profile, value map, and fit gaps.

## Information Architecture And Structure

### Card Sorting
- **Use when**: the team needs to discover how users would naturally group content, features, or product offerings before committing to a navigation or taxonomy.
- **Avoid when**: a structure is already in place and the question is whether users can find things in it; use tree testing instead. Also avoid when content is so technical that participants have no basis for grouping.
- **Inputs**: a list of 30 to 50 items written in plain language, a target user segment, and at least 15 to 30 participants for stable patterns.
- **Output**: clusters of items, candidate category labels, a dendrogram of grouping similarity, and a draft hierarchy.
- **Good looks like**: items written at consistent granularity in plain language, open sort used for discovery, closed sort reserved for narrow validation, dendrograms read for stable clusters rather than perfect agreement.
- **Common failures**: cards written in internal jargon, mixed granularity producing meaningless clusters, recruiting participants who are not target users, treating the result as a finished IA rather than a starting point.

### Tree Testing
- **Use when**: a draft or live navigation needs to be evaluated for findability before launch, or to identify where users get lost in an existing structure.
- **Avoid when**: there is no candidate hierarchy yet; do card sorting first. Also avoid when the failure is more likely a labeling problem than a structure problem; consider first-click testing or content review.
- **Inputs**: a labeled tree, a set of representative tasks, and 50 or more participants per user segment for diverse coverage.
- **Output**: success rate, directness, time on task, and first-click and path heatmaps showing where users diverge from the intended route.
- **Good looks like**: tasks framed as user goals not feature names, success measured by reaching the right destination not the shortest path, multiple findable paths treated as a feature rather than a bug.
- **Common failures**: writing tasks that telegraph the answer through label matching, treating low directness as proof the whole tree is wrong when it might be one ambiguous label, optimizing for one perfect path rather than recoverable navigation.

### Mental Models
- **Use when**: there is a gap between how users think a system works and how it actually works, and that gap is causing errors, abandonment, or support load.
- **Avoid when**: the question is purely about visual design or a single feature; mental model work is heavyweight and rewards problems with broad scope.
- **Inputs**: contextual interviews or task observations, a candidate domain to model, and willingness to revise either the system or its surface to match user expectation.
- **Output**: a diagram of user beliefs, system behaviors, and the mismatches between them, with a list of interventions to close the gap.
- **Good looks like**: the model captures user vocabulary not internal vocabulary, mismatches are categorized as either system changes or communication changes, the resulting interventions are testable.
- **Common failures**: drawing a system diagram and calling it a mental model, treating user misconceptions as bugs in the user, modeling everything when the gap is local.

### Object-Oriented UX
- **Use when**: an interface has multiple object types (orders, customers, articles, classes, students) and the team is debating page structures, navigation, or flows in isolation from those objects.
- **Avoid when**: the product is a linear funnel or a single-task tool. Object-oriented UX is overhead unless the system has nouns the user reasons about.
- **Inputs**: a candidate list of objects, their attributes, their relationships, and the actions a user wants to take on each.
- **Output**: an object map showing object types, their fields, their relationships, and a derived navigation and screen inventory.
- **Good looks like**: every screen ties to one or more objects, attributes are collected per object rather than per screen, navigation reflects relationships between objects.
- **Common failures**: extracting objects from existing screens rather than from user goals, conflating an object with a feature, mapping attributes nobody actually needs.

## Interaction Design

### Norman Action Cycle
- **Use when**: a flow has poor completion or recovery, and the team needs a structured way to find whether the breakdown is in figuring out what to do, doing it, or interpreting the result.
- **Avoid when**: the problem is strategic or research-shaped rather than an interaction breakdown.
- **Inputs**: a representative task, a working artifact or prototype, and observation of users attempting the task.
- **Output**: a stage-by-stage account of where attention, action, perception, and interpretation break down, with targeted fixes (better signifiers, better feedback, better mapping).
- **Good looks like**: the diagnosis names a specific stage, the gulf is identified as execution or evaluation, the fix matches the gulf rather than redesigning the whole flow.
- **Common failures**: treating every breakdown as an execution problem and adding more affordances when feedback was the issue, or vice versa.

### Microinteractions Anatomy
- **Use when**: a small repeated moment in the product (a toggle, a like, a save, a notification, a status change) needs to feel reliable, fast, and right.
- **Avoid when**: the bigger flow is broken; fixing a microinteraction inside a broken flow is polish on the wrong layer.
- **Inputs**: a clearly bounded moment with one job, an understanding of how often it fires, and the technical surface that produces the trigger.
- **Output**: a specification for trigger (manual or system), rules (what can and cannot happen), feedback (visual, auditory, haptic), and loops or modes (how it changes over time or in special contexts).
- **Good looks like**: feedback weight matches event importance (a save toast is not a system alert), nothing starts from a blank zero state when the system already knows something, modes used sparingly and clearly entered and exited.
- **Common failures**: adding animation as decoration rather than feedback, missing feedback for a system trigger that the user never initiated, overusing modes so users lose track of which one they are in.

### UI State Inventory
- **Use when**: designing or reviewing any data-bearing screen or component, or auditing existing work for production readiness.
- **Avoid when**: pure brand or marketing layouts that do not load or change content.
- **Inputs**: the screen or component in question, the data it depends on, and an honest list of what can fail or be missing.
- **Output**: a complete set of state designs covering at minimum empty (first use, cleared, no results), loading (initial, refresh, partial), success (typical, dense, sparse), error (recoverable, fatal, network), and offline. Each state has copy, an action when one is possible, and a transition rule.
- **Good looks like**: empty states answer "what should I do now," loading states match expected duration (skeleton for predictable shape, spinner for unknown, progress for long), error messages name the problem in user terms and offer a path forward, no flicker between states under one second.
- **Common failures**: designing only the success state with rich data, using a generic spinner when the shape is predictable, error copy that exposes raw system errors, no thought given to no-results-after-filter as a distinct empty state.

### Affordances And Signifiers
- **Use when**: users do not realize an element is interactive, or interact with elements that are not, or use the wrong gesture.
- **Avoid when**: discovery is fine and the issue is downstream in the flow.
- **Inputs**: the surface in question, the gestures or input modalities available, and observation of misclicks or missed actions.
- **Output**: a revised design where signifiers (visual cues) make affordances (possible actions) discoverable, with an explicit list of what is interactive and how the user knows.
- **Good looks like**: a person not on the team can predict what is clickable from a static screenshot, hover and focus and pressed states are designed not assumed, no false affordances on decorative elements.
- **Common failures**: mistaking minimalism for clarity, designing for the user's second use rather than first use, assuming hover states cover discovery on touch devices.

## Design Systems And Visual Architecture

### Atomic Design
- **Use when**: the team is building or organizing a component library and needs a shared mental model for how small parts compose into larger structures.
- **Avoid when**: the product has fewer than 10 reusable components, or the team is litigating chemistry labels rather than building.
- **Inputs**: an existing or planned UI, a willingness to name components by composition rather than feature.
- **Output**: a component hierarchy from foundational elements to full pages, with rules for what belongs at each level and how levels reference each other.
- **Good looks like**: the labels (atoms, molecules, organisms, templates, pages) help the team communicate, not constrain it. Composition rules are clear: lower levels never depend on higher levels.
- **Common failures**: arguing whether something is an atom or a molecule for hours, taking the chemistry analogy literally, forcing a flat library into a strict hierarchy when the team would be served by a flat or feature-grouped structure.

### Design Token Architecture
- **Use when**: the system needs to support theming, dark mode, multi-brand, or accessibility variants, or when a rebrand has touched hundreds of components.
- **Avoid when**: the product is single-brand, single-theme, and unlikely to change. Tokens add overhead that pays off through change.
- **Inputs**: the visual properties used across the system (color, spacing, typography, radius, shadow, motion), the themes or brands that need to coexist, and the platforms tokens must reach (web, native, email).
- **Output**: a layered token system with primitive (raw values), semantic (intent like color-text-primary), and component-level (button-bg-default) tiers, plus a transformation pipeline to each platform.
- **Good looks like**: components reference semantic tokens, semantic tokens reference primitives, theming is a swap of the semantic layer, naming is intent-based not value-based (color-action-primary not color-blue-500).
- **Common failures**: skipping the semantic layer so components reference primitives directly, value-based names that lie when the value changes, building component tokens for every component before the semantic layer is stable.

### Component API Design
- **Use when**: a reusable component is being designed and the team needs to decide its props, variants, slots, and states before consumers build on it.
- **Avoid when**: the surface is one-off and unlikely to be reused. Designing a flexible API for one user is overhead.
- **Inputs**: a list of intended use cases, the consumers of the component (designers, engineers, product teams), and the platforms it must run on.
- **Output**: a documented API with named props, allowed values, default states, slot or composition rules, accessibility requirements, and a list of explicitly unsupported variations.
- **Good looks like**: the component handles its core use cases without consumer escape hatches, variants are restricted not unlimited, compound components compose explicitly, the unsupported list is published.
- **Common failures**: adding a prop for every request rather than questioning the request, exposing every internal style as a prop, undocumented escape hatches that consumers rely on and that block future changes.

## Accessibility And Inclusion

### POUR (WCAG Principles)
- **Use when**: building or auditing any interface that real users will use, especially one subject to legal accessibility requirements.
- **Avoid when**: brand exploration or mood work; POUR applies once functional UI exists.
- **Inputs**: the interface, the relevant WCAG version (2.2 is current), and access to assistive technologies for testing (screen reader, keyboard-only, voice).
- **Output**: a conformance assessment by principle, a prioritized remediation list, and ongoing rules for new work.
- **Good looks like**: each issue is mapped to a specific success criterion, severity is judged by user impact not just conformance, fixes are durable (built into components and tokens) rather than per-screen patches.
- **Common failures**: treating POUR as a one-time audit rather than an ongoing practice, focusing only on color contrast because it is easy to test, conflating WCAG conformance with usability for disabled users, ignoring keyboard focus order.

### Persona Spectrum
- **Use when**: the team is designing for ability, sensory, or cognitive variation and needs to expand a single persona into a range of permanent, temporary, and situational conditions.
- **Avoid when**: used as a substitute for involving disabled users in research and decisions.
- **Inputs**: a target permanent condition (mobility, vision, hearing, cognition), an understanding of the related temporary conditions (injury, illness) and situational conditions (environment, distraction, multitasking).
- **Output**: a spectrum mapping the related conditions and a design brief that names which interventions help across the spectrum (solve for one, extend to many).
- **Good looks like**: the spectrum drives concrete design constraints (target sizes, contrast ratios, error tolerances), informed by research with people who have the permanent condition.
- **Common failures**: simulating a disability with a blindfold or earplug instead of consulting people who live with it, using the spectrum to soften the case for accessibility ("everyone benefits") rather than to strengthen it.

### Inclusive Design Exclusion Mapping
- **Use when**: a team needs to find who their current solution leaves out, especially before validating with a representative-but-narrow user sample.
- **Avoid when**: the team is unwilling to change anything in response. Exclusion mapping is uncomfortable on purpose.
- **Inputs**: a current design or product, a description of the assumed user, and willingness to identify mismatches honestly.
- **Output**: a list of mismatches between people and the design, categorized by whether the cause is the design, the environment, the social context, or the technology, plus interventions for each.
- **Good looks like**: exclusions are stated specifically and without euphemism (a person using a screen reader cannot complete checkout because the form labels are missing), interventions name who they help and how the team will know it worked.
- **Common failures**: producing a list of vague concerns no one will act on, treating exclusion as an edge case rather than a design failure, conflating exclusion with accessibility (it is broader, including language, literacy, and culture).

## Design Quality And Critique

### LIWI (I Like, I Wish, What If)
- **Use when**: a small group needs to give feedback on work-in-progress without descending into redesign or defensiveness.
- **Avoid when**: the work needs a directional decision rather than feedback. Feedback is not a substitute for a decision-maker.
- **Inputs**: a presented artifact or prototype, a clear question the presenter wants feedback on, a facilitator who keeps statements in the right form.
- **Output**: a list of likes (what is working and why), wishes (what could be improved), and what-ifs (alternative directions worth exploring).
- **Good looks like**: feedback is specific to the work shown, the presenter listens without defending, the facilitator catches statements that drift into command form ("you should..."), what-ifs are exploratory not prescriptive.
- **Common failures**: turning critique into a redesign session, vague likes ("nice work") that carry no signal, wishes that are really commands, the presenter defending instead of listening.

### Heuristic Evaluation
- **Use when**: quickly finding usability issues against established principles.
- **Avoid when**: replacing user testing for high-stakes workflows.
- **Output**: prioritized usability findings and recommended fixes.

### Cognitive Walkthrough
- **Use when**: checking whether a user can understand and complete a flow without instruction.
- **Avoid when**: the team needs broad strategic discovery.
- **Output**: step-by-step usability risks and fixes.

### Design Parity Check
- **Use when**: a built feature should match its design specification, especially during release readiness or for design system adoption.
- **Avoid when**: the build is exploratory and the design intent is still evolving.
- **Inputs**: the design source (Figma file, spec, tokens), the built artifact, and access to inspect both.
- **Output**: a list of discrepancies categorized as token violations (hardcoded values), spacing or sizing drift, missing states, or interaction differences.
- **Good looks like**: discrepancies are specific (color X used instead of token Y at location Z), categorized by whether the design or the build is wrong, fed back into the design system so the same drift does not recur.
- **Common failures**: pixel-counting in screenshots rather than inspecting tokens, treating every difference as a build bug when the spec was ambiguous, producing a list nobody fixes because there is no accountable owner.

### Task Analysis
- **Use when**: improving a workflow, productivity tool, or user task completion.
- **Avoid when**: the problem is market-level strategy.
- **Output**: task steps, decisions, friction, error points, and redesign opportunities.

## Technology And Feasibility

### Architecture Decision Record
- **Use when**: a decision will be hard to reverse, will be challenged later, or affects more than one team. Examples: which framework, which database, which integration pattern, which design system, which token format.
- **Avoid when**: the decision is small, reversible, and affects one person. ADR overhead is not free.
- **Inputs**: the decision question, the forces in tension (technical, organizational, cost, time), the options considered, the chosen option.
- **Output**: a short markdown document (one to two pages) with title, status, context, decision, and consequences. Stored next to the code or in a `decisions/` folder.
- **Good looks like**: written in plain language and full sentences, names the alternatives that were rejected and why, lists positive and negative consequences, immutable once accepted (a new ADR supersedes rather than edits an old one).
- **Common failures**: writing ADRs after the fact for decisions no one will revisit, recording the chosen option without the alternatives, editing accepted ADRs in place rather than superseding them, treating it as architecture documentation rather than decision history.

### C4 Model
- **Use when**: a software system needs to be explained to a mixed audience and current diagrams are either absent, inconsistent, or too detailed for non-technical stakeholders.
- **Avoid when**: the system is small, single-purpose, or fully described by its README. Also avoid for products that are mostly customization (Salesforce, SAP) rather than bespoke development.
- **Inputs**: the system in question, an audience (executives, new engineers, security review, ops), and a target zoom level.
- **Output**: hierarchical diagrams, system context (level 1, the whole world), container (level 2, deployable units), component (level 3, internals of one container), code (level 4, optional and rarely useful by hand).
- **Good looks like**: each diagram has a title, legend, and stated audience, the level matches the question being asked, container and component levels do not blur into each other, diagrams are kept in source control and updated with code.
- **Common failures**: drawing one diagram for all audiences, mixing levels in a single picture, treating boxes-and-lines as the model rather than what the boxes mean, producing a level 4 code diagram by hand.

### Build, Buy, Borrow
- **Use when**: a capability is needed and the team is debating whether to build it from scratch, buy a vendor product, or borrow open source or an existing internal solution.
- **Avoid when**: the capability is core to the product's differentiation; that is a build by default.
- **Inputs**: the capability needed, the time and cost of each path, the long-term ownership cost, the strategic importance of the capability, and the integration surface.
- **Output**: a comparison across the three paths with one-time cost, ongoing cost, time to value, control, and strategic risk, plus a recommendation.
- **Good looks like**: the strategic question (is this a differentiator?) is answered before the cost question, the ongoing cost includes maintenance and integration not just license, "borrow" is a real option not an afterthought.
- **Common failures**: treating "build" as free because labor is internal, choosing "buy" without understanding the integration cost, ignoring the option to borrow because nobody surveyed what exists, making the decision once and never revisiting as the product matures.

### Tradeoff Sliders
- **Use when**: a decision involves competing qualities (speed vs correctness, cost vs flexibility, scope vs schedule) and stakeholders need to make the tradeoff explicit before scoping work.
- **Avoid when**: the qualities do not actually trade off, or the conversation is really about a missing constraint.
- **Inputs**: the qualities under tension (typically three to five), the stakeholders who own the decision, and the project at hand.
- **Output**: a set of sliders showing each quality's relative priority for this decision, with explicit acknowledgment of what is being deprioritized.
- **Good looks like**: every quality has a position, no slider is at maximum without something else being lower, the resulting picture survives stress-testing against likely difficult choices.
- **Common failures**: every slider at maximum because nobody wants to say no, the sliders treated as a wishlist rather than a decision, no documented reference back when scoping conversations happen later.

### Spike Or Build
- **Use when**: there is uncertainty about whether something is technically feasible, how long it will take, or what shape the solution will have, and the team is about to commit to building it.
- **Avoid when**: the path is well-understood and the question is just sequencing.
- **Inputs**: the specific uncertainty in question, the time budget for resolving it, the smallest experiment that would resolve it.
- **Output**: a time-boxed exploration (a spike) that produces a written learning, a working but throwaway prototype, or both, with a decision on whether to proceed, change direction, or stop.
- **Good looks like**: the spike has a written question, a time limit, and a written outcome. The output is the answer, not the artifact. The spike's code is explicitly thrown away or rebuilt in production form.
- **Common failures**: the spike turns into the production code by accident, the time limit is ignored, no learning is written down so the next person re-spikes the same question.

## Product Strategy

### Strategy Kernel
- **Use when**: the team needs a coherent strategy rather than a list of goals.
- **Avoid when**: the question is a tactical feature decision.
- **Output**: diagnosis, guiding policy, and coherent actions.

### Product Strategy Stack
- **Use when**: aligning vision, strategy, roadmap, goals, and execution choices.
- **Avoid when**: the question is a single experiment or UX flow.
- **Output**: aligned stack and contradictions to resolve.

### Product Vision Board
- **Use when**: defining product vision, target group, needs, product, business goals, and competitors.
- **Avoid when**: the product is mature and the issue is optimization.
- **Output**: product vision snapshot.

### North Star Framework
- **Use when**: aligning teams around a metric that represents delivered customer value and business growth.
- **Avoid when**: the product lacks a clear value exchange or usage event.
- **Output**: North Star metric, inputs, guardrails, and team ownership.

### Metric Tree
- **Use when**: decomposing a high-level outcome into controllable drivers.
- **Avoid when**: the team does not trust the data or lacks instrumentation.
- **Output**: outcome, driver tree, leading indicators, and intervention points.

### OKRs
- **Use when**: translating strategy into measurable objectives and key results.
- **Avoid when**: the strategy is unclear or the team uses OKRs as a task list.
- **Output**: objectives, key results, initiatives, and confidence checks.

### Wardley Mapping
- **Use when**: understanding strategic landscape, user needs, value chain, evolution, build/buy/partner choices, and competitive movement.
- **Avoid when**: the problem is a narrow UX or growth experiment.
- **Output**: map of user needs, components, maturity, doctrine, and strategic moves.

### Blue Ocean Strategy
- **Use when**: seeking differentiation by changing the basis of competition.
- **Avoid when**: the market category and positioning are already fixed.
- **Output**: eliminate-reduce-raise-create grid and strategy canvas.

### Playing To Win
- **Use when**: making explicit strategic choices about winning aspiration, where to play, how to win, capabilities, and systems.
- **Avoid when**: the team cannot make tradeoffs.
- **Output**: choice cascade.

### Three Horizons
- **Use when**: balancing core business, emerging opportunities, and future bets.
- **Avoid when**: the problem is immediate product discovery.
- **Output**: horizon portfolio and investment posture.

### Ansoff Matrix
- **Use when**: choosing between market penetration, product development, market development, and diversification.
- **Avoid when**: the team lacks basic market and product clarity.
- **Output**: growth direction options and risk profile.

### BCG Matrix
- **Use when**: comparing business lines or products by growth and relative share.
- **Avoid when**: used for a single product feature decision.
- **Output**: portfolio posture and investment implications.

### Business Model Canvas
- **Use when**: reasoning about value proposition, customers, channels, relationships, revenue, resources, activities, partners, and costs.
- **Avoid when**: the business model is stable and the issue is local UX.
- **Output**: business model map and weak points.

### Lean Canvas
- **Use when**: evaluating an early-stage product or startup idea.
- **Avoid when**: the company is mature and has many existing constraints.
- **Output**: problem, solution, unfair advantage, channels, revenue, costs, metrics, and customer segments.

## Growth Strategy And Lifecycle

### Growth Loops
- **Use when**: identifying compounding mechanisms where product outputs feed future acquisition, activation, engagement, or monetization.
- **Avoid when**: the product has no repeatable input-output cycle or cannot instrument loop health.
- **Output**: loop diagram, input, action, output, reinvestment path, coefficient, cycle time, and constraints.

### AARRR / Pirate Metrics
- **Use when**: diagnosing lifecycle bottlenecks across acquisition, activation, retention, referral, and revenue.
- **Avoid when**: used as a growth strategy by itself rather than a measurement lens.
- **Output**: funnel/lifecycle diagnosis and bottleneck priorities.

### AAARRR
- **Use when**: awareness matters as a distinct stage before acquisition.
- **Avoid when**: brand or demand generation is not part of the problem.
- **Output**: awareness-to-referral lifecycle map.

### Growth Model
- **Use when**: the team needs a quantitative model of how users, revenue, retention, and channels interact.
- **Avoid when**: there is insufficient data for even rough assumptions.
- **Output**: growth equation, drivers, sensitivities, and leverage points.

### Growth Accounting
- **Use when**: understanding retained, resurrected, new, and churned users or revenue.
- **Avoid when**: user identity and cohort data are unreliable.
- **Output**: growth accounting table and priority diagnosis.

### Retention Curve Analysis
- **Use when**: retention or engagement is suspected to be the growth constraint.
- **Avoid when**: the product has very long usage cycles and limited cohorts.
- **Output**: cohort curves, activation correlations, and retention hypotheses.

### Engagement Loop
- **Use when**: repeated usage is driven by triggers, actions, rewards, investment, or habit formation.
- **Avoid when**: the product is episodic by nature.
- **Output**: trigger-action-reward-investment map and friction points.

### Hook Model
- **Use when**: designing habit-forming engagement loops ethically.
- **Avoid when**: manipulative engagement would harm users or trust.
- **Output**: trigger, action, variable reward, investment, and ethical guardrails.

### Lifecycle Marketing Map
- **Use when**: coordinating messaging, nudges, and education across user stages.
- **Avoid when**: product value itself is unclear.
- **Output**: stage map, user state, message, channel, trigger, metric, and failure mode.

### Activation Framework
- **Use when**: users sign up but fail to reach first value.
- **Avoid when**: acquisition quality is the primary problem.
- **Output**: aha moment, setup path, friction, segmentation, and activation experiments.

### Referral Loop
- **Use when**: growth depends on users inviting, sharing, publishing, or collaborating.
- **Avoid when**: sharing does not create real value for sender and receiver.
- **Output**: sender motivation, receiver value, trigger, channel, incentive, and loop health.

### Content / SEO Loop
- **Use when**: user-generated or company-generated content can compound into discoverability.
- **Avoid when**: search intent is weak or content quality cannot be sustained.
- **Output**: content supply, indexing, distribution, conversion, and reinvestment loop.

### Sales-Led Growth Motion
- **Use when**: buying requires high trust, complex stakeholders, procurement, or enterprise adoption.
- **Avoid when**: the product can be adopted self-serve with low friction.
- **Output**: ICP, buying committee, sales stages, proof assets, and handoffs.

### Product-Led Growth Motion
- **Use when**: users can discover, try, adopt, and expand mostly through the product.
- **Avoid when**: implementation requires heavy services or executive approval.
- **Output**: self-serve journey, value gates, monetization trigger, and expansion paths.

### Subscription Value Loop
- **Use when**: a subscription product must connect ongoing value creation, delivery, and capture.
- **Avoid when**: revenue is transactional or one-off.
- **Output**: value creation, delivery, capture, reinvestment, and compounding opportunities.

### Monetization Ladder
- **Use when**: designing tiers, packaging, paywalls, or expansion paths.
- **Avoid when**: willingness to pay is unknown and no value metric exists.
- **Output**: free-to-paid path, value metric, package boundaries, and upgrade triggers.

## Prioritization And Decision-Making

### RICE
- **Use when**: prioritizing product opportunities by reach, impact, confidence, and effort.
- **Avoid when**: inputs are political guesses or the strategic objective is unclear.
- **Output**: ranked opportunities with confidence notes.

### ICE
- **Use when**: quickly prioritizing experiments by impact, confidence, and ease.
- **Avoid when**: reach varies dramatically and must be explicit.
- **Output**: quick experiment ranking.

### Weighted Decision Matrix
- **Use when**: comparing options across multiple criteria with explicit tradeoffs.
- **Avoid when**: criteria weights are arbitrary or hide a strategic disagreement.
- **Output**: scored options, sensitivity, and recommendation.

### Cost Of Delay / WSJF
- **Use when**: sequencing work where delay has measurable value impact.
- **Avoid when**: cost of delay cannot be estimated even directionally.
- **Output**: weighted shortest job first ranking.

### MoSCoW
- **Use when**: aligning on must, should, could, and will-not scope.
- **Avoid when**: every stakeholder labels their request a must.
- **Output**: scope tiers and negotiation points.

### Eisenhower Matrix
- **Use when**: separating urgent/important work from noise.
- **Avoid when**: prioritizing strategic product bets.
- **Output**: do, schedule, delegate, delete actions.

### One-Way / Two-Way Door
- **Use when**: deciding how much analysis a decision deserves based on reversibility.
- **Avoid when**: reversibility is unclear or consequences are systemic.
- **Output**: decision speed, evidence bar, and rollback plan.

### OODA Loop
- **Use when**: operating in competitive, fast-changing, uncertain environments.
- **Avoid when**: the problem is slow-cycle planning with stable data.
- **Output**: observe, orient, decide, act loop and learning cadence.

### Premortem
- **Use when**: pressure is high and the team needs to surface failure modes before committing.
- **Avoid when**: the team is not willing to change the plan.
- **Output**: failure story, causes, mitigations, and watchpoints.

### Decision Journal
- **Use when**: the user wants to improve judgment over time.
- **Avoid when**: there is no clear decision or future review point.
- **Output**: decision, context, options, assumptions, expected outcomes, and review date.

## Strategy, Market, And Positioning

### April Dunford Positioning
- **Use when**: customers do not understand what the product is, who it is for, or why it matters.
- **Avoid when**: the core product value is not yet real.
- **Output**: competitive alternatives, unique attributes, value, target segment, category, and trends.

### Geoffrey Moore Positioning Statement
- **Use when**: the team needs a concise positioning statement for a focused segment.
- **Avoid when**: category or segment choices are unresolved.
- **Output**: for, who, product, category, benefit, alternative, differentiation statement.

### Category Design
- **Use when**: the product may need to define a new market frame instead of competing inside an existing one.
- **Avoid when**: buyers already have a clear category and search behavior.
- **Output**: category POV, enemy, new value criteria, and narrative.

### Competitive Alternatives
- **Use when**: understanding what customers would use if the product did not exist.
- **Avoid when**: focusing only on direct competitors.
- **Output**: alternatives map and differentiation opportunities.

### Porter Five Forces
- **Use when**: assessing industry attractiveness and structural pressures.
- **Avoid when**: the problem is product discovery or UX.
- **Output**: force assessment and strategic implications.

### SWOT
- **Use when**: quickly summarizing internal and external factors for discussion.
- **Avoid when**: it becomes a shallow list without strategic choices.
- **Output**: strengths, weaknesses, opportunities, threats, and implications.

### PESTLE
- **Use when**: external macro factors may shape strategy.
- **Avoid when**: the problem is internal execution.
- **Output**: political, economic, social, technological, legal, and environmental scan.

### Crossing The Chasm
- **Use when**: moving from early adopters to mainstream market adoption.
- **Avoid when**: the product is not in a technology adoption market.
- **Output**: beachhead segment, whole product gaps, and go-to-market focus.

### ICP And Segmentation
- **Use when**: deciding who the product should serve first or best.
- **Avoid when**: the team is unwilling to exclude low-fit segments.
- **Output**: ideal customer profile, segment scoring, and focus recommendation.

## Systems And Complexity

### Systems Map
- **Use when**: the problem has many actors, incentives, feedback loops, and unintended consequences.
- **Avoid when**: a linear funnel or task analysis is enough.
- **Output**: actors, relationships, feedback loops, leverage points, and risks.

### Causal Loop Diagram
- **Use when**: reinforcing and balancing loops explain the behavior of a product, market, or organization.
- **Avoid when**: relationships are too speculative to reason about.
- **Output**: causal loops, delays, and intervention hypotheses.

### Theory Of Constraints
- **Use when**: improving a process, system, or team by finding the limiting constraint.
- **Avoid when**: the bottleneck is not measurable.
- **Output**: constraint, exploitation plan, subordination choices, and next constraint.

### Leverage Points
- **Use when**: looking for high-impact interventions in a complex system.
- **Avoid when**: the system boundary is unclear.
- **Output**: leverage point ranking and intervention options.

### Iceberg Model
- **Use when**: moving from events to patterns, structures, and mental models.
- **Avoid when**: immediate tactical response is enough.
- **Output**: event, pattern, structure, mental model diagnosis.

## Execution, Planning, And Learning

### Lean Startup Build-Measure-Learn
- **Use when**: validating a product hypothesis through iterative experiments.
- **Avoid when**: the team needs strategy before experimentation.
- **Output**: hypothesis, MVP/test, metric, learning, and pivot/persevere decision.

### Experiment Loop
- **Use when**: turning ideas into controlled tests.
- **Avoid when**: the decision cannot be influenced by test results.
- **Output**: hypothesis, audience, intervention, metric, threshold, duration, and decision rule.

### Research Plan
- **Use when**: evidence gaps require interviews, surveys, usability tests, or data analysis.
- **Avoid when**: the team already has enough evidence to decide.
- **Output**: research questions, method, sample, script outline, and synthesis plan.

### DACI / RAPID
- **Use when**: decision ownership and stakeholder roles are unclear.
- **Avoid when**: one accountable owner already exists.
- **Output**: driver/recommender/approver/contributors/informed or RAPID role map.

### RACI
- **Use when**: execution roles are unclear after a decision.
- **Avoid when**: the work is still in discovery.
- **Output**: responsible, accountable, consulted, informed matrix.

### Working Backwards PRFAQ
- **Use when**: defining a customer-facing product vision before implementation.
- **Avoid when**: the team needs quick tactical iteration.
- **Output**: press release, FAQ, customer promise, and open questions.

### Narrative Strategy Memo
- **Use when**: a nuanced decision needs shared context and judgment.
- **Avoid when**: a simple canvas is enough.
- **Output**: written argument with diagnosis, options, recommendation, risks, and decision.

## Elimination Rules

Cull or de-prioritize frameworks when they:

- Produce labels but no decision.
- Require data the user cannot reasonably gather.
- Are redundant with a better-fitting framework.
- Encourage premature ideation before problem diagnosis.
- Hide tradeoffs behind scoring theater.
- Do not produce a useful artifact for the user’s next step.
