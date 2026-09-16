# 38 Redwood — Listing Microsite

Static 4-page listing site (Home / Gallery / Details / Contact). Plain HTML + CSS, no build step.

## Status: scaffold — listing facts still needed

Every spot that needs real information is marked `[NEED: ...]` in the HTML. Find them all with:

```
grep -rn "\[NEED" .
```

Still to fill in:

- Full street address (suffix, city, ZIP) — used in page titles, headings, and the map
- List price, beds, baths, square footage, lot size, year built, property type
- MLS #
- 4 highlight bullets and the long-form description
- Hero tagline
- Neighborhood name + blurb
- Open house date(s)/time(s) and showing instructions
- Agent phone and email (name and DRE# are already set)
- Google Maps embed URL (`details.html`, iframe is commented out until the address is confirmed)
- Formspree endpoint — `contact.html` form `action` is `[FORMSPREE_ENDPOINT]`; the form will not
  send until a real endpoint from formspree.io is dropped in

## Photos

Drop files in `images/` using the names already referenced in `gallery.html`
(`01-exterior-front.jpg`, `02-kitchen.jpg`, ...). Each slot currently renders a dashed
placeholder box; swap the placeholder `<div>` for the commented-out `<img>` tag above it.

## Deploying to GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → Branch: `main` (or this branch) / root.
The site is served from the repo root, so `index.html` is the landing page.

## Compliance (do not strip)

Every page footer carries: Nathan Irving, REALTOR® · DRE# 02414117 · Coldwell Banker Realty,
Greenbrae · Equal Housing Opportunity · "information deemed reliable but not guaranteed."
