# QODS STORE

Multilingual AL QODS STORE storefront for Casablanca, in Arabic, French, and English. A product-photo-led fashion campaign uses GSAP and ScrollTrigger for its hero scenes, image reveals, and scroll movement, with an integrated catalog editor, cart, and WhatsApp checkout.

## Start

You can open `index.html` directly in a browser. Products, cart, and layout use classic browser scripts and work from a `file://` address. GSAP, ScrollTrigger, and Google Fonts load from public CDNs; cinematic motion and typography need an internet connection. For development, install dependencies and run `npm run dev`.

## Product editor

Select the small pencil icon in the header. Each product has its own image field; replacement uploads affect only that product. The editor stores products and cart contents in the current browser's local storage. Uploaded images are resized and compressed before saving. This is a front-end demo: products are saved per browser/device, not to a shared server.

## Checkout

The checkout button opens a WhatsApp message to QODS STORE at +212 604 55 40 28. The message includes cart items and total, with a prompt to enter the delivery city.
