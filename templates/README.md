# Templates

Common shapes for files GitHub does not inherit from this repository. Copy
them into a project and fill them in.

| Template | Becomes | Notes |
|---|---|---|
| [`README.template.md`](README.template.md) | `README.md` | Fixed section order; delete the sections marked *(optional)* that do not apply |
| [`AGENTS.template.md`](AGENTS.template.md) | `AGENTS.md` | Instructions for AI coding agents. Add a `CLAUDE.md` containing `@AGENTS.md` so Claude Code reads it too |

## README rules

- Centered header: logo, name, a bold one-line promise, one supporting line,
  one row of badges.
- Badges use the palette: `090c0a` background, `1b231d` label, `b3bf3a` logo.
- The `[!IMPORTANT]` box states the project's boundary: what it does not do or
  prove.
- No emoji in headings.
- PostgreSQL projects use the elephant mark; everything else the ermine or its
  own mark.

## AGENTS.md rules

- Project-specific sections (*What this repository is*, *Hard rules*,
  *Layout*, *Conventions*, *Commands*) are written per repository.
- Blocks between `<!-- fyannk:shared:start NAME -->` and
  `<!-- fyannk:shared:end NAME -->` are identical in every repository. Edit
  them here first, then copy them to each project.
- Every hard rule names the test or script that enforces it.
