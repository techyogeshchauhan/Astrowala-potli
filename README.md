# Astrowala — product landing pages

Standalone marketing pages in the style of astrowala.com/webinar25 (no site header/footer, no form, no video).

## Pages

| Page | Path |
|---|---|
| अभिमंत्रित नवग्रह शांति पोटली (₹5,100 + GST) | `navgrah-shanti-potli/index.html` |

## Editing

- **Order button / phone / payment link:** edit the `CONFIG` object at the bottom of `index.html`.
  Leave `paymentLink` empty to send orders to WhatsApp, or set it (e.g. an Instamojo link) to send buyers straight to payment.
- **Product photo:** replace `navgrah-shanti-potli/assets/potli.png` (square image works best).
- **Potli contents:** the "पोटली में क्या है?" list is marked with a `TODO` — confirm it matches the real product.
- Logo, trainer photo and background images load from `https://astrowala.com/assets/...`.

## Preview

Open `navgrah-shanti-potli/index.html` directly in a browser — no build step.
