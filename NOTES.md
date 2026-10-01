# NOTES

## 1. What I changed
- Rebuilt the single-page store into a more editorial, premium Mistvale storefront with a calmer visual hierarchy, stronger typography, more whitespace, consistent card treatment, sticky navigation, responsive layouts and a refined cart drawer.
- Kept the supplied product catalog, prices, stock, descriptions, ratings and simulated API behavior intact.
- Added a custom Mistvale wordmark SVG and a clearer hero treatment using the supplied hero image.
- Improved product browsing with search, category filters, sorting, sold-out-last ordering, wishlist persistence, quick view, cart quantity controls and a free-shipping progress bar.
- Improved checkout behavior so the demo does not navigate to the example endpoint; it explains that the endpoint is not connected.
- Fixed localStorage normalization, numeric id handling, stale asynchronous search responses, coupon eligibility/cap/minimum rules, shipping calculation, pincode error handling, and safe text rendering.
- Added accessible focus states, keyboard-friendly dialogs/drawer controls, semantic FAQ details, live status messages and reduced-motion support.
- Added SEO metadata and runtime JSON-LD for the store, products and FAQ.

## 2. Brand interpretation
- Deep forest green is the primary brand anchor.
- Warm cream and parchment provide the paper/tea-label feel.
- Saffron is reserved for small accents, badges and focus/CTA details.
- Fraunces is used for editorial display headings; Inter is used for navigation, forms and commerce UI.
- Motion is intentionally subtle: named-property transitions, no `transition: all`, and a reduced-motion fallback.

## 3. AI use
- I used AI assistance to restructure the UI, reason through the supplied bug list, and write the implementation.
- The exact prompts used for the code/design work are in `PROMPTS.md`.
- The supplied product/hero placeholder assets were retained rather than inventing product facts or unsupported imagery.

## 4. Testing
- Verified the generated HTML is present and self-contained apart from the Google Fonts request.
- Ran the page in a headless Chromium smoke test after implementation.
- Checked desktop and narrow mobile screenshots, search/filter/sort rendering, cart open/close, quantity controls, coupon validation, FAQ rendering and pincode validation.

## 5. Time spent
- Approximately 4 hours including inspection, implementation, visual refinement and browser smoke testing.

## 6. Constraints / assumptions
- The uploaded archive contained `index.html`, `NOTES.md` and image assets. A separate `BRAND.md` and `README.md` were not present in the archive I received, so I used the brand rules already reflected in the supplied draft/notes and did not invent missing business requirements.
