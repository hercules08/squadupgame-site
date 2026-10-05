# Squad Up public site

The current site lives in `src/`. It is a static site with no JavaScript trackers or
forms. The GitHub Pages workflow publishes only the current HTML, stylesheet, and
required images; the older LaunchKit sample files remain in the local workspace
for reference but are ignored by Git and are not deployed.

Public URLs:

- `https://squadupgame.com/`
- `https://squadupgame.com/privacy/` — use for Google Play and App Store Connect
- `https://squadupgame.com/support/`
- `https://squadupgame.com/terms/`

The domain must be configured as a custom domain in the repository's GitHub Pages
settings, with Cloudflare DNS pointed at GitHub Pages. The workflow deploys pushes
to `main`; do not update either store's policy URL until the live HTTPS page has
been checked from outside the development machine.

Before changing the mobile app's data practices or adding an SDK, review the
privacy policy and both stores' data disclosures together. The public contact is
`damola@swyftstudios.io`.
