# QA — The Salon Hair & More

## Gate 1 — source/fact audit
PASS
- Business: The Salon Hair & More.
- Category: салон за красота.
- Address used: София, бул. „Йерусалим“, бл. 12, партер — Studio24 cleaner address; Google Maps text had a duplicated address string.
- Phone: 088 399 9773 — source sheet/Google Maps.
- Booking: https://studio24.bg/the-salon-hair-more-s4423/m — Studio24.
- No official standalone website found; only Studio24/Google/Facebook traces.

## Gate 2 — visual-result image audit
PASS WITH NOTE
- Studio24 gallery contains usable real nail-result images and salon interior images.
- No accessible public hair-result images found; site does not overclaim hair result proof and uses nail-result photos as visible work proof.
- Facebook public page attempts were login-blocked/no useful public imagery.

## Gate 3 — testimonial audit
PASS WITH CAUTION
- Google Maps text capture found mixed reviews.
- Used only one verified positive written Google review excerpt with real reviewer name.
- No aggregate review count displayed.

## Gate 4 — copy audit
PASS
- Bulgarian copy kept plain and local.
- No invented prices, awards, guarantees, or exaggerated rating claims.
- Services based on Studio24 profile categories.

## Gate 5 — link/schema/SEO-head audit
PASS
- Tested local href extraction: phone, Studio24, Google Maps, navigation anchors present.
- BeautySalon schema includes NAP, opening hours, sameAs, canonical URL.
- SEO head includes title, description, robots, canonical, single H1, OG tags, twitter card, absolute og:image.

## Gate 6 — image/layout audit
PASS
- All referenced local image assets exist.
- Hero uses salon interior; result/gallery uses nail-result photos and room photos without duplicate hero misuse.

## Gate 7 — map/local SEO audit
PASS
- Bottom local SEO/contact map block present directly above footer.
- Exactly one visible navigation CTA in the map/contact block.
- Google Maps iframe uses full business + address query.

## Gate 8 — responsive visual QA
PASS
- CSS includes responsive mobile layout for hero, cards, gallery, CTA, map and footer.
- HTML/CSS asset audit passed; no broken local image references.

## Gate 9 — live QA
PASS
- Repo: https://github.com/Deanooooooooo/the-salon-hair-more-site
- Live: https://deanooooooooo.github.io/the-salon-hair-more-site/
- HTTP 200 confirmed after Pages build.
- Live HTML contains business name, verified testimonial name, schema, OG tags, map block and phone CTA.
