# CLAUDE.md

This file provides guidance for AI assistants working in this repository.

## Repository Overview

This is a **GitHub profile repository** (`kaifisidhu/kaifisidhu`). GitHub treats this special repository uniquely: the `README.md` file at the root is rendered directly on the user's public GitHub profile page at `https://github.com/kaifisidhu`.

## Repository Structure

```
/
├── README.md hidden eye   # GitHub profile README (rendered on profile page)
└── CLAUDE.md              # This file — AI assistant guidance
```

There are no build systems, dependency files, test frameworks, or configuration files — this is a pure documentation repository.

## The README File

The file is named `README.md hidden eye` (unusual name with spaces — this is the actual filename as committed). It currently contains the **default GitHub profile template** with unfilled placeholders:

```
- 👋 Hi, I'm @Kaifisidhu
- 👀 I'm interested in ...
- 🌱 I'm currently learning ...
- 💞️ I'm looking to collaborate on ...
- 📫 How to reach me ...
```

The HTML comment block at the bottom explains that this special repository's README appears on the GitHub profile.

> **Note on the filename**: GitHub renders `README.md` at the root of a special profile repository. The file here is named `README.md hidden eye` — the extra words after `.md` and the spaces mean GitHub may **not** auto-render this as the profile README. Do not rename or move this file without confirming its effect on profile display.

## Git History

```
7160ca6  Merge pull request #1 from Kaifisidhu/claude/add-claude-documentation-vpLAJ
7a1f26e  Add CLAUDE.md with codebase documentation for AI assistants
706d102  Create README.md hidden eye
```

- PR #1 (merged) added the initial `CLAUDE.md`.
- The initial commit created the profile README with the default template.

## Development Workflow

### Branches

| Branch | Role |
|--------|------|
| `main` | Default / production branch (what appears on the GitHub profile) |
| `claude/<description>-<id>` | Feature branches used for Claude-assisted changes |

Current active feature branch: `claude/add-claude-documentation-om9sz`

### Making Changes

1. Check out the appropriate feature branch (or create one following the naming pattern).
2. Edit `README.md hidden eye` to update profile content.
3. Commit with a descriptive message.
4. Push to the feature branch.

```bash
git checkout -b claude/<description>-<id>
git add "README.md hidden eye"
git commit -m "Update profile README: <what changed>"
git push -u origin claude/<description>-<id>
```

> Always **quote** the filename in shell commands because it contains spaces.

### No Build or Test Steps

There is nothing to build, lint, or test. Changes are validated by viewing the rendered Markdown on GitHub after merging to `main`.

### Merging

Changes reach the profile by merging a feature branch into `main` (via a pull request or direct push). Claude-assisted workflows typically go through a PR.

## Key Conventions

- **Filename caution**: `README.md hidden eye` is the committed filename. GitHub's profile README detection looks for exactly `README.md` — the extra text in the name may prevent automatic rendering. Verify after any change.
- **Markdown only**: All content is standard GitHub Flavored Markdown (GFM). Inline HTML is supported.
- **Profile-appropriate content**: This file is publicly visible. Keep content professional and accurate.
- **Emojis**: The existing template uses GitHub emoji shortcodes (`:wave:`) and Unicode emojis — both are conventional for profile READMEs.
- **No secrets**: This is a public repository. Never commit credentials, tokens, or private information.

## Common Tasks

| Task | Action |
|------|--------|
| Update bio/intro | Edit line 1 of `README.md hidden eye` |
| Add interests | Fill in the `👀 I'm interested in ...` placeholder |
| Update learning section | Fill in the `🌱 I'm currently learning ...` placeholder |
| Add collaboration info | Fill in the `💞️ I'm looking to collaborate on ...` placeholder |
| Add contact details | Fill in the `📫 How to reach me ...` placeholder |
| Add badges/stats | Insert GitHub badge Markdown (shields.io, github-readme-stats, etc.) |
| Add sections | Append new `##` headings with content |
| Update this file | Edit `CLAUDE.md` on a feature branch, then merge to `main` |

## Useful Badge Patterns

Common additions to GitHub profile READMEs:

```markdown
<!-- GitHub stats card -->
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=Kaifisidhu&show_icons=true)

<!-- Most used languages -->
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Kaifisidhu&layout=compact)

<!-- Shields.io badge example -->
![Twitter Follow](https://img.shields.io/twitter/follow/handle?style=social)
```
