# Contributing

## Setup

```bash
pnpm install --ignore-workspace
pnpm dev          # Astro dev server at localhost:4321
```

Requires Node ≥ 22.12 and pnpm ≥ 10.

## Build

```bash
pnpm build        # outputs to dist/
```

## Tests

```bash
pnpm test         # vitest unit tests (src/__tests__/)
pnpm test:e2e     # playwright e2e (tests/e2e/) — requires a running dev/preview server
```

## Code style

Biome handles formatting and linting (`@biomejs/biome`). Before committing:

```bash
pnpm exec biome check --write .
```

## Branch / PR conventions

- Commit direct to `main` for small fixes.
- For larger changes open a PR from a short-lived branch (`fix/…`, `feat/…`).
- Conventional commits: `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`.
- One logical change per PR; keep diffs small.

## Data

Medicine data lives in `data/` and is refreshed daily by the `scrape` workflow. Do not manually edit generated JSON files.
