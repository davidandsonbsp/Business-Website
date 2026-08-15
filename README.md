# David & Sons Barbershop — Website

A fast, mobile-first, single-page site for **David & Sons Barbershop**, 1025 Cortelyou Rd,
Ditmas Park, Brooklyn. No build step — it's one self-contained `index.html`.

## View it
- Double-click `index.html`, or drag it into any browser.
- To host: upload `index.html` to any static host (Netlify drop, Cloudflare Pages,
  GitHub Pages, Vercel). No server needed.

## Design
Modern-heritage: warm cream + ink + barber-red accent, Fraunces (headlines) + Inter (UI).
The red "&" in "David **&** Sons" is the brand mark — no barber-pole cliché. Full
rationale in [docs/business-facts.md](docs/business-facts.md) and the competitor work in
[docs/](docs/).

## Before launch — swap in the reals (search `TODO` in index.html)
- [ ] **Booking links** — David's **theCut** profile URL (primary) + **Booksy** URL.
      Replace every `data-book` `href` and the two booking buttons.
- [ ] **Phone** — replace the `(000) 000-0000` placeholders.
- [ ] **Hours** — confirm the real hours in the Visit section (currently marked "confirm").
- [ ] **Photos** — replace the dark `.ph` placeholders: hero portrait of David (4:5),
      a family/kids-cut photo (5:4), David's portrait, and 4 portfolio shots.
- [ ] **Reviews** — replace the 3 placeholder testimonials with **real** Google/Booksy
      reviews. Don't publish a star rating until it's a real one.
- [ ] **Instagram** — real handle in the footer.
- [ ] **"& Sons"** — if other/family barbers cut here, add cards in the `#team` section.

## Pricing note for David
The printed "Regular Cut + Eyebrows = $30" combo is identical to buying them separately
($25 + $5), so it isn't really a deal — it's left off the site for clarity. The genuine
value, **cut + beard + eyebrows for $30**, is featured as "The Full Service." Worth
deciding whether to reprint the in-shop list to match.

## Project files
- `index.html` — the website (self-contained).
- `favicon.svg` — the "&" brand mark (also export to PNG for the Google logo/social avatar).
- `robots.txt`, `sitemap.xml` — hosting/SEO (set the real domain before submitting to Google).
- `docs/` — the strategy: [reference teardown](docs/reference-teardown-georges-barbershop.md),
  [1-mile competitor field](docs/competitor-field-1mile.md),
  [business facts & brand brief](docs/business-facts.md),
  [local SEO & Google plan](docs/local-seo-plan.md).

## Done this round
- ✅ `HairSalon` structured data (JSON-LD) with address, geo, hours, and all 9 services + prices.
- ✅ SEO meta (title, description, canonical, geo, Open Graph/Twitter) + `favicon.svg` brand mark.
- ✅ Local-search playbook — see [docs/local-seo-plan.md](docs/local-seo-plan.md).

## Still to do (needs owner input / next phases)
- Set the **real domain** in: canonical + OG tags + JSON-LD (`index.html`), `robots.txt`, `sitemap.xml`.
- Add a real **og-image.jpg** (1200×630) for link previews.
- **Google Business Profile** setup + review drive (full steps in the local SEO plan).
- **Client re-connection** campaign (bring David's following over) — pending non-compete check.
