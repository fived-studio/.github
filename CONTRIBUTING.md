# Contributing to FiveD Studio

Thanks for taking the time to contribute. We're a small team shipping real products, and outside contributions help us move faster and ship better software.

This document is the **default contribution guide for every repo in the FiveD Studio organization**. Individual repos may add their own `CONTRIBUTING.md` that overrides specific sections — when in doubt, the repo's own guide wins.

---

## How we work

We follow a lightweight, founder‑mode process:

1. **Talk before you build.** For anything non‑trivial, open an issue or draft PR first — it's faster than rewriting after a wrong turn.
2. **Small PRs, fast review.** Aim for diffs under ~400 lines. Bigger changes should be staged.
3. **Trunk‑based development.** `main` is always shippable. Long‑lived branches are a smell.
4. **Tests are part of "done".** New behavior gets tests; bug fixes get a regression test.
5. **Ship the smallest thing that works.** Then iterate based on real signal.

---

## Ways to contribute

- 🐛 **Report bugs** via the bug report template
- 💡 **Suggest features** via the feature request template — please include the user problem, not just the solution
- 📝 **Improve docs** — fixing a confusing README is high‑leverage
- 🧪 **Add tests** for under‑covered code paths
- 🔧 **Send a PR** for an open issue (look for `good first issue` and `help wanted` labels)

---

## Development setup

Setup varies per project — see each repo's README for the canonical commands. As a baseline, most repos support:

```bash
# clone
git clone https://github.com/fived-studio/<repo>.git
cd <repo>

# install
make install        # or: pnpm install / npm install / mvn install / pip install -e .

# run tests
make test

# run locally
make dev
```

If `make` isn't there, the README will spell it out.

---

## Pull request checklist

Before opening a PR, please confirm:

- [ ] The change is scoped — one logical concern per PR
- [ ] Tests pass locally (`make test` or repo equivalent)
- [ ] New behavior has tests; bug fixes have regression tests
- [ ] Linter and formatter are clean
- [ ] Public APIs, env vars, and breaking changes are documented in the PR description
- [ ] Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/) (e.g., `feat: add ...`, `fix: prevent ...`)
- [ ] You've signed off on the [Code of Conduct](./CODE_OF_CONDUCT.md)

PRs are squash‑merged by default. We rewrite the merge title to match Conventional Commits if needed.

---

## Commit style

We use **Conventional Commits** because it makes changelogs almost free:

```
feat(checkout): support saved payment methods
fix(api): handle null user in /v1/me
chore(deps): bump zod to 3.23
docs(readme): clarify env var requirements
```

Allowed types: `feat`, `fix`, `chore`, `docs`, `refactor`, `perf`, `test`, `build`, `ci`, `revert`.

---

## Reporting security issues

**Do not open a public issue.** See [SECURITY.md](./SECURITY.md) for our private disclosure process.

---

## Questions?

- General questions → [SUPPORT.md](./SUPPORT.md)
- Found a bug → open an issue with the bug template
- Want to chat → reach out to a maintainer on the [org profile](https://github.com/fived-studio)

We read everything. Thanks for helping us ship.
