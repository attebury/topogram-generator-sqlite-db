# Topogram Generator: sqlite

Package-backed Topogram generator for SQLite database lifecycle bundles.

## Manifest

- Generator id: `@attebury/topogram-generator-sqlite-db`
- Surface: `database`
- Projection platform: `db_sqlite`
- Package manifest: `topogram-generator.json`
- Adapter export: `index.cjs`

## Verify Locally

```bash
npm run check
```

The smoke test packs this generator, installs it beside `@attebury/topogram` in a temporary consumer project, runs `topogram check`, runs `topogram generate`, and verifies expected generated files.
