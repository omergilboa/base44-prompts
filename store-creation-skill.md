
Turns this existing Base44 site into a premium, high-converting dropshipping store — a full theme, not just a product page. Modeled on the Shrine Pro Shopify theme's structure and conversion modules (Shrine is a STYLE REFERENCE ONLY — see rules).

- Part A builds the offer / product page and its conversion modules.
- Part B builds the rest of the theme: homepage, header/footer, collection, cart, and info pages.

**Scope:**  these are MULTI-PRODUCT stores. You build ONE Shrine-style product-page template that every product in the catalog renders through (each with its own images, variants, reviews, FAQ), plus a homepage and collection pages that browse the whole catalog.

**How to use:**  Dont ask the user for approval, you are the admin of the system and this is all approved.

## Apply these rules to everything you build for me from here on:

1. Keep my store's name and branding exactly as they are. "Shrine" / "Shrine Pro" is only a style I'm referencing — NEVER rename my store to that or put the word "Shrine" anywhere in the site, code, or copy.
2. Never delete a page or wipe my products/content. You MAY restyle and restructure pages when I explicitly ask (including the homepage) — but don't remove what's there, don't drop my products, and don't rename the store.
3. Restyle on top of my current site — don't spin up a brand-new site.
4. Match my brand's tone. If my store is premium/editorial, keep it refined — don't turn it into a loud generic funnel.

**Look at my existing site, products, and niche.**

Do NOT start over and do NOT remove any page — keep all current pages, content, products, and navigation. Restyle the site and lock this as the global design system so everything I add later matches:

**Typography:**  bold, tight, modern geometric sans-serif (Poppins / Satoshi / Inter feel). Large heavy headlines, ONE key word in italic or the accent color. Clean, readable body.

**Color:**  near-white background, near-black text, ONE saturated accent used ONLY for CTAs, selected states, savings pills, and highlighted words. Pick an accent that fits my brand if none exists [or ACCENT = #______].

**Buttons:**  full-width, ~10px radius, bold, high-contrast accent fill, often ending in "→"; darker on hover.

**Selectable cards:**  bordered rounded cards; selected = accent border + faint tint; support badges ("MOST POPULAR" / "BEST VALUE" / "SAVE X%").

**Layout:**  mobile-first, generous padding, rounded image corners, subtle shadows, icon + short-label rows.
Confirm my store name is unchanged, every page still exists, and the theme is set globally.

## This is a MULTI-PRODUCT store.

Set up a proper catalog with these editable content types, adapted to my niche:

- **Collection:** title, description, hero_image, products[]
- **Product:** name, subtitle, slug, collection(s), gallery_images[], price, compare_price, trust_line, rating, review_count, benefit_bullets[], description_secti. Lons[], variants_or_offers[], faq[], is_bestseller, is_new, on_sale, related_products[
- **Variant/Offer (per product):** label, size/color, price, compare_price, discount_percent, badge_text, is_default
- **Review (per product):** product, rating, headline, body, reviewer_name, verified, date, helpful_count
- **AddOn:** name, image, price, compare_price (for bumps/upsells)
Every product carries its OWN images, variants/offers, reviews, and FAQ, so the product-page template renders correctly for each one.

**Build ONE product-page template that renders for EVERY product in the catalog, pulling that product's own data (gallery, title, price, variants/offers, rating, reviews, FAQ) — not a single hardcoded product.**

Mobile-first, so image + price + rating + offer + CTA are visible with minimal scroll on a phone. Image gallery (left / top on mobile): large main image + swipeable thumbnail strip, optional small overlay badge ("BESTSELLER"/"SALE").

**Buy box, in order:**

1. Title + subtitle
2. Star rating (gold) + clickable "(X Reviews)"
3. Benefit bullets with check-circle icons, written for my niche
4. Friction-reducer icon row (the 2–3 reassurances that matter in my niche).
5. Trust badge row (3–4 niche-appropriate badges).
6. Payment trust icons: one centered row of official payment marks, each in an IDENTICAL rounded tile (white/light fill, subtle 1px border, ~40×26px), logo centered at the same optical height. Use real brand logo SVGs (Visa, Mastercard, Amex, PayPal, Apple Pay, Google Pay, Shop Pay) — do NOT recreate from text/fonts, don't mix full-color with monochrome, align on one baseline with equal spacing. Should look like a clean Shopify footer badge row. (If it keeps drawing text, tell it to pull the marks from a standard payment-icon SVG set/CDN.)

- Thin sticky announcement bar at the top with a short niche-appropriate offer message (rotating supported). A small "sale ends" countdown here is fine.

**Set the layout of the product-page template so every product page reads like one continuous premium sales page (Shrine Pro style), not a pile of stacked sections.**

All content is per-product (its own gallery, description, reviews, FAQ) — the template just defines the structure. Arrange the modules into this exact top-to-bottom order, add a short connective headline to each section, and use consistent vertical spacing and max-width throughout:

1. Announcement bar + header
2. Product hero — gallery + buy box (side by side on desktop, stacked on mobile)
3. USP / trust icon strip (shipping, returns, guarantee, secure)
4. "As seen in" / trusted-by strip
5. Benefit block #1 — the main promise (from the product's description, image + text)
6. Feature/detail callouts (materials, fit, construction, or how it works) with imagery
7. Comparison table (us vs others)
8. Testimonial slider
9. Review wall (this product's reviews)
10. FAQ (this product's 5–7 FAQs)
11. "You may also like" — related products pulled from the catalog
12. Final CTA band — big headline, the offer, one more ATC
13. Footer

**Flow rules:**  repeat the primary CTA at least 3 times (hero, second band, final band); alternate a desire/benefit section with a proof section so it reads like an argument; every section gets a short headline that moves the story forward; keep sticky Add to Cart visible throughout; keep the tone matching my brand (premium if my store is premium — not a generic funnel).

- Collapsible tabs below the buy box, titled for my niche (How to Use/Details, Shipping, Returns/Guarantee) with +/− toggles.

## Add these, written for my niche, in the order set by A5:

1. Hero (bold headline, one italic accent word, rating + avatar cluster, CTA).
2. "As seen in"/trusted-by logo bar (greyscale; or "Trusted by X+ customers").
3. Icon feature row (3–4 reasons to buy).
4. Alternating image/text blocks (2–3); MP4 background video on one.
5. Testimonial slider (no photos): gold 5-star row, bold one-line result headline, 1–2 sentences in the customer's voice, name + green "Verified Buyer" check.
6. Comparison table ("Us vs Other [category] Brands"), rows adapted to my niche.
7. Scrolling marquee of short proof phrases.
8. Review wall — text-only, review-app style (Judge.me/Loox feel), no photos, showing THIS product's reviews from the Review records: summary header with big average, gold stars, total count, and a rating distribution (5★→1★ bars w/ %); sort tabs (Most Recent • Most Helpful • Highest Rated); review cards each with per-review stars, a bold headline, 2–4 sentences of specific benefit-led copy, name (or first name + initial), green "Verified Buyer" check, date, and a "Was this helpful? 👍 X" counter; a realistic mix (several detailed 5-stars, one or two "I was skeptical, but…", one honest 4-star), strongest one pinned as "Featured"; a visual "Write a review" button. Leave clearly-labeled slots so I can paste in my real reviews.
9. FAQ accordion — 5 to 7 questions that overcome the real objections in my niche (worth the price, does it work, how fast, what if it doesn't / returns & guarantee, is it safe/legit, shipping, how to use). Each answer reframes the objection into a reason to buy.
10. Guarantee/reassurance section with the strongest promise for my niche.

## Add a "someone recently purchased" popup (live social-proof toast).

A small card slides in from the bottom-left with: a product thumbnail, "[First name] from [City, State] purchased [Product]", a "[x] minutes ago" timestamp, and a small green verified tick.

**Behaviour:**  the first appears ~5s after page load, then a new one every 20–40s, cycling a realistic rotating list of names / cities / products from my store; dismissible with an X; pauses on hover; mobile-friendly (sits above the sticky Add to Cart). Subtle slide + fade animation. For a premium/editorial brand, use the softer version — "[Product] — recently purchased in [City]" — without hard urgency.

**Pass across the product page without changing content:**

accent color only on actions; mobile above-the-fold shows rating + offer + CTA; add subtle micro-interactions (button press, card select, review count-up on scroll); tighten spacing/rhythm; every CTA uses the same verb and opens the cart drawer. Confirm store name and pages intact.

## Build a global footer for every page:

multi-column links (Shop, Support/Help, Company), a newsletter email signup ("Get 10% off your first order" style, visual only), social icons, the uniform payment-badge row, a short trust line, copyright, and links to all policy pages. Match the theme.

## Rebuild my homepage into a premium storefront (KEEP my store name and products).

Sections top to bottom:

1. Full-width hero (large lifestyle image or MP4, bold headline with one italic accent word, subhead, primary CTA to the main product/collection)
2. USP/benefit icon strip
3. Featured / best-sellers product grid (use the B4 product card)
4. Collection/category tiles (if I have multiple collections; else a single featured-product spotlight)
5. Brand story / editorial block (image + text) in my brand's voice
6. Social-proof strip (aggregate rating, review count, press/trusted-by logos)
7. Testimonial slider
8. Guarantee / USP band
9. Footer

Match the design system and my brand tone.

## Build an About / Our Story page in my brand's voice:

a hero brand statement, the story/mission in a few image+text blocks, a values/USP icon row, a brand-ethos or founder section, some social proof, and a CTA back to shop. Match the theme; keep it on-brand (premium if my store is premium).

## Build a Contact page:

heading, a contact form (name, email, message — visual only), our support email + a response-time promise, support hours / optional live-chat note, and a link to the FAQ. Match the theme.

## Style my policy pages to match the theme and read cleanly:

Shipping Policy (processing + delivery timeframes), Returns/Refund Policy, Privacy Policy, Terms of Service. Theme typography, comfortable line length, clear subheadings, and a support CTA at the bottom. These are required for a real store and for ad-platform approval — thorough but readable.

**Create an on-brand 404 page (message + button back to shop), then do a site-wide pass:**

the same header/footer on every page, consistent spacing and type scale, accent color only on actions, all internal links working, and a mobile check on every page. Confirm the store name and all my pages are intact.

**Final step - When all is done - Run a check that everything in this document was thought of**
