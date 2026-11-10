# Reply Nara — £0 commercial launch checklist (10 November 2026)

## Prepared (not yet published commercially)
- Static site: `index.html`, `partners.html`, `privacy.html` and browser-only demo
- General enquiries via mailto only; no visitor form, backend, payments or analytics
- `robots.txt` and meta robots set to noindex until commercial launch is approved
- Security response headers for Netlify; Render may require equivalent headers configured in its dashboard

## Required operator actions and approvals
1. **Host**: Authorise a free commercial static hosting provider (Render Static Site or Netlify Free). Confirm free usage limits and commercial terms. A provider login may be required. Do NOT host commercial operation on Vercel Hobby.
2. **Identity**: Confirm who legally operates Reply Nara and publish required name and address / appropriate service address, updating the final privacy notice and trading disclosures. Do not fabricate personal identity.
3. **Brand**: Check Companies House and UKIPO trademarks before promoting Reply Nara as a cleared trademark.
4. **Privacy**: Finalise lawful basis, retention, Gmail use, service providers, rights request process, controller contact, security and ICO fee/self-assessment. Replace the clearly marked draft privacy page.
5. **Enquiry collection**: Keep mailto-only until legal notice is completed. If later deploying a form, choose a secure processing provider, define retention and anti-spam, prevent collecting other businesses' customer records, and assess processors/contracts.
6. **Payments**: Connect your own Stripe account (or another regulated payment provider), complete identity, bank verification and any business checks. Finalise scope/contract, cancellation and invoice details before enabling any checkout. No fake checkout, fake card input or payments collected by the static site.
7. **SEO release**: Once the above are complete, replace meta `noindex,nofollow` with `index,follow`, change robots.txt to Allow: /, create a canonical sitemap with the actual public URL, connect Google Search Console and test anonymous access.
8. **Testing**: Confirm mobile, keyboard, privacy links, HTTP responses, mailto, 404, headers and that no fictional messages transmit data.

## Deployment
- **Netlify**: drag-and-drop the *contents* of the zip, or upload this folder using a connected Netlify account. Its `_headers` configuration applies.
- **Render**: create a free Static Site backed by a Git repository; publish directory is `/` (or the project folder). Static assets don't need a build step. Header configuration differs from Netlify.

## Explicitly not completed
- Commercial-host account authorization or deployment
- Legal identity, final privacy/legal disclosures and ICO decisions
- Payment provider activation, real visitor form, business contracts
- Search indexing or third-party public access verification
