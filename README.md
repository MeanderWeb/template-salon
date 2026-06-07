# Meander Web — Salon / Beauty Template
Local business website template for salon and beauty businesses.
Built with vanilla HTML, CSS, and JavaScript.

## Usage
Replace all [BRACKET] tokens with client-specific content.
Deploy to Cloudflare Pages.

## Tokens to Replace
- [BUSINESS_NAME]
- [PHONE]
- [EMAIL]
- [ADDRESS], [CITY], [STATE], [ZIP]
- [TAGLINE]
- [YEAR_FOUNDED]
- [LICENSE_NUMBER]
- [PRICE_START]
- [BRAND_1], [BRAND_2]
- [BOOKING_URL] (remove button if N/A)
- [MAPS_EMBED_URL] — Google Maps Embed API URL, built dynamically by
  MockupGenerator from the client's address + a configured API key:
  https://www.google.com/maps/embed/v1/place?key=API_KEY&q=[ADDRESS]+[CITY]+[STATE]+[ZIP]&zoom=14
