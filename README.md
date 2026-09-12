# WEKND.SPIRIT — V4.1

Premium event discovery + ticketing demo for WEKND.SPIRIT.

## V4.1 highlights
- Original event-specific poster artwork for every showcased experience.
- Actual WEKND.SPIRIT WS monogram + wordmark used in the UI, splash and ticket surfaces.
- Mobile-first event discovery with horizontal featured experiences and a vertical event grid.
- Event details before ticket selection.
- Ticket quantities, customer details, UPI app selection, card-brand detection and payment processing demo.
- Client-side scannable QR ticket using QRCode.js.
- Organizer camera scanner with VALID / INVALID / ALREADY USED demo states.
- Profile, photo upload, bookings and passwordless OTP demo (OTP: 123456).

## Production note
Payments and ticket issuance are intentionally demo-only. A live deployment should create Razorpay orders server-side, verify signatures, validate webhooks/idempotency, and keep ticket/check-in state on a backend.
