# AGENTS.md

## Project file purposes (one line each)
- `index.html`: Homepage with Yushinkai identity, hero content, and top-header navigation links.
- `training.html`: Training page with dojo notes, long-form philosophy narrative, contact form, and top-header navigation links.
- `styles.css`: Shared stylesheet for layout, typography, spacing, reusable UI components, and site-wide background treatment.
- `images/hero-bear-duel.svg`: Main hero concept illustration used on the homepage.
- `images/bg-dojo-texture.svg`: Background texture image used site-wide for atmosphere.
- `images/kendo-bogu-stock.svg`: Stock-style decorative kendo-themed local image.
- `images/naginata-stock.svg`: Stock-style decorative naginata-themed local image.
- `images/*`: Static visual assets (photos, icons, illustrations) referenced by HTML pages and documented with source credits.
- `README.md`: Public project overview, page map, local usage instructions, and asset attribution.
- `CLAUDE.md`: Contributor/agent workflow reference aligned to this repository's coding and process conventions.
- `AGENTS.md`: Agent-facing instructions, file purpose index, and required development conventions.
- `.gitkeep`: Placeholder file to keep the repository tracked while content is minimal.

## Coding conventions
- Prefer semantic HTML (`header`, `main`, `section`, `nav`, `footer`) and meaningful heading hierarchy.
- Keep styling centralized in `styles.css`; avoid inline styles unless absolutely necessary.
- Reuse existing classes/utilities before adding new CSS rules to prevent duplication.
- Keep files concise; when a file approaches or exceeds ~400 lines, split by responsibility.

## Process conventions
- Update `AGENTS.md`, `README.md`, and `CLAUDE.md` whenever structure, workflow, or conventions change.
- Before adding new logic/styles, check whether similar code already exists and extract shared utilities/components.
- Document any third-party assets (source + license) in `README.md` under Asset Credits.
- If a file exceeds ~400 lines, add a refactor follow-up note to `README.md` and `CLAUDE.md`.
