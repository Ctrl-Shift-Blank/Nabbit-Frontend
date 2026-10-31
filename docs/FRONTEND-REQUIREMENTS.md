# Product and direction

Nabbit Collections is a community-maintained catalogue of resources: games, software, archives, websites, documentation and tools. A collection has a six-digit NABCODE, often displayed as 123-456.

## Required public screens

- Browse/search index: title, concise description, category, NABCODE, contributor; category navigation, sort, filters, pagination and direct code lookup.
- Collection detail: readable description, primary external resource action, mirrors if present, metadata, contributor, tags, screenshots/proof, relationships and edit history. Real artwork only when available. External links clearly identified.
- Contributor profile: name/avatar/banner/bio, roles and achievements, contribution list. Personality is welcome; osu! profiles are an influence! feel free to use that as a reffrance
- Contributor leaderboard, achievements catalogue, help/NABCODE guide, terms/privacy/copyright reporting. (this feature was about of the nabbit collection site that was shutdown, we do need guide and terms. contributor leadboard achievements are not needed_
- Sign in/register, submission form and submission status/history. Browsing and opening public resource links must NOT require an account.
- Notification list and own-profile edit including avatar/banner crop, remove, preview, save and cancel.(might not be used if we make this non accont based)
- Staff UI designs: moderation queue and submission review, verification, maintainer applications, users/roles, broken links, audit, analytics, import/export, announcements/maintenance. 
- 403/404/500, maintenance, suspended, missing collection and signed-out states.

## Behaviours

Search submits deliberately; do not hammer an API on every keystroke. Preserve filter/sort/page state in URLs. Long titles, codes and URLs wrap correctly. Missing artwork/avatar/banner and zero collections look deliberate. Images must not replace essential labels. Show a readable fallback if media fails to load. (API HANDLING WILL BE HANDLED IN BACK END IF ANYTHING)

## Completion gate

Review at 320, 375/390, 768, 1024 and 1280+ CSS px. No horizontal page overflow. Verify keyboard/focus, touch controls, dialog/drawer close and focus return, 200% zoom, dark/light and reduced motion. Test empty/loading/error/401/403/429/503 states. Show the owner screenshots and working preview.
