# Contributing

This file covers GitHub conventions shared across Lorien Web repositories. Most repos in this org are private client work, and my internal procedures are kept separately.

## Outside contributions

I'm not accepting outside pull requests yet. If I open a repo to contributors, it will get its own CONTRIBUTING file that replaces this one.

You can open an issue on a public repo if you find a bug. I read them, but I can't promise a timeline.

## Conventions

- **Issues:** use the templates when you file one.
- **Branches:** branch from an up-to-date `main` and name it `type/short-topic`, like `fix/footer-link-label` or `feat/events-page`.
- **Commits:** short, imperative, and typed: `fix(a11y): ...`, `feat: ...`, `docs: ...`.
- **Pull requests:** one purpose per PR. Fill in the template, including the accessibility checklist for UI changes, and check the preview deployment before asking for review.
- **Accessibility claims:** record what you tested in the PR. Don't write "accessible" or "compliant" in a PR, commit, or client-facing copy unless the project's accessibility record backs it up.
- **Secrets:** never commit secrets, tokens, or `.env` files.
