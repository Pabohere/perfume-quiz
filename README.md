# Vela — Perfume Quiz

A polished, no-build-step fragrance discovery MVP. It runs entirely in the browser, remembers an in-progress quiz in the current session, and uses deterministic matching against a small, clearly defined development catalog.

## Run locally

Run the following in the project folder, then visit `http://localhost:3000`:

```powershell
npm start
```

No package installation is needed. You can also open `index.html` directly or use the VS Code Live Server extension.

## What’s included

- Nine-step accessible quiz with back navigation, session persistence, and multi-select deal-breakers.
- Transparent rule-based ranking that weights scent direction, opening, dry-down, exclusions, budget, and brand preference separately.
- Individualized result profile, five ranked recommendations, opening-to-dry-down analysis, cautions, and a copyable sample shortlist.
- Responsive editorial design with no runtime dependencies.

## Data note

The seven-fragrance catalog is sample MVP data. Verify every perfume’s notes, performance, pricing, and product links with authoritative sources before production use. The structure in `app.js` is intentionally easy to replace with a database/API-backed catalog when Laravel and a PHP runtime are available.

## Branches

`demo` is the working showcase branch. `prod` is created from the same tested implementation and is ready for deployment configuration.
