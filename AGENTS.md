# AGENTS.md

## Project Overview
- Static personal homepage intended for GitHub Pages.
- Single-page HTML with Tailwind CSS loaded from the CDN.

## Repo Layout
- `index.html` is the only page and owns all markup/styles.
- `CNAME` configures the custom domain and should not be modified unless requested.

## Development
- No build step, package manager, or tests.
- Preview by opening `index.html` in a browser or running `python3 -m http.server` from the repo.

## Conventions
- Prefer Tailwind utility classes; avoid adding new tooling or bundlers unless asked.
- Keep HTML semantic and accessible (headings, alt text, link labels).
- Keep content and links accurate; confirm before changing names or contact info.
- Add new images/assets to a clearly named folder (e.g., `assets/`) and update references.

## Visual / Style Constraints
- Maintain the current dark, minimal aesthetic with a centered card layout.
- Keep typography clean and readable; avoid adding extra fonts unless requested.
- Use the indigo accent for CTAs/links; keep color palette restrained.
- Avoid heavy animation; keep motion limited to simple hover/transition states.
- Ensure mobile layout remains single-column and scannable.

## Hosting / Deploy (GitHub Pages)
- Publish from the repository root; `index.html` must remain at the top level.
- Enable Pages in GitHub: Settings -> Pages -> Deploy from `main` branch, `/` root.
- `CNAME` controls the custom domain; update only when the domain changes.
- Commit changes to `main`; GitHub Pages will redeploy automatically.
