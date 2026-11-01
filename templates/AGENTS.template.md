<!--
fyannk AGENTS.md template v1 — copy to AGENTS.md and fill every {{…}}.
Sections between "fyannk:shared" markers are identical across repos:
change them in fyannk/.github/templates first, then copy them everywhere.
Add a CLAUDE.md next to it containing the single line:  @AGENTS.md
-->

# AGENTS.md — {{Project}}

Instructions for AI coding agents working in this repository. These rules apply
to the entire repository unless a more specific `AGENTS.md` exists below the
path being changed.

## What this repository is

{{Two or three sentences: what the project does, what it deliberately does not
do, and where it runs. Name the one boundary that must never be crossed.}}

<!-- fyannk:shared:start code-is-truth -->
## The code is the truth

The code and its tests define what this project does. Nothing else does.

- Behavioral authority, in order: the code, then the tests beside it.
- Documentation **explains** that truth for humans; it is never a
  specification. If the docs and the code disagree, the code is right and the
  page is a bug: fix the page.
- Never change code to match a sentence in the docs. If behavior is wrong,
  say so and change it deliberately, with its tests.
- Do not create design, spec, plan, or contract documents. A rule that must be
  normative for contributors belongs in this file; a fact a reader needs
  belongs in the docs.
- A behavior change updates the code, its tests, and the affected docs in the
  same change.
<!-- fyannk:shared:end code-is-truth -->

## Family context (optional)

{{Sibling repositories and how they relate. They are read-only references:
never modify them from this repository.}}

| Repository | Role | Local path |
|---|---|---|
| {{repo}} | {{role}} | `{{~/projects/perso/…}}` |

## Hard rules

Violating any of these is a bug. Each one is enforced by a test or a check.

1. **{{Rule}}**: {{one sentence}}. Enforced by `{{test or script}}`.
2. **{{Rule}}**: {{one sentence}}. Enforced by `{{test or script}}`.

## Layout

| Path | Owns |
|---|---|
| `{{cmd/}}` | {{entry points}} |
| `{{internal/…}}` | {{responsibility}} |
| `{{web/}}` | {{docs site / UI}} |

## Conventions

- **Language**: {{Go 1.26, standard library first, …}}
- **Naming**: {{settled names to use exactly}}
- **Errors and logging**: {{rules}}
- **UI** (optional): follow the fyannk design system (dark-first tokens,
  IBM Plex Mono/Sans, one accent, status = color + glyph + word).

## Commands and verification

| Command | What it proves |
|---|---|
| `{{make check}}` | {{build, unit tests, lint, structural checks}} |
| `{{make test-integration}}` | {{…}} |
| `{{make docs}}` | {{docs build}} |

Run `{{make check}}` before declaring any change done. If a check cannot run
locally, say so explicitly rather than claiming success.

<!-- fyannk:shared:start change-discipline -->
## Change discipline

- Work in small vertical slices: one behavior, its tests, its docs.
- Atomic commits, imperative mood, first line under about 72 characters; the
  body explains *why*.
- Never add AI attribution to commits or pull requests (no
  `Co-Authored-By` trailers for agents, no "generated with" lines).
- Never commit secrets, tokens, kubeconfigs, or customer data.
- Do not push, tag, release, or force-push unless explicitly asked.
<!-- fyannk:shared:end change-discipline -->

<!-- fyannk:shared:start handoff -->
## Handoff

When you finish, report:

- what changed and why, file by file if it is not obvious;
- which commands you ran and their result;
- what you could not verify, and what is left to do.
<!-- fyannk:shared:end handoff -->
