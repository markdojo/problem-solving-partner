# Memory Model

The first version should be local-first and portable. The goal is to preserve useful thinking without locking the workflow into one assistant, editor, or storage product.

## Recommended Starting Point

Use local markdown files as the default memory layer.

Reasons:

- Works across Cursor, Claude, Codex, ChatGPT, and humans.
- Easy to edit, copy, version, and migrate.
- Does not require database schema decisions before the workflow is proven.
- Keeps the first version focused on judgment and method quality.

## What To Save

Save artifacts that will be useful later:

- Problem briefs.
- Framework selections and why they were chosen.
- Working canvases.
- Decision logs.
- Experiment plans and results.
- Reusable examples.
- Personal notes about which frameworks worked well or poorly.

Do not save everything. Raw conversation is usually less useful than a clean synthesis.

## Suggested Folder Structure

```text
problem-solving-partner/
  briefs/
  decisions/
  experiments/
  examples/
  framework-notes/
```

This can live inside a project, a personal notes folder, or a Notion export. The Cursor Skill itself should stay small and reference the reusable playbook files.

## Memory Levels

### Level 0: No Memory

Use for quick conversations where the artifact is disposable.

- **Pros**: fastest, no maintenance, works anywhere.
- **Cons**: loses continuity, repeats context collection.

### Level 1: Local Markdown

Use for the first durable version.

- **Pros**: portable, simple, inspectable, versionable.
- **Cons**: search and linking are manual unless paired with a notes system.

### Level 2: Notion

Use when you want searchable personal or team knowledge.

- **Pros**: structured records, databases, backlinks, sharing, tasks.
- **Cons**: requires schema design and creates tool dependence.

Good Notion databases:

- Problem Briefs.
- Framework Decisions.
- Experiments.
- Strategy Memos.
- Research Notes.

### Level 3: MCP

Use when assistants need tools to read/write shared state or query structured knowledge.

- **Pros**: reusable across assistant surfaces, can expose framework lookup, saved briefs, Notion, databases, or search.
- **Cons**: needs API design, auth, deployment, and ongoing maintenance.

Good MCP tools later:

- `search_frameworks`
- `recommend_frameworks`
- `create_problem_brief`
- `save_decision_log`
- `list_open_experiments`
- `retrieve_related_briefs`

### Level 4: Standalone App

Use when the workflow needs a visual and collaborative interface.

- **Pros**: best for canvases, comparisons, guided intake, and team use.
- **Cons**: highest build and maintenance cost.

Good app features later:

- Problem intake wizard.
- Framework recommendation engine.
- Canvas editor.
- Side-by-side approach comparison.
- Saved decision history.
- Experiment tracker.
- Team templates.

## Persistence Decision Rule

Move up a memory level only when the lower level is painful:

- If you keep repeating context, save markdown briefs.
- If you cannot find prior work, move briefs into Notion.
- If assistants need to retrieve and update prior work automatically, add MCP.
- If humans need a dedicated visual workflow, build an app.

## Default Export Format

Use this filename pattern:

```text
YYYY-MM-DD-short-problem-name.md
```

Use this frontmatter when saving locally:

```yaml
---
type: problem-brief
problem_type:
dominant_uncertainty:
framework:
status: draft
created:
review:
---
```

## What Not To Build Yet

- Do not start with a database.
- Do not build a recommendation API before the rubric has been tested manually.
- Do not encode framework selection as rigid rules too early.
- Do not make Notion required for the workflow.
- Do not store raw chat unless there is a clear retrieval use case.
