LSJ SILKS WEBSITE — DEMO / STARTER
====================================
Files:
- index.html
- lsj-logo.png

Features:
- Responsive storefront inspired by modern saree e-commerce layouts.
- Search, category filters, selected-sale filter.
- Product details modal.
- Cart stored in the browser.
- WhatsApp cart ordering to 7013096613.
- +91 70959 58417 displayed for call + WhatsApp.
- Demo admin product manager via the "Admin" footer link.
- Admin demo password: LSJ2026 (CHANGE BEFORE PUBLISHING).

IMPORTANT BEFORE LAUNCH:
1. Replace demo product names/prices with real LSJ Silks products.
2. Upload real saree photos and use image URLs or a proper image-storage backend.
3. For secure admin access, use a server/database authentication system; the included password is only a browser demo.
4. For online payments, connect a payment gateway such as Razorpay/Stripe with a secure server. Do not put secret payment keys in this HTML.
5. Add shipping, returns, privacy policy, terms, GST/business details and delivery areas.
6. Test WhatsApp links and checkout on Android/iPhone.

The design is inspired by common e-commerce patterns and the requested Sudathi reference, not a copy of their code or branding.

Customer delivery address form: name, mobile, PIN, house/street, area, city and state. The completed order and address are sent to WhatsApp 7013096613. COD is not available; prepaid only.


PAYMENT: PhonePe/UPI QR added from customer-provided screenshot. UPI ID: reddyvarilatha8-1@okhdfcbank. COD is not available; prepaid only. The site does not automatically verify UPI payment; the customer must tap 'I HAVE PAID' after payment and the order is sent to WhatsApp.

UPDATED: Customer order confirmation is sent to both WhatsApp numbers: +91 70959 58417 and 7013096613.

FINAL CHECKOUT FLOW: Adding a saree opens the cart only. Customer can add/change quantities. Checkout page is shown only after pressing CHECKOUT. Back to Cart is available. Address + QR payment are in the checkout step.


CORRECTED PRODUCT-SELECTION FLOW:
- Clicking ADD on a saree only adds it to the cart and does NOT open the cart or checkout.
- Customer can continue selecting as many required sarees as needed.
- Cart icon shows selected quantity.
- Customer opens the cart when finished selecting.
- Customer reviews/changes quantities.
- Only then does the customer press CHECKOUT — FINAL STEP.
- Address + PhonePe QR/payment confirmation are shown only in the final checkout step.

UX FIX: Product selection no longer shows a browser alert. After selecting a saree, the ADD button changes to a quantity control (− quantity +). Customers can continue selecting other sarees. Checkout remains the final step from the cart.

Checkout button/text is simply shown as CHECKOUT. No 'FINAL STEP' wording is displayed.

UPDATED: No browser alert/pop-up is used when selecting sarees. ADD silently updates the quantity on the product card. Checkout validation uses an inline message instead of a browser popup.

FIXED: Product cards were not rendering because a JavaScript syntax error in the admin function stopped the whole script. The admin function is repaired and localStorage loading is now protected so the demo products always display.

UPDATED PRODUCT SELECTION UI:
- ADD appears on the product image when quantity is 0.
- After adding, ADD becomes an over-image quantity control: − 1 +.
- + increases quantity and − decreases quantity.
- No browser popup appears when selecting products.
- Customer can continue selecting products; checkout remains separate.

UPDATED UI:
- VIEW button is now fully visible on the left/bottom action row.
- ADD / quantity control is anchored to the product image, so it cannot overlap VIEW.
- When selected, the image control shows − quantity +.

UPDATED CATALOG:
8 sarees now use real web-sourced product/reference images and matching product titles instead of placeholder LSJ images.
Important: these are reference images from third-party listings; for commercial LSJ use, replace them with photos you own or have permission to use.
