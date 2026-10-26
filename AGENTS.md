# openscout-app organization profile

This repository holds the public profile of the `openscout-app` GitHub
organization and the brand assets that the integration repositories share. It
is public. [README.md](README.md) lists each asset and what owns it.

| Path | Holds |
| --- | --- |
| `profile/README.md` | The organization home page |
| `profile/assets/` | The profile hero images and the social card art |
| `assets/` | The avatar, brand tokens, lockups, illustrations, and the Pages stylesheet |
| `illustrations/` | The illustration generator, the platform marks, and the gallery |
| `scripts/` | Asset rendering and the profile check |
| `ORG_METADATA.md` | The recommended organization fields |

## Rules

- The profile loads its images from `raw.githubusercontent.com` URLs on
  `main`. Rename or move an image only in the same change as the README that
  loads it.
- `assets/pages/scout-pages.css` is the source of the Pages stylesheet. Each
  integration repository keeps a byte-identical copy in `docs/assets/`. Edit
  it here, then copy it.
- Profile copy follows the openscout.app site. Do not write "pilot" or
  "coming soon", and do not invent numbers.
- Scout is for high-trust local developer use. Do not claim enterprise,
  compliance, or multi-tenant readiness.
- This repository is public. Do not commit local paths, host names,
  credentials, or private source.

## Checks

- `bun install` once, then `bun run check`.
- After you change an art source: `bun run assets:render` and
  `bun run illustrations:render`.

## Commits and pull requests

- Commit subjects use gitmoji: `💄 Refresh the profile hero`.
- Do not add AI co-author trailers or "Generated with" lines.
- Push a branch to `openscout-app/.github` and open a pull request into
  `main`.

<!-- scout:begin -->
## Scout

- Work for another agent, or on another machine, goes through Scout: `scout ask` (MCP `ask`).
- Another machine: `scout ask --on <host> --project <path on that host> --harness <claude|codex>`; `scout hosts` lists machines and their projects. Don't ssh in to launch agents.
- Syntax: `scout ask --help`, `scout help --detail`. Added by `scout setup agents-md`; `scout setup agents-md --remove` takes it out.
<!-- scout:end -->
