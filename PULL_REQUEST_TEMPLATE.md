## What and why

<!-- One or two sentences. Link the issue if there is one: Closes #123 -->

## How to check it

<!-- Preview URL, steps, or the command to run. -->

## Flags

These follow the PR rules in the code and review standard (`docs/standards/code-and-review.md` in the private `lorien-documentation` repo). The standard is the authority on what each one means.

- [ ] CMS schema changed (say whether content needs migrating)
- [ ] Dependency or lockfile changed (intended, and explained below)
- [ ] Environment variable added (example file, runtime config, and host for Production and Preview)
- [ ] AI substantially shaped this change

## Checks

- [ ] Lint, typecheck, tests, and production build pass for what I changed
- [ ] Preview deployment checked
- [ ] Redirects added for any changed URLs
- [ ] No secrets, tokens, or `.env` values in the diff
- [ ] README or docs updated if behavior changed

### Accessibility (UI changes)

- [ ] Keyboard only: order makes sense, focus is visible, no traps
- [ ] Heading outline correct, one `h1`
- [ ] Content images have useful alt text, or are decorative
- [ ] Contrast checked for any new colors
- [ ] 200% and 400% zoom, and 320px width: nothing clipped, no horizontal scroll
- [ ] Not applicable (no UI change)

**What I tested:**

<!-- Be specific: tools, browsers, what you ran. Leave "accessible" out unless the project's accessibility record backs it up. -->

## Notes for the reviewer

<!-- Anything risky, unfinished, or worth a second look. -->
