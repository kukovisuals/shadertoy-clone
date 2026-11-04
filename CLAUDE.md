# Rules

- Every line of code must have a purpose. If you can't say why a line is needed, don't write it.
- Write as little code as possible. Reuse existing code before adding anything new.
- Build only what was asked for. No extra features, files, pages, dependencies, or docs.
- CSS uses blue and white only.
- Use the existing fonts. Don't add or change a font unless asked.

# C4 diagrams

Diagrams use [LikeC4](https://likec4.dev). Everything lives in `doc/architecture/model.c4`.

Run from `doc/`:

- `npm install`
- `npm run dev` previews the diagrams
- `npm run validate` checks the model

A diagram request means editing `model.c4` and nothing else, unless asked otherwise.
