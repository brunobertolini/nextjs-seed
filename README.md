# NextJS Seed

This is my personal NextJS seed project, configured with:

- Jest + Testing Library
- ESLint (with some particular config)
- Prettier (with some particular config)
- TailwindCSS
- Storybook (working with Tailwind)
- Husky
  - Commit message validation with `commitlint`
  - Pre-commit running `lint-staged` to lint and format staged files
  - Pre-push running `yarn test` to guarantee quality
- Path aliases
  - `~` alias pointed to `./src`
  - `/` alias pointed to project root folder
