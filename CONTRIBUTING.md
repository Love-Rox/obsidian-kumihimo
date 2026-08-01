# Contributing

This repository is generated, and everything in it is built from
[Love-Rox/kumihimo](https://github.com/Love-Rox/kumihimo) under `packages/obsidian` — where
the plugin lives beside the compiler it uses. It is mirrored here because Obsidian's
community directory reads `manifest.json` from the root of a repository, which a monorepo
cannot offer.

The source is here and it builds:

```sh
pnpm install
pnpm build
```

That produces the `main.js` attached to the matching release, from the compiler version
pinned in `package.json`.

Open issues and pull requests against the monorepo. Changes made here are overwritten by
the next release.
