# Sprylo — Tech &amp; Gadgets Ecommerce HTML Template

A free, production-ready HTML template for tech and electronics
retailers, gadget marketplaces, audio/camera shops, and modern consumer
electronics stores. Bright **white surface** with **indigo primary**,
multi-color **bento product cards** in the hero (deep-blue, purple
gradient, orange, green, near-black), and a clean three-font system —
**Plus Jakarta Sans** (display) + **Outfit** (body) + **Roboto Mono**
(captions). Tokenised, responsive, accessible. No framework, no build
step, no JS dependencies.

## Pages

- `index.html` — Home (utility strip · header with search · category nav · 5-card bento hero · trending-products with tabs · 2-up discount banners · 5-tile category grid · compact card row · brand strip · indigo-purple newsletter · 5-column footer)
- `shop.html` — Catalogue (sticky sidebar with category / price-range / brand / rating / availability filters · sort toolbar · 3-up product grid · numbered pagination)
- `product.html` — Product detail (5-thumbnail gallery + main image · price with strikethrough &amp; save badge · color swatches · configuration option pills · qty stepper · add-to-cart / buy-now / wishlist · specs table · review distribution + individual reviews · related products)
- `cart.html` — Cart (line items with quantity stepper · promo code input · order summary with discount line · trust strip · payment-method icons)
- `contact.html` — Contact (5 info blocks with circular icons · trade-desk callout · 4-field grid form · short FAQ)

## Tech

- Static HTML, vanilla CSS, vanilla JS (no framework, no build, no dependencies)
- Google Fonts: **Plus Jakarta Sans** (500/600/700/800 — headlines), **Outfit** (400/500/600/700 — body), **Roboto Mono** (400/500 — eyebrows / captions / coordinates)
- Real Unsplash product photography linked directly — replace with your own assets before launch
- Reduced-motion friendly, keyboard accessible, semantic landmarks, skip-link, ARIA on interactive controls
- Responsive at 375 / 768 / 1024 / 1440

## Design system

All tokens at the top of `assets/css/styles.css`:

- **Palette** — `--paper` (#FFFFFF) primary surface, `--bg` (#F8FAFC) section fill, `--ink` (#0F172A) text, `--indigo` (#4F46E5) primary CTA &amp; accent, `--indigo-soft` (#EEF2FF) chip/hover fill, plus a set of bento card colors: `--card-blue`, `--card-purple`, `--card-orange`, `--card-green`, `--card-black`
- **Typography** — three-font system (display / body / mono), modular type scale, all headlines 700/800 weight in Plus Jakarta Sans
- **Spacing** — 1 → 10 modular scale
- **Motion** — single ease (`cubic-bezier(0.22, 1, 0.36, 1)`), full reduced-motion fallback
- **Layout** — sticky 84px header + sticky 60px category nav (z-stacked), 1280px container max
- **Shadows** — three depth tiers plus a signature indigo-offset shadow on primary CTAs

Adjust the `:root` block to recolor or rescale the whole template.
Change `--indigo` to recolor every primary CTA, badge, hover, and
accent line across all five pages. Swap the bento `--card-*` colors to
restyle the hero without touching markup.

## Layout archetype

- **Top utility strip** on the ink ground (free shipping promo + utility links)
- **Sticky main header** with logo + central search + account/wishlist/cart icons
- **Sticky category nav** with indigo "All Categories" pill + horizontal nav + promo callout
- **Bento hero** — 5 colored cards: one large gradient blue card (lead product), one purple gradient sidekick, then three smaller cards (orange, green, black) on the row beneath. Each card has its own product image positioned bottom-right with drop-shadow.
- **Trending products** — tab filter (Mobile / Watch / Camera / Accessories / Speaker) + 5-up product card row with badges, ratings, in-stock indicators, hover wishlist toggle
- **2-up discount banners** — dark-navy + purple gradient with offset product images
- **Round-tile category grid** — 5 across, each with image + name + product count
- **Compact card row** — 4 across, sideways-laid for "Just for you" picks
- **Brand strip** — wordmark logos in muted grey, hover ink
- **Newsletter** — indigo→purple gradient banner with rounded pill form
- **5-column footer** — brand + socials, then 4 link columns

## License

Free for personal and commercial projects. Attribution appreciated but
not required. Photography is linked from Unsplash; replace before
production deployment.
