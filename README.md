# Boozy Bites storefront

This is a self-contained mock storefront inspired by the Boozy Bites Shark Tank deck. Open `index.html` in a browser to preview it.

The `assets/` folder contains the supplied Boozy Bites poster, package lineup, and flavor-lid artwork. The real package artwork is used in the hero and product cards.

## Connect Supabase

1. Run `supabase-schema.sql` in the Supabase SQL Editor.
2. In `index.html`, set `SUPABASE_URL` to the project URL and `SUPABASE_ANON_KEY` to the public anon key. Do not put a service-role key in this file.
3. The waitlist form will then insert emails into `public.waitlist`. The cart currently remains a local mock cart, which is appropriate for the project prototype.

## Current prototype behavior

- 21+ age gate
- Six flavor cards with a build-your-own six-pack flight for $21.99
- Add-to-cart drawer with quantity controls and local persistence
- Waitlist form with optional Supabase persistence
- Wholesale/business inquiry form for bars, shops, grocers, and events
- Responsive mobile layout
