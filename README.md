# Starlight + astro-og-canvas

[![Built with Starlight](https://astro.badg.es/v2/built-with-starlight/tiny.svg)](https://starlight.astro.build)

## Issue

```
pnpm build
...
src/pages/og/[...route].ts:5:10 - warning ts(80007): 'await' has no effect on the type of this expression.

5   pages: await import.meta.glob("/src/content/docs/**/*.md", { eager: true }),
           ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
...
 building client (vite)
...
 generating static routes
...
__dirname is not defined in ES module scope
  Stack trace:
    at file:///astro-og-canvas-example/dist/chunks/prerender_UQoVfpFk.mjs:8106:43
 ELIFECYCLE  Command failed with exit code 1.
```
