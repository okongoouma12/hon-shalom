# Hon. Shalom Senate Campaign Page (Siaya County)

Static site: `index.html`, `style.css`, `app.js`. No build step.

## Deploy
1. Create a GitHub repo and upload these 4 files (or `git push`).
2. Netlify / Cloudflare Pages / GitHub Pages -> connect repo -> publish root folder.

## Edit before launch (top of `app.js`)
- `CAND` candidate name, `WA` WhatsApp number (254...), `PAYBILL`, `PIN`, `GFORM` Google Form link
- `MAN` manifesto pillars, `UPD` updates
- `ENDPOINT` a Formspree/Getform URL so volunteer, donation and survey submissions reach your email

## Notes
- Without `ENDPOINT`, submissions stay in the visitor's browser only.
- The Campaign Desk PIN is client-side (not secure). Use a real backend/login for production.
- WhatsApp broadcast opens a wa.me chat per recipient; true bulk sending needs the WhatsApp Business API.
- Verify the 30 ward names against the IEBC list.
