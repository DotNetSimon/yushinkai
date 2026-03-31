# CLAUDE.md

## Contributor / agent workflow
1. Read `AGENTS.md` before making changes.
2. Reuse existing structures/utilities before introducing duplicate markup or CSS.
3. Keep changes scoped and files short; prefer small, composable sections.
4. After each change, update `AGENTS.md`, `README.md`, and `CLAUDE.md` if conventions or structure changed.
5. Document new/updated image assets in `README.md` Asset Credits.

## Project conventions alignment
- `index.html`: Landing page with clear top-level navigation and semantic structure.
- `training.html`: Training-specific content page, linked from `index.html`.
- `styles.css`: Shared style definitions; avoid inline overrides when possible.
- `images/*`: Store only web-ready optimized assets; keep names descriptive and kebab-case.

## Quality checks before commit
- Confirm internal links between `index.html` and `training.html` are valid.
- Confirm pages render with shared styles from `styles.css`.
- Confirm docs (`AGENTS.md`, `README.md`, `CLAUDE.md`) reflect current structure.

## Refactor follow-up note (400+ line rule)
If any file exceeds ~400 lines, add a follow-up task in docs and split by responsibility:
- Break large HTML into smaller template/component units when tooling permits.
- Split large CSS into modular partials (base, layout, components, utilities).
