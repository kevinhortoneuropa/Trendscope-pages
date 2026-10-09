# Trendscope — public pages

The homepage and privacy policy that Google's OAuth consent screen links to.

Trendscope itself is a local application and lives in a separate repository;
nothing here is part of it. These two files exist only because Google requires
a public homepage URL and a public privacy policy URL before an OAuth app can
be switched from Testing to In production.

- `index.html`   — what the app is, and what it does with Google data
- `privacy.html` — how Google user data is handled (locally, and not shared)

Served by GitHub Pages from the `main` branch, root folder.
