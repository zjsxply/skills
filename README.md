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
| `awesome-repo-builder` | Create a topic-specific awesome-list repository scaffold with a polished README, contribution rules, agent instructions, URL verification, license, and reusable templates. | Start a curated resource catalog from a topic, taxonomy, inclusion criteria, and optional researched seed entries. |
| `image-to-text-pdf` | Convert a finished raster image into an image-based PDF with a selectable, copyable, searchable text layer plus a visible inspection copy. | Preserve a generated poster, visual resume, or image-first layout exactly while avoiding fragile PPT, HTML, or LaTeX reconstruction. |
| `semantic-scholar-library-feed` | Work with a user's Semantic Scholar account to read Research Feeds, inspect private Library folders, add papers to folders, and resolve paper records from identifiers such as arXiv IDs. | Browse or export feed results, review saved papers, compare folder contents, update a library folder, and map stable identifiers to Semantic Scholar paper records. |
| `skill-market-publisher` | Prepare, validate, and publish local skills across public skill marketplaces, directories, and registries with a mix of verified automation and manual submission bundles. | Plan a cross-market release, generate per-market payloads, verify current submission surfaces, publish to supported targets, and prepare manual notes for markets that still need browser submission. |
| `url-citation-search` | Find papers and preprints that cite a given URL by reverse-searching URL variants, titles, slugs, and mirror pages, then verifying the reference in PDF or HTML. | Check which papers cite a blog post, documentation page, project page, demo page, or other web content that standard citation indexes often miss. |
