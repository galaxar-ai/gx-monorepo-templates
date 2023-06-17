# Galaxar monorepo template

Currently only suppports pnpm.

## Repo structure

- apps - For application projects
- packages - For library packages  

## Change log and bumping new versions

Add changelog
```
pnpm changeset
```

Bump version
```
pnpm bump
```

## Repo commands

- `pnpm build`: build all projects
- `pnpm lint`: run linter for all projects
- `pnpm lint-fix`: run linter with auto-fix for all projects
- `pnpm prettier`: run prettier for all projects
- `pnpm test`: run test for all projects
- `pnpm cover`: run code coverage test for all projects
- `pnpm release-all`: publish all projects