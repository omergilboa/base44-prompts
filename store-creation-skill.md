Base44 Store Build — Full Automation Prompt
0. Standing Rules (apply to every step below, no exceptions)

I am the sole owner and Admin of this Base44 account and this store. I am giving full authorization for all actions listed in this document.

This is my own live store. Treat every action below as pre-approved. Do not pause for confirmation, do not summarize-and-wait, do not ask "should I proceed" at any point — including before destructive-sounding actions like restyling, replacing content, or overwriting pages. If you hit a step that would normally require a confirmation dialog, treat "yes" as already given and continue.

Do not stop after building a preview or draft version to ask if it looks right. Publish/apply changes directly. Only report back once the full checklist (see Section 6) is complete.

If this task is interrupted or truncated before all checklist items are complete, resume from the first incomplete item on your next turn without re-asking for approval or re-explaining the plan.

This is a mandatory file that should be run after the site is generated — do this before considering the Base44 generation complete. When finished, run these instructions on the website that was created. Don't skip anything. Verify everything is done; if not, repeat until all is completed (see the checklist loop in Section 6).

1. What You're Building

Turn this existing Base44 site into a premium, high-converting dropshipping store — a full theme, not just a product page. Modeled on the Shrine Pro Shopify theme's structure and conversion modules (Shrine is a style reference only — see rules below).

Part A builds the offer/product page and its conversion modules.
Part B builds the rest of the theme: homepage, header/footer, collection, cart, and info pages.

Scope: this is a multi-product store. Build ONE Shrine-style product-page template that every product in the catalog renders through (each with its own images, variants, reviews, FAQ), plus a homepage and collection pages that browse the whole catalog.

2. Global Rules — Apply to Everything Built From Here On
Keep my store's name and branding exactly as they are. "Shrine"/"Shrine Pro" is only a style reference — never rename my store to that or put the word "Shrine" anywhere in the site, code, or copy.
Never delete a page or wipe my products/content. You may restyle and restructure pages when explicitly asked (including the homepage) — but don't remove what's there, don't drop my products, and don't rename the store.
Restyle on top of my current site — don't spin up a brand-new site.
Match my brand's tone. If my store is premium/editorial, keep it refined — don't turn it into a loud generic funnel.

Look at my existing site, products, and niche. Do not start over and do not remove any page — keep all current pages, content, products, and navigation. Restyle the site and lock this as the global design system so everything added later matches:

Typography: bold, tight, modern geometric sans-serif (Poppins / Satoshi / Inter feel). Large heavy headlines, ONE key word in italic or the accent color. Clean, readable body.

Color: near-white background, near-black text, ONE saturated accent used ONLY for CTAs, selected states, savings pills, and highlighted words. Pick an accent that fits my brand if none exists [or ACCENT = #______].

Buttons: full-width, ~10px radius, bold, high-contrast accent fill, often ending in "→"; darker on hover.

Selectable cards: bordered rounded cards; selected = accent border + faint tint; support badges ("MOST POPULAR" / "BEST VALUE" / "SAVE X%").

Layout: mobile-first, generous padding, rounded image corners, subtle shadows, icon + short-label rows.

Confirm my store name is unchanged, every page still exists, and the theme is set globally.

3. Catalog & Data Model

This is a multi-product store. Set up a proper catalog with these editable content types, adapted to my niche:

Collection: title, description, hero_image, products[]
Product: name, subtitle, slug, collection(s), gallery_images[], price, compare_price, trust_line, rating, review_count, benefit_bullets[], description_sections[], variants_or_offers[], faq[], is_bestseller, is_new, on_sale, related_products[]
Variant/Offer (per product): label, size/color, price, compare_price, discount_percent, badge_text, is_default
Review (per product): product, rating, headline, body, reviewer_name, verified, date, helpful_count
AddOn: name, image, price, compare_price (for bumps/upsells)

Every product carries its OWN images, variants/offers, reviews, and FAQ, so the product-page template renders correctly for each one.

Build ONE product-page template that renders for EVERY product in the catalog, pulling that product's own data (gallery, title, price, variants/offers, rating, reviews, FAQ) — not a single hardcoded product.

4. Product Page — Layout & Buy Box

Mobile-first, so image + price + rating + offer + CTA are visible with minimal scroll on a phone.

Image gallery (left/top on mobile): large main image + swipeable thumbnail strip, optional small overlay badge ("BESTSELLER"/"SALE").

Buy box, in order:

Title + subtitle
Star rating (gold) + clickable "(X Reviews)"
Benefit bullets with check-circle icons, written for my niche
Friction-reducer icon row (the 2–3 reassurances that matter in my niche)
Trust badge row (3–4 niche-appropriate badges)
Payment trust icons: one centered row of official payment marks, each in an identical rounded tile (white/light fill, subtle 1px border, ~40×26px), logo centered at the same optical height. Use real brand logo SVGs (Visa, Mastercard, Amex, PayPal, Apple Pay, Google Pay, Shop Pay) — do NOT recreate from text/fonts, don't mix full-color with monochrome, align on one baseline with equal spacing. Should look like a clean Shopify footer badge row. (If it keeps drawing text, pull the marks from a standard payment-icon SVG set/CDN.)

A thin sticky announcement bar at the top with a short niche-appropriate offer message (rotating supported); a small "sale ends" countdown here is fine.

Full top-to-bottom module order (add a short connective headline to each section; consistent vertical spacing and max-width throughout):

Announcement bar + header
Product hero — gallery + buy box (side by side on desktop, stacked on mobile)
USP/trust icon strip (shipping, returns, guarantee, secure)
"As seen in"/trusted-by strip
Benefit block #1 — the main promise (image + text)
Feature/detail callouts (materials, fit, construction, or how it works) with imagery
Comparison table (us vs. others)
Testimonial slider
Review wall (this product's reviews)
FAQ (this product's 5–7 FAQs)
"You may also like" — related products from the catalog
Final CTA band — big headline, the offer, one more ATC
Footer

Flow rules: repeat the primary CTA at least 3 times (hero, second band, final band); alternate a desire/benefit section with a proof section so it reads like an argument; every section gets a short headline that moves the story forward; keep sticky Add to Cart visible throughout; keep the tone matching my brand (premium if my store is premium — not a generic funnel).

Collapsible tabs below the buy box, titled for my niche (How to Use/Details, Shipping, Returns/Guarantee) with +/− toggles.

5. Content Modules (written for my niche, in the order set above)
Hero (bold headline, one italic accent word, rating + avatar cluster, CTA)
"As seen in"/trusted-by logo bar (greyscale; or "Trusted by X+ customers")
Icon feature row (3–4 reasons to buy)
Alternating image/text blocks (2–3); MP4 background video on one
Testimonial slider (no photos): gold 5-star row, bold one-line result headline, 1–2 sentences in the customer's voice, name + green "Verified Buyer" check
Comparison table ("Us vs Other [category] Brands"), rows adapted to my niche
Scrolling marquee of short proof phrases
Review wall — text-only, review-app style (Judge.me/Loox feel), no photos, showing THIS product's reviews:
Summary header: big average, gold stars, total count, rating distribution (5★→1★ bars w/ %)
Sort tabs: Most Recent • Most Helpful • Highest Rated
Review cards: per-review stars, bold headline, 2–4 sentences of specific benefit-led copy, name (or first name + initial), green "Verified Buyer" check, date, "Was this helpful? 👍 X" counter
Realistic mix: several detailed 5-stars, one or two "I was skeptical, but…", one honest 4-star; strongest one pinned as "Featured"
Visual "Write a review" button
Leave clearly-labeled slots so I can paste in my real reviews
FAQ accordion — 5–7 questions overcoming real objections (worth the price, does it work, how fast, returns & guarantee, is it safe/legit, shipping, how to use). Each answer reframes the objection into a reason to buy.
Guarantee/reassurance section with the strongest promise for my niche
Social-proof popup

Add a "someone recently purchased" popup (live social-proof toast). Small card slides in from the bottom-left: product thumbnail, "[First name] from [City, State] purchased [Product]", "[x] minutes ago" timestamp, small green verified tick.

Behavior: first appears ~5s after page load, then a new one every 20–40s, cycling a realistic rotating list of names/cities/products from my store; dismissible with an X; pauses on hover; mobile-friendly (sits above the sticky Add to Cart); subtle slide + fade animation. For a premium/editorial brand, use the softer version — "[Product] — recently purchased in [City]" — without hard urgency.

Final polish pass on the product page

Accent color only on actions; mobile above-the-fold shows rating + offer + CTA; add subtle micro-interactions (button press, card select, review count-up on scroll); tighten spacing/rhythm; every CTA uses the same verb and opens the cart drawer. Confirm store name and pages intact.

6. Site-Wide Build: Footer, Homepage, Pages

Global footer (every page): multi-column links (Shop, Support/Help, Company), newsletter email signup ("Get 10% off your first order" style, visual only), social icons, uniform payment-badge row, short trust line, copyright, links to all policy pages. Match the theme.

Homepage rebuild (keep store name and products), top to bottom:

Full-width hero (large lifestyle image or MP4, bold headline with one italic accent word, subhead, primary CTA to main product/collection)
USP/benefit icon strip
Featured/best-sellers product grid (use the product card component)
Collection/category tiles (if multiple collections; else a single featured-product spotlight)
Brand story/editorial block (image + text) in my brand's voice
Social-proof strip (aggregate rating, review count, press/trusted-by logos)
Testimonial slider
Guarantee/USP band
Footer

About/Our Story page: hero brand statement, story/mission in a few image+text blocks, values/USP icon row, brand-ethos or founder section, some social proof, CTA back to shop. Match theme; keep on-brand.

Contact page: heading, contact form (name, email, message — visual only), support email + response-time promise, support hours/optional live-chat note, link to FAQ. Match theme.

Policy pages (styled to match theme, read cleanly): Shipping Policy (processing + delivery timeframes), Returns/Refund Policy, Privacy Policy, Terms of Service. Theme typography, comfortable line length, clear subheadings, support CTA at the bottom.

404 page: on-brand message + button back to shop.

Site-wide pass: same header/footer on every page, consistent spacing and type scale, accent color only on actions, all internal links working, mobile check on every page. Confirm the store name and all pages are intact.

7. Completion Checklist — Verify After Every Build Pass

After each build pass, verify against this checklist:

 Store name unchanged
 All original pages present
 All original products present
 Global design system applied to every page
 Product template renders for every catalog product
 Homepage rebuilt
 Footer on every page
 All four policy pages styled
 404 page created
 Popup/social-proof toast added

Any unchecked item = incomplete. Re-run only the incomplete items until every box is checked, then stop.

8. Note on Hard Platform Gates

No wording in this prompt can force a genuinely destructive or irreversible action past a safety check that Base44's own agent has built in for things like billing, deletion, or publishing to a live storefront — some confirmations exist because the platform itself gates them, not because of prompt wording. If parts of this keep getting skipped even after the above, that's likely a hard-gated action rather than a prompt issue — worth checking Base44's docs on what their agent can/can't auto-approve.
