# LearnTerms docs instructions

## About this project

- This repo powers the external LearnTerms documentation site on Mintlify.
- Pages are written in MDX with YAML frontmatter.
- Site configuration lives in `docs.json`.
- Run `npx mint dev` to preview locally.
- Run `npx mint broken-links` to validate internal links.

## Source material

- Prefer the LearnTerms app repo at `/Users/justindang/learnterms` as the source of truth.
- Existing in-app docs live under `/Users/justindang/learnterms/src/routes/docs`.
- Product workflows should match the current app UI and route structure.

## Terminology

- Use `cohort`, `class`, `module`, and `question` consistently.
- Prefer `study flow` over generic phrases like `learning experience`.
- Use `Content Library` and `Question Studio` as product names.
- Refer to LearnTerms generation models by their product-facing names.

## Style preferences

- Use active voice and second person.
- Keep sentences concise and concrete.
- Lead with the user goal or workflow.
- Bold UI labels and controls.
- Use code formatting for commands, paths, route segments, and config keys.

## Content boundaries

- Document shipped behavior first.
- Mark planned or migrating areas clearly instead of presenting them as complete.
- Do not copy Mintlify starter language unless it is specifically about the Mintlify toolchain.
