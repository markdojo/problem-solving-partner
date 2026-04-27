# Problem-Solving Partner

A portable operating system for tackling ambiguous design, product, strategy, and growth problems.

## What This Is

This is a personal Cursor Skill plus a portable markdown playbook. The same workflow can be used in Cursor, Claude, Codex, ChatGPT, or by a human facilitator.

## How To Use

Ask for help framing a problem, for example:

```text
Help me think through why activation is weak for our new onboarding flow.
```

The partner should:

1. Diagnose the problem type.
2. Identify the dominant uncertainty.
3. Recommend a framework.
4. Guide application of that framework.
5. Produce a reusable artifact.

## Files

- `SKILL.md`: Cursor Skill adapter.
- `framework-library.md`: broad curated framework library.
- `problem-taxonomy.md`: classification system for problem types and uncertainties.
- `selection-rubric.md`: framework matching and rejection rules.
- `workflow.md`: end-to-end conversational flow.
- `memory-model.md`: local-first storage guidance and future Notion/MCP path.
- `portable-prompts.md`: prompts for Claude, Codex, ChatGPT, and generic assistants.
- `evaluation-rubric.md`: quality rubric for diagnosis, framework selection, framework application, and output usefulness.
- `templates/`: reusable artifact templates.
- `examples/`: example walkthroughs.
- `evals/`: starter evaluation cases for improving the partner over time.

## Recommended First Use

Start with a real problem and ask the partner to create an intake brief. After the first session, export a synthesis brief and save only the useful artifact, not the entire chat.

## Improvement Loop

Use the cases in `evals/` to test whether the partner chooses the right framework, rejects weak fits, and produces a useful artifact. When a case fails, update the smallest relevant file rather than rewriting the whole system.
