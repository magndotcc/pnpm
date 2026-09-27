---
"pacquet": patch
---

`pnpm install --frozen-lockfile false` turns frozen lockfile off again, and `--frozen-lockfile true` turns it on. pnpm 12 treated the extra word as a package name, switched the command to `pnpm add`, and rejected `--frozen-lockfile` [#14741](https://github.com/pnpm/pnpm/issues/14741).
