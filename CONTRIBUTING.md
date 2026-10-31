# Contributing

Pick a small piece of work you can finish and explain.

## Before starting

Review page order, open an issue, read an issue, look at open pull requests. If you're thinking of creating a new page, changing an existing layout, or adding a dependency, open an issue; provide a description of your changes and the reasoning behind them, along with sketches or screenshots when appropriate. Get a maintainer to agree on the scope before doing a substantial rewrite.

Do not mix a page redesign with unrelated formatting, renamed files and dependency updates.

## No AI-generated contributions

Don't write code in Codex, Claude, ChatGPT, GitHub Copilot or other generators, rewrites or tools. This applies to source code, CSS, markup, UI designs, prose, translations, images, tests, commit messages and pull request descriptions. This includes agent mode and generated scaffolding. Simply pasting a generation and replacing a handful of things isn't creating the contribution yourself.

You must understand and be able to explain everything you submit. Do not submit work for someone else to conceal its origin.

AI-generated submissions will be closed without merging. Material discovered after a merge will be removed or reverted. Repeated attempts or a deliberately false declaration may result in a contribution ban.

A style somebody dislikes is not proof that a tool was used. Maintainers may ask questions about a contribution; do not accuse or harass other contributors. Do not upload private files, conversations or personal records to prove authorship.

Formatters, linters, compilers, test runners, ordinary non-generative editor completion and documentation search are fine.

## Frontend work only

Use sample data behind a replaceable service adapter.

Do not remove a required page because its backend is unavailable. Build its loading, success, empty and failure states with fixtures.

## Code and files

Use semantic HTML, shared CSS variables and small JavaScript modules. Keep navigation usable without decorative assets. Handle user text as text, not raw HTML.

Do not add explanatory comments to first-party browser-delivered code. Put explanations in documentation and use clear names. Preserve required copyright and licence notices.

Use kebab-case file names. Keep generated output, node_modules, editor files and local build caches out of Git. Avoid adding dependencies for a small helper you can reasonably write and maintain.

## Check your work

Test desktops and phones widths, keyboard navigation, long content, missing images and error states. Screenshots of the page you changed. If you haven't tested a feature, note it. Don't say "fully tested" when you only opened the homepage!

## Pull requests

Explain the problem, what you changed, how to try it and what you tested. Include before/after screenshots for UI changes and please link the issue. Mention unfinished work and new dependencies. Complete the authorship declaration in the template honestly.

A maintainer must approve the change.

