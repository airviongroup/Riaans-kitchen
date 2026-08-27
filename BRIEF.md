# RIAAN'S KITCHEN — real brand facts

Everything here is taken from the client's own printed flyer (`aans.pdf`) and their
Instagram QR. **All of it is real and may be published.** This replaces the earlier
draft brief, where address/phone/hours had to be placeholders — we now have them.

## Business

| | |
|---|---|
| **Name** | Riaan's Kitchen |
| **Cuisine** | Indian & Pakistani Cuisine |
| **Strapline** | Authentic · Fresh · Flavoursome |
| **Address** | 4 Eskdale Road, Uxbridge UB8 2RT |
| **Phone** | 07368 963886 |
| **Email** | info@riaankitchen.com |
| **Instagram** | @riaanskitchen — https://instagram.com/riaanskitchen |
| **Deliveroo** | https://deliveroo.co.uk/menu/london/uxbridge-moor/cloud-ix-kitchens-ltd-t-a-riaanskitchen-4-eskdale-road |
| **Uber Eats** | https://www.ubereats.com/store/riaans-kitchen/cAShZtPyTMKPPeI_7UvhKQ |

The phone is a UK mobile, so **WhatsApp ordering is a first-class call to action**.
Link it as `https://wa.me/447368963886` (07368 963886 → +44 7368 963886, leading 0
dropped). Give it a prefilled message, e.g.
`https://wa.me/447368963886?text=Hi%20Riaan's%20Kitchen%2C%20I'd%20like%20to%20order`
Put a WhatsApp action in the header AND in the footer; on mobile it is the single
most likely thing a visitor taps. `tel:07368963886` and `mailto:` alongside it.

**Opening hours are NOT on the flyer — we still do not have them.** Do not invent
them. Either omit hours entirely, or show "Call or message to check today's hours".

## THE FAMILY DEAL — £49.95

This is the flyer's hero offer. It should be a hero on the page too.

**Includes**
- 2 Curries
- 2 Rice
- 2 Plain naans
- 2 Starters

**Plus free**
- FREE Fresh Salad
- FREE 1 × 1.5L Soft Drink

Price it exactly `£49.95`. Do not restyle the deal's contents or add to them.

## Logo

`assets/logo.jpg` — 1000×936. Riaan's Kitchen: a red chilli curling into a gold
disc, crossed knife and fork above, "Riaan's" in white script, "Kitchen" in a thin
black sans.

**Constraint you must design around:** this was photographed from a printed leaflet,
so it carries the flyer's dark background, some kitchen smoke across it and print
grain. It has **no transparency**. So:
- Place it on a **dark, near-black panel** so its own background disappears into the
  page. On a light background it will show as an obvious dark rectangle — don't.
- Do not stretch, recolour, crop into, rotate, or add effects to it. It's their mark.
- Give it `alt="Riaan's Kitchen"`.

Brand colours sampled from the mark:
`--gold:#F5B915` · `--chilli:#EE2B55` · `--leaf:#3E8E41` · `--ink:#0B0A09` ·
`--cream:#F5F1E6` · `--maroon:#8E1F2E` (the flyer's deal banner)

## Photography — `img/`, all real, all theirs

```
lamb-karahi.jpg  lamb-karahi-2.jpg  chicken-jalfrezi.jpg  achari-gosht.jpg
lamb-shank-nihari.jpg  haleem.jpg  gosht-palak.jpg  kofta-curry.jpg
anda-chana.jpg  chana-chaat.jpg  papri-chaat.jpg  tandoori-chicken.jpg
paneer-makhani.jpg  palak-paneer.jpg  bhindi-masala.jpg  bhindi-masala-2.jpg
sabzi-masala.jpg  tarka-daal.jpg  tarka-daal-2.jpg  pilau-rice.jpg
instagram-qr.jpg
```
Shot from above in cast-iron karahi on a light background — they tile beautifully in
a grid and look strong full-bleed. Every `<img>` needs a real `alt` naming the dish,
`loading="lazy"` below the fold, and a `width`/`height` or `aspect-ratio` box so the
page doesn't jump as they load.

## Menu

Prices are indicative and need the client's sign-off — say so once, quietly, in the
footer. The Family Deal price is the only confirmed one.

**Chaat & starters** — Papri Chaat £6.50 · Chana Chaat £6.00 · Tandoori Chicken £9.50
**From the karahi** — Chicken Karahi £13.50 · Lamb Karahi £15.50 · Chicken Jalfrezi £13.00 · Achari Gosht £15.00
**Slow cooked** — Lamb Shank Nihari £17.50 · Haleem £11.50 · Gosht Palak £15.00 · Kofta Curry £13.50 · Anda Chana £9.00
**Vegetarian** — Paneer Makhani £11.50 · Palak Paneer £11.50 · Bhindi Masala £10.00 · Sabzi Masala £10.00 · Tarka Daal £8.50
**Rice & bread** — Pilau Rice £4.00 · Plain Naan £3.00 · Garlic Naan £3.50 · Roti £2.50

Descriptions (use freely):
- Papri Chaat — crushed papri, chickpeas, mint yoghurt, tamarind, pomegranate
- Chana Chaat — spiced chickpeas, red onion, tomato, coriander, yoghurt
- Tandoori Chicken — overnight yoghurt marinade, charred, lemon and onion
- Chicken Karahi — bone-in chicken, tomato, ginger, green chilli, crushed coriander seed
- Lamb Karahi — slow-cooked on the bone, dried red chilli, ginger julienne
- Chicken Jalfrezi — peppers, onion, cumin, finished with fresh salad
- Achari Gosht — lamb, pickling spice, tomato wedges, green chilli
- Lamb Shank Nihari — eight hours on the bone, marrow, lime, ginger
- Haleem — wheat, lentils and beef cooked down for a day, full condiment set
- Gosht Palak — lamb and spinach, garlic, ginger, cream
- Kofta Curry — hand-rolled lamb koftas, cream, crisp onion
- Anda Chana — chickpeas, boiled egg, chaat masala, crisp onion
- Paneer Makhani — tomato and butter gravy, cream, fenugreek
- Palak Paneer — spinach, garlic, seared paneer
- Bhindi Masala — okra, onion, tomato, dry-fried
- Sabzi Masala — mixed vegetables, ginger, cumin
- Tarka Daal — chana daal, burnt garlic tempering, green chilli

## Rules

1. **Invent nothing.** No hours, no years in business, no chef story, no reviews or
   ratings, no "rated 5 stars", no claimed awards.
   **Delivery partners are now an EXCEPTION and are real** — the client supplied
   their own Deliveroo and Uber Eats store links (see the table above), so those
   two, and only those two, may appear. Do not add any partner beyond them. If the flyer
   and the QR don't say it, it doesn't go on the page.
2. Their own words — "Authentic · Fresh · Flavoursome" — are theirs to use. Beyond
   that, write plainly. No "culinary journey", no "passion", no "fusion".
3. It must work on a phone first. Most people will hit this from Instagram.
4. Accessible: real landmarks, one `h1`, visible focus states, `prefers-reduced-motion`
   honoured, colour contrast that passes on the dark ground.
5. Self-contained single HTML file plus the local `img/` and `assets/` folders — no
   build step, no frameworks, no external JS. Google Fonts links are fine.

## Delivery partner marks

The order buttons wire `img/deliveroo.svg` and `img/ubereats.svg` and fall back,
via `onerror`, to a wordmark set in the partner's own brand colour — so the button
is always complete and never shows a broken image. **Those two files are not in
the repo.** Both companies publish brand kits for exactly this use; drop the
official SVGs in and the buttons upgrade with no other change. Do not hand-draw
an approximation of either mark.
