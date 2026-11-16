# Barber Demos — Z3BE

Three independent, unofficial HTML5/CSS3 website concepts for barbers and men's grooming businesses in Ras Al Khaimah. No JavaScript, build step, dependencies, forms, analytics, or data collection.

## Pages

| Shop | Source path | Expected URL after GitHub Pages is enabled |
| --- | --- | --- |
| Rani Gent’s Salon | shop-01/index.html | https://z3b-xs.github.io/barber-demos/shop-01/ |
| Salon XO | shop-02/index.html | https://z3b-xs.github.io/barber-demos/shop-02/ |
| Majesty Men Care Center | shop-03/index.html | https://z3b-xs.github.io/barber-demos/shop-03/ |

The root index is a collection directory. Each shop page is self-contained in its navigation and does not link to the other businesses.

## Preview

Open index.html directly, or open this folder in VS Code and use Live Server. Shared assets are relative paths and work under the repository subpath.

## Publish on GitHub Pages

Repository Settings → Pages → Build and deployment:
- Source: Deploy from a branch.
- Branch: main.
- Folder: / (root).
- Save.

Wait for GitHub's pages-build-deployment run to finish. The expected URLs above are not a deployment confirmation. No custom workflow or token is required. Subsequent pushes to main are published automatically once Pages is enabled.

## Structure

- index.html — collection directory.
- shop-01/index.html — Rani concept, dark green and brass.
- shop-02/index.html — XO concept, ivory and muted lime.
- shop-03/index.html — Majesty concept, olive and champagne.
- assets/style.css — shared responsive design, focus styles, reduced-motion support.
- assets/chair.svg — original decorative chair illustration; not a photograph of any shop.
- assets/favicon.svg — original collection favicon.
- 404.html — custom not-found page.
- robots.txt and robots meta — request exclusion from search indexing. This is not access control.
- .nojekyll — static publishing marker.

## Factual content and sources

Checked 2026-11-17. Public directory information may be outdated; owners must confirm it before any official launch. Service copy describes categories, not guaranteed availability. No ratings, testimonials, prices, business hours or claimed endorsements are displayed.

| Business | Displayed factual data | Public sources |
| --- | --- | --- |
| Rani Gent’s Salon | Khuzam Street, RAK; +971 50 750 0068; haircut/beard/hair-care categories | https://barberspot.net/en-ae/i/11466-rani-gents-salon/ ; https://salonist.io/cs/s/RaniGentssalon |
| Salon XO | Al Muntasir Road, opposite Centrepoint, Al Nakheel, RAK; haircut/styling/facial categories | https://salonist.io/cs/s/salonXO ; https://www.terno.io/discover/ar-ae/b/salon-xo-3585d11f |
| Majesty Men Care Center | 70 Khuzam Road, RAK; +971 50 133 0625; grooming/facial/relaxation categories | https://qr1.be/KO34 ; https://bestthings.ae/ras-al-khaimah/majesty-men-care-center/411277 |

XO's previously suggested telephone number could not be independently reverified, so the demo intentionally uses only a Maps search link. Rani and XO Maps links search by business name and area rather than pretending to be verified place IDs. Majesty's Maps and WhatsApp destinations come from its public link page.

## Design and usage

All pages prominently identify themselves as unofficial, independent concepts. Proposed typography, colors, wordmarks and promotional text are design proposals, not official brand assets. No shop photos, copied logos or third-party fonts are used. All vector assets were created for this project.

Call links open the phone dialer. The Majesty WhatsApp link opens its published contact destination. External links open a new tab with noopener and noreferrer. Neither action sends a message or creates a booking automatically.

## Validation

Source checks verify relative resource paths, internal fragment targets, exact three-shop mapping, document metadata, unique HTML IDs, no scripts/forms/placeholder links, and existence of the shared assets. CSS includes responsive layouts at 900px/640px, visible keyboard focus, touch targets, reduced-motion handling and bottom safe-area spacing.

Browser rendering and deployment must be checked separately; source checks alone do not prove visual rendering or live publication. Suggested manual checks: 360px/390px mobile, 768px tablet, 1440px desktop; keyboard navigation; FAQ expansion; call/Maps/WhatsApp destinations; deployment URLs.
