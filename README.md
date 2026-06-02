# Halluna — Official Website

Static, English-only website for **Halluna**, an AI companion app for women. It
is built for App Store and Google Play submission, including Marketing URL,
Support URL, Privacy Policy, Terms, and the account/data-deletion page Google
Play requires.

## Pages

| File | Purpose | Use as |
|------|---------|--------|
| `index.html` | Landing / marketing page | **Marketing URL** |
| `support.html` | Support + FAQ | **Support URL** |
| `privacy.html` | Privacy Policy | **Privacy Policy URL** |
| `terms.html` | Terms of Service | **Terms / EULA URL** |
| `delete-account.html` | Account & data deletion | **Data deletion URL** (Google Play) |
| `styles.css` | Shared styling | — |
| `STORE-LISTING.md` | Ready-to-paste store copy | App Store / Play form fields |

## ⚠️ Replace before publishing

1. **Support email** — currently `support@halluna.app` (placeholder) across all
   pages. Find & replace with your real support inbox.
2. **Download buttons** — the App Store / Google Play links in `index.html` point
   to `#`. Replace with your real store URLs once the app is live.
3. **Domain** — in `STORE-LISTING.md`, replace `YOUR-DOMAIN` with your actual host.
4. **Effective dates** — Privacy Policy and Terms use `June 2, 2026`. Update if needed.
5. **App icon** — the header logo is a custom Halluna mark. Swap it for the final production icon if needed.

> **Legal note:** The Privacy Policy and Terms are solid, store-ready drafts but are
> not legal advice. Have them reviewed by a qualified lawyer before launch,
> especially the GDPR/CCPA and AI-processing sections.

## Hosting

Pure static HTML/CSS — no build step. Host anywhere:

- **Drag-and-drop:** Netlify, Vercel, Cloudflare Pages.
- **GitHub Pages:** push this folder to a repo, enable Pages.
- **Any web server:** upload all files to the web root.

To preview locally:

```bash
cd halluna
python3 -m http.server 8000
# open http://localhost:8000
```

## Company

Future Sense Tech (Hong Kong) Limited
D-U-N-S: 765260046
Room A5, 7/F, Astoria Building, No. 34 Ashley Road, Tsim Sha Tsui, KL, Hong Kong
