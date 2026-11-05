# Tandoory Tales — Interactive Digital Menu

**Live website:** https://poplu2525.github.io/tandoory-tales-menu/

A mobile-first, bilingual (English / Hindi) digital menu for **Tandoory Tales**, Best Mega Mall, Rohini Sector 24, Delhi.

## Features
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
- `pics` maps category/flavour keys to remote representative food photos.
- `featured` controls which six items appear in the Signature Picks section.

Prices are based on the original counter-board photos. **Pudina Chaap is ₹130 half / ₹220 full**. Punjabi Chaap was confirmed available, but no price was supplied, so it appears as **Ask for price**. Do not invent its price.

Only **Tandoori Momos** are offered. The supplied board provided a price for Paneer Cheese Momo only; do not add other momo varieties or prices without confirmation.

## Photography

The current website uses illustrative, externally hosted Pexels food photography (not actual Tandoory Tales plated dishes). The popup makes this clear. The Pexels license allows commercial website use: https://www.pexels.com/license/. Replace images with real photos of each dish when available. External image hosting means photos may fail if the third-party source changes; the layout includes a fallback.

## Food description accuracy

Descriptions explain the usual dish style and flavour, rather than asserting an exact proprietary recipe. Verify details of marinades, ingredients, dietary restrictions, and allergens at the counter before making more specific claims.

The iodine/tincture test detects added starch in paneer; it **does not establish protein content or overall paneer quality**.

## GitHub Pages

If needed, open **Settings → Pages** and select **Deploy from branch → main → /(root)**. The homepage is `index.html`, with no build tools or database needed.
