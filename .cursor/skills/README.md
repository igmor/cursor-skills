## Project Skills

This directory contains **project-level Cursor skills** for this repository.

### How to add a new skill

1. Choose a short, kebab-case directory name (e.g. `git-commit-helper`).
2. Create a subdirectory under this folder with that name.
3. Inside the subdirectory, create a `SKILL.md` file with:
   - YAML frontmatter:
     - `name`: the same kebab-case identifier.
     - `description`: a clear, third-person description of what the skill does and when to use it.
   - Markdown body describing instructions, workflows, and examples.

Example structure:

```text
.cursor/skills/
  git-commit-helper/
    SKILL.md
  code-review/
    SKILL.md
```

Skills in this directory are automatically available when you open this repository in Cursor.

