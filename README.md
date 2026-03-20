# LearnTerms Docs

This repository contains the external Mintlify documentation site for LearnTerms.

## Local preview

From the repository root:

```bash
npx mint dev
```

Then open `http://localhost:3000`.

If you prefer a global install:

```bash
npm i -g mint
mint dev
```

## Source of truth while migrating

Most product docs are still being migrated out of the app repo. Use these locations as references:

- `../learnterms/src/routes/docs`
- `../learnterms/src/routes`
- `../learnterms/README.md`

## Validation

Check internal links with:

```bash
npx mint broken-links
```
