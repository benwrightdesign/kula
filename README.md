# Kula website

Brand pass of the Kula website: a single-page site built to the Kula Visual Identity Guide 2026.

## What's here

| Path | What it is |
| --- | --- |
| `index.html` | The whole site: markup, styles and scripts in one file |
| `hero.jpg` | Homepage header photo (brand duotone), used as the video fallback |
| `hero-desktop.*`, `hero-mobile.*` | Homepage header video montage (MP4 + WebM), with `hero-poster*.jpg` stills |
| `logos/` | Partner logos (SVG) used in the ticker and case studies |
| `cases/` | Case study imagery |
| `favicon.svg` | Kula mark for the browser tab |

Pages are switched with the address hash: `#home`, `#work`, `#how`, `#about`, `#contact`, and case studies at `#case-bighams`, `#case-clays`, `#case-myclaim`.

## Viewing it

Open `index.html` in a browser, or publish with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Editing case studies

Case content lives in the `CASES` object inside `index.html`. Each case follows the same four chapters: The Kula Challenge, What we created, What worked, The Kula Effect. Text in square brackets is a placeholder still to be written.

## Fonts

Plus Jakarta Sans and Source Serif 4, loaded from Google Fonts.

## Creator sign-ups

The **Creators – Join us** button in the main navigation (and the footer link) opens a sign-up form. It isn't connected anywhere yet: submissions show a thank-you marked as a preview and are not sent.

To connect it, search `index.html` for `JOIN_ENDPOINT` and paste in a form endpoint URL (for example a Formspree form URL). The form then posts its fields there as JSON: `name`, `email`, `platform`, `handle`, `followers`, `niche`, `consent`.
