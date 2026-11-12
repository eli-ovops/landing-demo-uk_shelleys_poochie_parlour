# Local Demo QA — Shelley’s Poochie Parlour

Status: `LOCAL QA PASS; DENSE-CONTENT INDEPENDENT REVIEW PASS; USER VISUAL ACCEPTANCE PENDING`. This is not deployment, public-link, outreach, customer or final-source-transfer evidence.

## Render evidence

| Check | Evidence | Result |
| --- | --- | --- |
| Desktop | `qa/screenshots/desktop-1440x900-final-content.png`; `http://127.0.0.1:4173/`; viewport 1440×900; 2026-09-01 | PASS — full page renders at 7,849px high; no console errors or horizontal clipping observed. |
| Mobile | `qa/screenshots/mobile-390x844-final-content.png`; same local URL; viewport 390×844; 2026-09-01 | PASS — full page renders at 8,493px high; explicit single-column collapse, legible controls and no console errors observed. |
| Runtime resources | Fresh local Chrome/Playwright page load | PASS — console errors: 0. |
| Local boundary | `127.0.0.1` temporary preview only | PASS — no upload, deployment, external write, login, booking or form action. |
| Gallery crop and alignment correction | `qa/screenshots/gallery-equal-final.png`; targeted independent review | PASS — both official gallery images use equal 1:1 cards; the left dog’s face and full body are visible, with no stretch, crop, overflow or rounded-corner defect. |
| Dense-content render | `qa/screenshots/desktop-content-expanded-final.png` and `qa/screenshots/mobile-content-expanded-final.png`; 1440×900 and 390×844 | PASS — services, FAQ and the 8-image official gallery render locally with console errors: 0. |

## Business-fidelity and scope QA

| Requirement | Evidence / conclusion |
| --- | --- |
| Customer recognition | Official logo, 6 distinct official dog-gallery images, both official locations/phones, the official public email and public Fresha route are visible. |
| Correct scope | Page represents dog grooming, nail clipping, dry clipping, anal gland care, collection/delivery, private bookings for nervous dogs, the no-cat/no-hand-stripping/non-mobile boundaries, both locations and external enquiry/booking routes. |
| Hours handling | PASS — no opening-hours claim is shown. The page routes current Stamford appointment availability to Fresha because the two public schedules conflict. |
| Exclusions held | No copied Fresha price/duration catalogue, review text/counts/ratings, named staff, platform portfolio media, Facebook content or outbound Facebook route, award/qualification, parking/insurance/cancellation claim, payment, booking UI, CMS or server function. |
| Asset chain | Every visible image is an `AS-01`–`AS-08` official asset recorded in `IMAGE_LEDGER.md`; `AS-05` Fresha portfolio is not used. |
| Visual storyboard | Hero, service proof, care image and distinct gallery images each use different official assets; no repeated photo crop is used to pad the page. |
| CTA | `Book on Fresha` is the single booking-intent label and points to the actual named Stamford Fresha venue. Telephone, mailto and official contact-form links are separate information/contact paths, not duplicate booking CTAs. |
| Client-visible internal-text gate | PASS after independent-review correction — `Independent concept preview` is the permitted customer-visible identity label; manual/grep review finds no local path, QA, PMO, rights, authorisation, hash, source-transfer, mock, placeholder, TODO or internal-process text. |

## Finesse pre-flight self-grade

1. **Engine check:** a restrained CSS hero frame is visible as the pink cutout frame, offset stamp and layered circular line; it is intentional `SPECTACLE 3`, not a claimed animation engine.
2. **Soul check:** Graphic Grooming Studio is visible in the locked ink/paper/berry palette, assertive rounded display hierarchy, sharp image crops and non-pastel service grid.
3. **Hard-ban sweep:** no visible em dash, invented number, gradient text, generic purple glow or placeholder. Two small labels across six major content sections meet the one-per-three guideline.
4. **Substrate check:** `styles.css` applies tinted neutrals, grain, translucent header borders, layered hero depth, tight headline tracking and berry-tinted shadows.
5. **Dial honesty:** `SPECTACLE 3` is deliberately static with no automatic animation; `DENSITY 6` is supported by services, care, local contact and gallery without a live catalogue.

## Acceptance and outstanding gates

- Expanded-content independent visual acceptance: `PASS` after a different Owner’s read-only review of the final Desktop/Mobile screenshots and customer-visible factual boundaries. It specifically confirms that no fixed/conflicting opening hours, unsupported hour-only appointment claim or unverified Facebook route remains.
- Dense-content independent review: `PASS` after a different Owner reconciled `AS-09`–`AS-14` across the HTML, Image Ledger and asset inventory, and verified every new service/FAQ item against `SRC-12` and customer intelligence. No static prices, times, opening hours, platform team/reviews/media, Facebook content or recreated server form appears.
- User visual acceptance remains pending. Until that judgement, do not mark the result `CLIENT-SHOWABLE DEMO = PASS`.
- Screenshot/package acceptance, deployment, public link allocation, outreach and source transfer remain unapproved until their separate gates and user authorisation are met.
