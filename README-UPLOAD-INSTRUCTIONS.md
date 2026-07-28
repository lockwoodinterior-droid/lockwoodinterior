# Lockwood Interiors — Updated Website

## What changed
- Repositioned homepage to speak to architects, interior designers, builders/contractors and retail clients, not just homeowners
- New page: `trade.html` — trade pricing, sample kits, spec support, dedicated account manager
- Fixed the broken "Sainik Farm" project image path
- Rewrote About, Services and Projects with fuller content and clearer structure
- New Contact page with a proper enquiry form (client-type dropdown) plus click-to-call/WhatsApp/email
- Consistent design system (colors, type, a herringbone-pattern motif that echoes your actual product) across every page

## Files in this folder
index.html, about.html, services.html, projects.html, trade.html, contact.html, style.css, script.js

## How to publish (your site is hosted on GitHub Pages)
1. Open your repo: `lockwoodinterior-droid/lockwoodinterior` on GitHub
2. Upload these files, replacing the existing ones with the same names (add `trade.html` and `style.css`/`script.js` as new files)
3. Keep your existing `/assets/images/` folder and `company-profile.pdf` as they are — the pages link to them directly
4. Commit — GitHub Pages will redeploy automatically within a minute or two

## Two things you need to do to make it fully functional
1. **Contact form**: it currently posts to a placeholder. Create a free account at formspree.io, make a form, and paste your form ID into the `action="https://formspree.io/f/YOUR_FORM_ID"` line in `contact.html`. Takes about 3 minutes, and submissions land in your email.
2. **Photos**: the site reuses your existing 5 project photos. For the best result, add more real project photography — especially a strong hero/banner shot and a few installation/site photos — since real work sells better than any stock image. Drop new files into `/assets/images/` and reference them the same way the existing ones are referenced.

## Optional next steps
- Add a Google Business Profile + embed a map on the Contact page
- Add 2–3 short case studies (before/after + sq.ft. + finish used) — architects and contractors respond well to specifics
- Consider a blog/insights page for SEO once the core site is live
