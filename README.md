# 38 Redwood Rd, Fairfax, CA 94930 — Listing Microsite

Static 4-page listing site (Home / Gallery / Details / Contact) for MLS# 326076344.
Plain HTML + CSS, no build step, served from the repo root.

**$849,000 · 2 bed · 1 bath · 1,168 sq ft · 4,948 sq ft lot · built 1962**

Open house: Saturday, September 19 & Sunday, September 20, 2026, 1:00–4:00 PM.

## Photos still needed

All listing copy is final. The 32 photo files are **not in the repo yet** — until they
are added, the Gallery page and the home-page hero render as broken images. See
`images/README.md` for the exact filenames the HTML expects.

## Contact form

`contact.html` posts to Formspree at `https://formspree.io/f/mqpakkla`. Send a test
inquiry after deploying to confirm the endpoint is verified and mail is arriving.

## Deploying to GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main`, folder: `/ (root)`.
`index.html` is the landing page. `.nojekyll` is present so nothing is filtered by Jekyll.

## Compliance (do not strip)

Every page footer carries: Nathan Irving, REALTOR® · DRE# 02414117 · Coldwell Banker
Realty, Greenbrae · Equal Housing Opportunity · "information deemed reliable but not
guaranteed." Verified present on all four pages.
