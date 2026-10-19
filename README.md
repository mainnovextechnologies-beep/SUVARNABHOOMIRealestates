# SUVARNABHOOMI Developers Pvt Ltd — React + Vite

## Run locally
1. Install Node.js 20+.
2. Open a terminal in this folder.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL shown by Vite.

## Production build
Run `npm run build`; output is created in `dist/`. Deploy the `dist/` folder to your static host.

## Demo behavior
WhatsApp, Call and Location buttons intentionally show a polite demo notice and do not initiate contact actions. Replace `demoAction()` in `src/main.jsx` with the intended live behavior before publishing:
- WhatsApp: open the configured `company.whatsapp` URL.
- Call: open `tel:+919030005019`.
- Location: open `company.maps`.
The enquiry form validates fields locally but does not send or store personal data. Configure a secure backend/CRM/email endpoint before going live.

## Content notes
- The six supplied images are in `public/images/`.
- Property cards are category previews with illustrative imagery, not verified inventory.
- The rating and excerpts are listing details supplied for this preview; verify against the live Google Business Profile before publication.
- Office hours are intentionally marked for confirmation.
- Add the production domain to canonical tags and sitemap once the domain is known. The included homepage metadata is a starting point; production SEO needs a real domain and server/static prerendering strategy for project detail pages.
