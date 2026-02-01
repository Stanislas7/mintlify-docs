# Tide docs

This repository hosts the **Tide language documentation**, built with Mintlify.

- Language implementation: https://github.com/Stanislas7/tide
- Docs: this repo

## Local preview

Install the Mintlify CLI:

```bash
npm i -g mintlify
```

Run the dev server from the repo root (where `docs.json` lives):

```bash
mintlify dev
```

Then open: http://localhost:3000

## Structure

- `docs.json` — navigation + theme
- `index.mdx` — homepage
- `language/` — language tour
- `reference/` — CLI, built-ins, grammar/spec (draft)

## Contributing

Keep pages small and concrete. Tide is alpha — document what exists, and label drafts clearly.
