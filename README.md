## Cursor Skills Repository

This repository is dedicated to storing and versioning your **Cursor Agent Skills**.

- **Project skills location**: skills for this repo live under `.cursor/skills/`.
- **Skill layout**: each skill is a directory containing at least a `SKILL.md` file.
- **Usage in Cursor**: when you open this repository in Cursor, all skills under `.cursor/skills/` become available as project-level skills.

### Directory structure

Recommended layout:

```text
.cursor/
  skills/
    my-skill/
      SKILL.md
    another-skill/
      SKILL.md
```

### Creating new skills

1. Create a new directory under `.cursor/skills/` using a short, kebab-case name (e.g. `api-docs-helper`).
2. Inside that directory, create a `SKILL.md` file with YAML frontmatter:

```markdown
---
name: api-docs-helper
description: Helps read and summarize API documentation. Use when working with REST or GraphQL API reference docs.
---
```

3. Below the frontmatter, document how the agent should use this skill:
   - What the skill is for.
   - When to apply it.
   - Any workflows, templates, or checklists the agent should follow.

For more details on authoring skills, see the built-in `create-skill` Cursor skill documentation.

