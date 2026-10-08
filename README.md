# GoodBull Moving Company — GitHub Pages website

Built for https://goodbullmoving.com as a labor-only moving services website. No build system required.

## Updated website notes
- Added a customer testimonials section with three five-star U-Haul Moving Help reviews transcribed from the supplied screenshots (Kyle T., Allison R., Jakob P.). The section links directly to the Moving Help customer reviews URL. Review text is not embedded via an iframe because third-party pages may prohibit iframe display. Please verify wording and permission/attribution before publication.
- The estimator now supports **loading and unloading at different locations**; this triggers custom pricing review and asks for the unloading ZIP. Customer arranges and drives their own transportation.
- The PODS service card uses an actual PODS photo; the couch-on-stairs photo appears under in-home moving labor.
- Header logo is larger on desktop with a mobile-specific scale.

## Before going live
1. **Formspree connected.** The quote form posts via JavaScript to `https://formspree.io/f/maeqobbp`. After publishing, send a real test request and confirm it reaches your Formspree submissions dashboard and email.
2. **Confirm pricing and policies.** Site currently lists $85/hour for two people, a two-hour minimum, and generally $25 per charged stair floor. Confirm travel charges, time rounding, cancellation policies, and the specialty item review wording before launching.
3. **Confirm photo use rights / permissions.** Real job photos are included as supplied. Confirm permission for identifiable crew members, customers, license plates, and private homes before publication. Consider cropping/obscuring visible plates and identifiable details.
4. **Ensure the description matches authorized work.** This site offers labor only and makes no transportation offer.
5. **Phone added:** (979) 220-9626 is linked for calls in the header and homepage, and for calls/texts in the footer. Optional: add a business email, Google Business Profile, and more customer testimonials.

## GitHub Pages deployment
- Upload everything inside this folder to the **root** of your GitHub repository (including `index.html`, `styles.css`, `script.js`, `CNAME`, and `assets/`). Do not upload only the ZIP itself.
- Settings > Pages > Deploy from a branch > `main` > `/ (root)` > Save.
- Custom domain: `goodbullmoving.com`; `CNAME` file included.
- Namecheap A records `@` => 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153; CNAME `www` => `goodbullmoving.github.io` (assuming GitHub username is `goodbullmoving`). Remove conflicting parking/redirect records, but preserve any email DNS records.
- After DNS verification, enable HTTPS in GitHub Pages settings.
- Check the site on mobile and desktop; submit a real test lead to verify delivery.

## Files
- `index.html` — homepage, services, pricing, gallery, FAQ, quote form.
- `styles.css` — all layout and branding.
- `script.js` — instant quote calculator and Formspree submission.
- `assets/` — optimized real project photos, supplied logo, edited jacuzzi video.

The video is an edited 19-second muted excerpt to minimize bandwidth. A separate specialty demonstration does not imply transportation services are offered.
