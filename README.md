# Nabbit Collections

The user interface for Nabbit's community resource index. Explore collections, locate a NABCODE, view a resource, or add a record. You're welcome to browse and open public links without an account.

We're beginning with the interface. There is no production backend here. Let's get the public pages correctly before the account and staff screens. The backend implementation will be in a separate repository and linked here once it exists.

## Stack

- HTML5
- CSS - with custom properties for shared colours, spacing and type
- Plain JavaScript using ES modules
- Vite for local development and builds</rool>
- npm, with a committed package-lock.json

No React, Next.js, Vue, Tailwind or component kit. Please ask before adding a framework or runtime dependency. Use system fonts.

1. Read [Contributing](CONTRIBUTING.md) and [Design rules](docs/DESIGN-RULES.md).  (THESE WILL BE WRITTEN)
2. Pick an unclaimed task from [Page order](docs/PAGE-ORDER.md). (THESE WILL BE WRITTEN)
3. Log an issue to follow the page or change you'd like to implement.
4. Have the layout checked out each time you build a page.

Work in this order: index → browse collection → detail → search and filters → contributor profiles → public pages accounts → submissions → staff screens. The full checklist and acceptance criteria are in Page order.

## Contributions

All contributions should be original writings by the contributor. Submissions of code, layouts, copy, assets or pull requests created or reworked using Codex, Claude, ChatGPT, Copilot, or any similar generative program will be disallowed. Including agent authored changes, generated scaffolding, AI autocomplete and lightly edited generated output. See the contribution policy.

Any submission that violates this rule will be closed. We will delete or revert generated material after merging. Do not post generated work under someone else's name or indicate that it was handwritten.

## Project notes

- [Page order and completion criteria](docs/PAGE-ORDER.md) (THESE WILL BE WRITTEN)
- [Frontend requirements](docs/FRONTEND-REQUIREMENTS.md) (THESE WILL BE WRITTEN)
- [Design rules](docs/DESIGN-RULES.md) (THESE WILL BE WRITTEN)
- [Backend boundary](docs/BACKEND-CONNECTION.md) (THESE WILL BE WRITTEN)
- [Existing route reference](docs/API-INVENTORY.md) (THESE WILL BE WRITTEN)
- [Security reporting](SECURITY.md) (THESE WILL BE WRITTEN)

All the files in reference/ and DESIGN-REFERENCE.md are meant for discussion. They are not a design you should follow or replicate.

## Licence

The code is licensed under [GNU AGPL v3.0](LICENSE).

Third-party assets retain their respective licences. The Nabbit name, logo and branding are not covered by the code licence.
