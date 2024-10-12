# jumpgen-fdir

A fork of [fdir](https://github.com/thecodrr/fdir) with an added ESM entry point. This is necessary to ensure `node:fs` can be mocked by Vitest while testing Jumpgen generators.

This package doesn't get published to NPM. It gets bundled with Jumpgen.
