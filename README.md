# Palmivo V3 Enhanced

An adult-friendly, responsive, MD3-inspired language-learning platform for Russian and French.

## Included

- Multiple original lesson records per CEFR level A1-C2.
- Progress-state animations.
- Original inline SVG situation illustrations.
- Error review and explanations.
- Spaced-repetition scheduling.
- Local progress with an optional sync API contract.
- Stripe checkout API placeholders with server-side protection notes.
- Premium lesson gating.

## Important

Payment endpoints require environment variables and a real Stripe webhook before production use. The demo runs without them and does not process payments until configured.

## Deploy

Import into Vercel. Add STRIPE_SECRET_KEY, STRIPE_PRICE_PLUS, STRIPE_PRICE_PRO and STRIPE_WEBHOOK_SECRET only after configuring Stripe.
