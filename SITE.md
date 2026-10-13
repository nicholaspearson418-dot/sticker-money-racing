# Sticker Money Racing site: build contract

Static site for GitHub Pages (repo nicholaspearson418-dot/sticker-money-racing, served from the repo root of `main`).
Plain HTML/CSS/vanilla JS. No build step, no frameworks, no CDNs except Google Fonts. All links RELATIVE (the site lives under /sticker-money-racing/).

## Team
Sticker Money Racing races in **Radical** (sports prototypes) and **GT4**. Colours: black, purple, chrome.
Facts not given by Nick (drivers, results, specs, series names, dates, sponsors) are written as `[TBD]`, never invented.

## Files
| path | owner |
|---|---|
| assets/css/style.css | smrstyle |
| assets/js/main.js | smrstyle (mobile nav toggle, small effects) |
| assets/img/placeholder-*.svg, logo-placeholder.svg | smrstyle |
| index.html, _template.html | smrstyle |
| content/*.md (home, team, cars, results, sponsors, join, contact) | smrcopy |
| team.html cars.html results.html sponsors.html join.html contact.html | smrpages (phase 2, from _template.html + content/*.md) |

## Pages and nav order
Home (index.html) · Team · Cars · Results · Sponsors · Join · Contact

## Design tokens (style.css :root)
--black #0a0a0c, --panel #141418, --purple #7b2cff, --purple-deep #4b1599, --chrome gradient silvers (#f4f4f6 -> #9a9aa3 -> #e6e6ea),
--text #ececf1, --muted #9a9aa8. Racing feel: angled/skewed section edges, thin purple speed stripes, subtle checkered motif.
Images: real photos arrive later; until then use the placeholder SVGs and put `data-todo="photo: <what>"` on each <img>.
