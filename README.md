# NextJS Starter

A pnpm project creating a nice base-ground on which to develop [nextjs](https://nextjs.org/) projects with dev tooling backed in from day 1.

## Tech

- Package Manager: [pnpm](https://pnpm.io/)
- Language: [JS/TypeScript](https://www.typescriptlang.org/)
- NextJS: [15](https://nextjs.org/blog/next-15-rc)
- React: [19](https://react.dev/blog/2024/04/25/react-19)
- Linting: [Prettier](https://prettier.io/), [ESLint](https://eslint.org/),
- GitHooks: [Husky](https://typicode.github.io/husky/) & [LintStaged](https://github.com/lint-staged/lint-staged)
- Build: [Turbo](https://nextjs.org/docs/architecture/turbopack)
- Env: [t3-env](https://github.com/t3-oss/t3-env)
- Schema validation: [zod](https://zod.dev/)
- Styles: [Tailwind CSS](https://tailwindcss.com/)

## Usage

Each of the commands can be run using `pnpm` followed by the command keyword eg. `pnpm dev`

- `dev`: Start the nextjs server in dev mode with hotreloading.
- `build`: Build the application optimised for production
- `start`: Start the production build.
- `lint`: Using the linting rules check the app.
- `prettier:format`: Automatically fix any linting issues in the project using prettier.
- `prettier:check`: Report on issues with the apps linting.
- `eslint:format`: Automatically fix any linting issues in the project using eslint.
- `test`: Run app tests in full browser mode.
- `test:ci`: Run the app tests in a headless mode.
- `test:coverage`: Build a coverage report.
- `test:watch`: Retest on file change.
- `postinstall`: NPM install hook to configure husky git hooks.
- `prepare`: NPM hook to run husky scripts on publishing NPM actions.
