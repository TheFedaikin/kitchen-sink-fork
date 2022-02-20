# This is a fork of `turborepo` kitchen sink starter: [Original](https://github.com/vercel/turborepo/tree/main/examples/kitchen-sink). This is hand-tailored to simplify live-coding demo with a Turborepo and publishing showcase

This is an official Yarn v1 starter Turborepo with multiple meta-frameworks all working in harmony and sharing packages.

## What's inside?

This Turborepo includes the following packages and apps:

### Apps and Packages

- `api`: an [Express](https://expressjs.com/) server
- `storefront`: a [Next.js](https://nextjs.org) app
- `admin`: a [Vite](https://vitejs.dev/) single page app
- `blog`: a [Remix](https://remix.run/) blog
- `logger`: isomorphic logger (a small wrapper around console.log)
- `@d/ui`: a dummy React UI library (which contains a single `<CounterButton>` component)
- `scripts`: Jest and eslint configurations
- `tsconfig`: tsconfig.json;s used throughout the monorepo

Each package and app is 100% [Typescript](https://www.typescriptlang.org/).

### Utilities

This turborepo has some additional tools already setup for you:

- [Typescript](https://www.typescriptlang.org/) for static type checking
- [ESLint](https://eslint.org/) for code linting
- [Jest](https://jestjs.io) test runner for all things JavaScript
- [Prettier](https://prettier.io) for code formatting
