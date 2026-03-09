# Skills

Custom skills for any skill-compatible agent.

For Chinese documentation, see [README.zh.md](README.zh.md).

## Install

This repository can be installed with the official `npx skills` CLI.

List skills available in this repo:

```bash
npx skills add zjsxply/skills --list
```

Install the skill from GitHub:

```bash
npx skills add zjsxply/skills --skill semantic-scholar-library-feed
```

Install the skill globally:

```bash
npx skills add zjsxply/skills --skill semantic-scholar-library-feed -g -y
```

Notes:

- Default install scope is the current project.
- Add `-g` to install globally.

## Available Skills

| Skill | What it does | Typical use cases |
| --- | --- | --- |
| `semantic-scholar-library-feed` | Work with a user's Semantic Scholar account to read Research Feeds, inspect private Library folders, add papers to folders, and resolve paper records from identifiers such as arXiv IDs. | Browse or export feed results, review saved papers, compare folder contents, update a library folder, and map stable identifiers to Semantic Scholar paper records. |

## Repository Layout

```text
semantic-scholar-library-feed/
  SKILL.md
  scripts/
  references/
  agents/
```

Each skill lives in its own directory and is centered around a `SKILL.md` file.
