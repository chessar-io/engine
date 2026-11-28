# Working on the Chessar.io engine

For anyone, human or AI agent, changing this repository.

## Commands

| Purpose | Command |
|---|---|
| Install | `npm ci` |
| Full suite (typecheck + tests) | `npm test` |

Run `npm test` before every pull request.

## Rules

1. **Zero runtime dependencies.** `package.json` has no `dependencies` or `peerDependencies`; dev dependencies only.
2. **Rules of the game change only with the maintainers' approval.** Label such a pull request `rules`.
3. **Tests with every change.** A behaviour change comes with a test that fails without it.
4. **Public repository.** Commit messages, code comments and docs describe the engine only. Nothing about private infrastructure, business plans, people or internal tooling.
5. **Sign off your commits** (`git commit -s`, Developer Certificate of Origin).
