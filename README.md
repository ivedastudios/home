# IVEDA AI — responsive website prototype

**Status:** Working static website; not published. Project cards contain conceptual CSS artwork, not finished film imagery. Includes functional mobile navigation, anchor links, favicon and responsive layout. Contact currently goes to https://www.iveda3d.com/ until you supply a dedicated email address. No contact form/backend or video hosting is included.

## View locally
Open `index.html` in a browser.

## Publish to Cloudflare Pages using GitHub
1. Create a GitHub repository such as `iveda-ai-site`. Upload `index.html` and `favicon.svg` to the repository root.
2. In the Cloudflare dashboard, open **Workers & Pages** → **Create** → **Pages** → connect to GitHub and select this repository.
3. Set the production branch to `main`. Select no framework, leave the build command empty, and select the repository root as the output directory (`/`). For workflows that require a build command, use `exit 0`.
4. Deploy. Cloudflare will supply a preview URL ending in `pages.dev`.
5. In Pages → your project → Custom domains, add your purchased domain and complete the displayed DNS instructions. A domain purchased from Cloudflare automatically uses Cloudflare DNS.
6. Future pushes to the repository will trigger new deployments. Review changes before publishing.

## Replace before public launch
- Insert real film stills / video embeds / reel links.
- Replace the temporary IVEDA3D contact link with a verified working studio email or contact form.
- Confirm project names, credits and the exact business/legal brand.
- Obtain permissions for all music, imagery and film materials before publishing.
- Add privacy/cookie policies if required by your audience and your actual tracking/tools.

## Notes
The studio site uses standard HTML/CSS/JS, not a locked-in website builder. The font falls back gracefully when Google Fonts are unavailable. The site is designed to work without bundling heavy video files: host films on a suitable streaming/video provider, embed them or link to them here.
