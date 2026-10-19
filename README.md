# NONONICK — Digital Systems Studio

A Persian, RTL-first dashboard for the NONONICK project collection. The home page uses a responsive desktop sidebar and a mobile bottom dock, with standalone HTML experiences organized under `apps/`.

## Open the site

- Main dashboard: `index.html`
- NonoMail AI: `apps/nomomail.html`
- iOS-inspired portfolio: `apps/ios-portfolio.html`
- Digital studio: `apps/digital-studio.html`
- Universal AI editor: `apps/ai-editor.html`
- Futuristic portfolio: `apps/futuristic-portfolio.html`
- Engineering portfolio: `apps/portfolio.html`
- NONONICK Studio: `apps/nononick-studio.html`
- TaskMate: `apps/taskmate.html`

## Run locally

Open `index.html` in a modern browser. Most pages are self-contained HTML; experiences that use external libraries or fonts need an internet connection for those resources.

## GitHub Pages

A deployment workflow is included in `.github/workflows/pages.yml`. In the repository settings, choose **Settings → Pages → Build and deployment → Source: GitHub Actions** if Pages is not already configured. The workflow then publishes the repository's static files from the default branch.

## Adding an app

1. Add the standalone HTML file under `apps/`.
2. Add a matching card/link in `index.html`.
3. Keep relative links working from the `apps/` directory and test the page on mobile.

## Notes

The HTML demos are published as separate pages; source archives for unrelated Vite/backend projects are not unpacked into this static site. Deploy those projects separately when their runtime, dependencies, and environment variables are ready.
