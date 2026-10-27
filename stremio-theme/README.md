# Stremio theme

An Apple TV–style, minimal redesign of [Stremio Web](https://github.com/Stremio/stremio-web), published at `haider.github.io/stremio`.

`apple-minimal.patch` is applied on top of the Stremio Web commit pinned in `.github/workflows/pages.yml`, then built and deployed with the rest of the site on every push to `main`.

What it changes:

- Black, frosted-glass look with the system (San Francisco) font
- Top tabs reduced to Home, Discover and Library; Add-ons and Settings are in the profile menu
- A rotating full-width banner on Home (swipe on phones, arrows on hover with a mouse)
- Posters that lift on hover instead of getting an outline; quieter titles and row headings
- An iOS-style tab bar on phones

To change the theme: clone Stremio Web at the pinned commit, `git apply` the patch, edit, then `git diff > apple-minimal.patch` (use `git add -N` first for new files).
