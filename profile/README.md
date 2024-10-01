# void(0): Unified Toolchain for JavaScript

## Our Projects

- [Vite](https://github.com/vitejs/vite) - the build tool for the web
- [Vitest](https://github.com/vitest-dev/vitest) - Vite-native test runner
- [Rolldown](https://github.com/rolldown/rolldown) - The fastest bundler
- [Oxc](https://github.com/oxc-project/oxc) - The fastest language toolchain

## About

We are building the next-generation of toolchain for JavaScript that is:

- **Unified**: using the same AST, resolver, and module interop for all tasks (parsing, transforming, linting, formatting, bundling, minification, testing), eliminating inconsistencies and reducing redundant parsing costs.
- **High Performance**: written in a compile-to-native language, designed from the ground up for speed, with maximum parallelization and low-overhead JS plugin support. The performance budget unlocks more ambitious features that improve not only developer experience, but end user experience as well.
- **Composable**: each component of the toolchain is independently consumable, offering building blocks for advanced customization.
- **Runtime Agnostic**: not tied to any specific JavaScript runtime—delivering the same developer experience across all environments.

Read [the announcement blog post](https://voidzero.dev/posts/announcing-voidzero-inc) to learn more.
