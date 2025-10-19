
# Orbridge Careers Training - Lead Generation Website

This is a minimal Vite + React + Tailwind website prepared for quick deployment.
It includes:
- Lead-capture forms (use Formspree or your backend)
- WhatsApp CTA buttons
- JSON-LD LocalBusiness schema
- English and Telugu app files

## Quick start (locally)
1. Install deps:
   npm install
2. Run dev server:
   npm run dev
3. Build for production:
   npm run build

## Important: Replace placeholders
- Open `src/config.js` and set:
  - FORM_ACTION: your Formspree endpoint or your backend URL
  - CONTACT_PHONE and CONTACT_EMAIL
  - GA_MEASUREMENT_ID etc.

## Deploy
- Push to GitHub and connect to Vercel or Netlify. Both detect Vite automatically.

## Formspree
1. Create a free form at https://formspree.io
2. Copy the form endpoint (looks like https://formspree.io/f/{id})
3. Replace FORM_ACTION in `src/config.js`

