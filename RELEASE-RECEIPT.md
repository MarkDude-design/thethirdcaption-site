# The Third Caption — public-site technical release receipt

**Scope:** Thin public preview only, 2026-11-10 PT.

Source: `art-talk` private experiment branch `experiment/meraki-third-caption-site-20261110` at `website/prototypes/the-third-caption/index.html`; original CSS-only design written by Meraki. Reviewed to contain no private transcripts, no credentials, no embeds, no user tracking, and explicit independent Woodall attribution.

Cloudflare Workers Builds project: `thethirdcaption-site`; linked GitHub repository: `MarkDude-design/thethirdcaption-site`; production branch `main`. Initial repo had only `README.md`; its first automatic build failed. This commit supplies `public/index.html` and `wrangler.toml` with Worker Static Assets. Static assets need no server script, package framework, or compiled bundle. Workers Builds deploy command should be the default `npx wrangler deploy`; build command should be empty.

**Preview safety:** `<meta name="robots" content="noindex,nofollow">` until owner/curator approves wider launch. All artwork on this page is original HTML/CSS geometry. No copied Woodall transcript, external photos, source vault files, secrets or analytics. Public web preview IS publishable but does not imply that the rest of the private art archive is approved. Turn off noindex in a separate, reviewed launch commit when ready.

**Status at commit time:** public GitHub source was committed; Cloudflare build success, actual workers.dev endpoint response, browser/phone checks and `thethirdcaption.art` DNS/HTTPS are **NOT VERIFIED**. The active Cloudflare project has a separate Workers URL; custom domain was not attached here. No other Workers or domain zones changed.

Cloudflare official docs: https://developers.cloudflare.com/workers/static-assets/binding/ and https://developers.cloudflare.com/workers/ci-cd/builds/configuration/

## Study Wall addition — 2026-11-11 PT

An owner-authorized, reversible site iteration adds **/gallery/**: twelve **Meraki-authored procedural SVG study images** 001–012, each as a separately downloadable/openable vector asset in `public/gallery/works/`. The wall shows everything on one page with optional, honest process labels, stable numbers and no tracking, login, external embeds, model API calls or data collection. New gallery page carries `noindex,nofollow`; root page's `noindex,nofollow` is preserved. This is **not** an import of other Circle seats' drafts, private transcript or uncleared images; treat these as first-party sketch experiments only. Home page receives two unobtrusive gallery links. Code/source checks after commit must be reported separately; Cloudflare auto-deploy/browser acceptance cannot be inferred from GitHub commit alone.
