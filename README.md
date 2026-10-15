# Jolly Furnitures Ecommerce MVP

Responsive static storefront for Jolly Furnitures, Kongowea, Mombasa. Open `index.html` in a browser (keep the `images/` folder beside it) or upload both to any web host.

## Features
- 19 products with your real photos (`images/`), category filters, sorting, search and saved favourites
- Product page per item (`index.html#/product/ID`): enlarge image, quantity, Add to Cart, Buy Now, WhatsApp enquiry, share, related products, sticky Buy Now bar on mobile
- Cart saved in the browser; checkout form (delivery or pickup, validation, remembers returning customers) that sends a structured order to WhatsApp 0781 287 268
- Mobile bottom navigation, hero slider with swipe, customer reviews, how-it-works, visit/contact section with directions

## Edit your products
All products are in the `products` array near the bottom of `index.html`.
- **Prices are demo prices. Replace them with your real prices.** Use `price:null` to show "Price on request".
- To add a product: put a photo in `images/`, add a line to the array with a new `id`.
- `fit:"contain"` suits white-background photos; `fit:"cover"` suits lifestyle photos.

## Notes
- No database, payment or admin yet. Orders are composed in WhatsApp for the customer to send.
- Product descriptions are written from the photos. Confirm materials and sizes and edit as needed.

## Delivery fees
The cart has a delivery-area menu with a fee per area (see `DELIVERY` in `index.html`). Fees are the **median** of local Mombasa mover/transport asking prices on Jiji.co.ke (Oct 2026). Nyali and Tudor KSh 12,000; Mombasa Island KSh 13,500; Bamburi KSh 14,000; Kisauni KSh 16,000; Changamwe KSh 19,000. Areas with too few listings (Kongowea, Likoni, Mikindani, Mtwapa, Diani) use the overall local median, KSh 13,500. These are house-moving prices, so adjust them to what you actually charge to deliver furniture.
