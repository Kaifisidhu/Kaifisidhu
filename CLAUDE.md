# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

This is a **GitHub profile repository** (`kaifisidhu/kaifisidhu`). GitHub treats this special repository uniquely: the `README.md` file at the root is rendered directly on the user's public GitHub profile page at `https://github.com/kaifisidhu`.

## Repository Structure

```
/
├── README.md hidden eye   # GitHub profile README (rendered on profile page)
└── CLAUDE.md              # This file
```

There are no build systems, dependency files, test frameworks, or configuration files — this is a pure documentation repository.

## The README File

The file is named `README.md hidden eye` (unusual name with spaces — this is the actual filename as committed). It currently contains the default GitHub profile template:

- Introduction line (`@Kaifisidhu`)
- Placeholder sections for interests, learning, collaboration, and contact

The HTML comment block at the bottom explains that this special repository's README appears on the GitHub profile.

## Development Workflow

### Branching
- Default branch: `main`
- Feature branches follow the pattern: `claude/<description>-<id>`

### Making Changes
1. Edit `README.md hidden eye` to update profile content
2. Commit with a descriptive message
3. Push to the feature branch, then merge to `main`

```bash
git add "README.md hidden eye"
git commit -m "Update profile README"
git push -u origin <branch-name>
```

Note: Always quote or escape the filename when using shell commands because it contains spaces.

### No Build or Test Steps
There is nothing to build, lint, or test. Changes are validated by viewing the rendered Markdown on GitHub.

## Key Conventions

- **Filename**: The README is literally named `README.md hidden eye` — do not rename it without understanding the impact on the GitHub profile display (GitHub looks for `README.md` at the root; the space in the name may affect rendering).
- **Markdown only**: All content is standard GitHub Flavored Markdown (GFM). HTML is supported inline.
- **Profile-appropriate content**: This file is publicly visible on the GitHub profile. Keep content professional and accurate.
- **Emojis**: The existing template uses GitHub emoji shortcodes and Unicode emojis — this is conventional for GitHub profile READMEs.

## Common Tasks

| Task | Action |
|------|--------|
| Update bio/intro | Edit line 1 of `README.md hidden eye` |
| Add interests | Fill in line 2 placeholder |
| Update learning section | Fill in line 3 placeholder |
| Add collaboration info | Fill in line 4 placeholder |
| Add contact details | Fill in line 5 placeholder |
| Add badges/stats | Insert GitHub badge Markdown (shields.io, github-readme-stats, etc.) |
| Add sections | Append new `##` headings with content |
