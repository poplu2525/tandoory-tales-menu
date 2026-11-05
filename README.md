# Tandoory Tales — Interactive Digital Menu

**Live website:** https://poplu2525.github.io/tandoory-tales-menu/

A mobile-first, bilingual (English / Hindi) digital menu for **Tandoory Tales**, Best Mega Mall, Rohini Sector 24, Delhi.

## Features
- Premium devotional hero banner featuring Shri Ram, Hanuman Ji, and Mata Vaishno Devi.
- An expandable, bilingual **Our Story** section explaining the working-professional founders’ small-counter dream.
- A bilingual **Tandoory Tales Way** section outlining ingredients, visible preparation, and care.
- Direct WhatsApp feedback link so visitors can help shape the business.
- Seven optimized food and devotional illustrations are stored directly in the repository under `assets/` (no temporary image-hosting links).
- English / Hindi toggle for headings, all dish names, prices and descriptions, buttons, and contact messages.
- Tap any food item or signature pick to open an accessible detail popup with a larger illustrative photograph, flavour notes, preparation-style explanation, and WhatsApp enquiry.
- Five categories: Soya Chaap, Paneer & Mushroom, Veg Kabab, Tandoori Momos and Extra Loaded.
- Six signature picks and a ₹199 full-chaap-plate offer.
- All chaap flavours advertised as rolls for ₹20 extra.
- Phone numbers: 72100 80540, 93100 44152, 91776 86011.
- Delivery within 3 km for orders of ₹500+; serving pockets 16–23.

## Updating

Edit **index.html** in the GitHub web interface, then commit the change to `main`. GitHub Pages republishes at the *same URL*, so the printed menu QR does **not** need to change.

In the JavaScript section at the bottom:
- `sections` contains each menu item, its English/Hindi name, half/full price, preparation category, flavour profile, and image key.
- `flavours` contains bilingual short descriptions and flavour notes.
- `i18n` contains translations of all interface labels and general preparation descriptions.
- `upgradedPics` maps six signature dish types to optimized images in `assets/`; `pics` provides representative fallback images for other varieties.
- `waySteps`, `storyTitle`, `storyIntro`, `storyMiddle`, `storyQuality`, and related `i18n` strings control the translated story and preparation cards.
- `featured` controls which six items appear in the Signature Picks section.

Prices are based on the original counter-board photos. **Pudina Chaap is ₹130 half / ₹220 full**. Punjabi Chaap was confirmed available, but no price was supplied, so it appears as **Ask for price**. Do not invent its price.

Only **Tandoori Momos** are offered. The supplied board provided a price for Paneer Cheese Momo only; do not add other momo varieties or prices without confirmation.

## Photography

The main six highlighted food photos and devotional header are optimized `.webp` files in `assets/`, so they load from GitHub Pages without third-party expiration. These images were AI-generated or selected by the owner as *illustrative food photography* rather than documentation of the food actually prepared at the counter. Other menu photos use Pexels placeholders and have a fallback mechanism.

For a new image of a signature dish, replace the matching file in the GitHub `assets/` directory using the exact same filename. The URL and QR code remain unchanged.

## Food description accuracy

Descriptions explain the usual dish style and flavour, rather than asserting an exact proprietary recipe. Verify details of marinades, ingredients, dietary restrictions, and allergens at the counter before making more specific claims.

The iodine/tincture test detects added starch in paneer; it **does not establish protein content or overall paneer quality**.

## GitHub Pages

If needed, open **Settings → Pages** and select **Deploy from branch → main → /(root)**. The homepage is `index.html`, with no build tools or database needed.
