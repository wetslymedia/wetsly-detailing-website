# Wetsly Auto &amp; Marine Detailing — Landing Page

A luxury, high-converting, single-file landing page for **Wetsly Auto &amp; Marine Detailing**,
a premium mobile boat, yacht &amp; auto detailing business serving all of Rhode Island.

Everything lives in **`index.html`** — HTML, CSS, and JS are embedded, so it's fast and easy to host anywhere.

---

## ✅ Before you go live — 3 things to paste in

Open `index.html` and search (Ctrl/Cmd + F) for each placeholder:

| # | Search for | Replace with | Where to get it |
|---|------------|--------------|-----------------|
| 1 | `YOUR_WEB3FORMS_KEY_HERE` | Your Web3Forms access key — replace **every** occurrence | Free at [web3forms.com](https://web3forms.com) — enter your email, they email you a key |
| 2 | `YOUR_PIXEL_ID_HERE` | Your Meta Pixel ID — replace **every** occurrence | [Meta Events Manager](https://business.facebook.com/events_manager) → Data Sources → your Pixel |

> Tip: use your editor's "Replace All" so you never miss one.

> The form emails you every submission. The Meta Pixel fires **`Lead`** on a successful form submit and **`Contact`** when someone taps a click-to-call button — both ready for your Meta Ads optimization.

---

## 🖼️ Swapping in your real assets

- **Logo** — the header, hero, and footer use a placeholder chrome SVG logo. To use your real logo, drop the file in an `assets/` folder and replace the inline `<svg>…</svg>` (marked with comments) with:
  ```html
  <img src="assets/logo.png" alt="Wetsly Auto & Marine Detailing">
  ```
- **Gallery photos** — search for `SLOT 1` … `SLOT 6` and replace each placeholder tile with:
  ```html
  <img src="assets/gallery-1.jpg" alt="Boat detailing before and after">
  ```
- **Testimonials** — placeholder text is in the "TESTIMONIALS" section; edit names/quotes directly.

---

## 🚀 Deploy for free

### Option A — Netlify (easiest, drag &amp; drop)
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag this whole folder onto the page. Done — you get a live URL instantly.
3. To connect a custom domain: **Site settings → Domain management**.

Or connect this Git repo: **Add new site → Import an existing project → pick this repo**. `netlify.toml` is already configured.

### Option B — Vercel
1. Go to [vercel.com/new](https://vercel.com/new)
2. Import this Git repo (no build settings needed — `vercel.json` is included).
3. Deploy. Add a custom domain under **Settings → Domains**.

---

## 📞 Business details baked in
- **Phone:** +1 (401) 362-9364 (click-to-call everywhere)
- **Service area:** All of Rhode Island
- **Services:** Boat &amp; Yacht Detailing, Auto Detailing, Ceramic Coating, Interior Deep Clean, Oxidation Removal &amp; Polish

---

## 🧩 What's included
- Mobile-first responsive design (built for Meta Ads mobile traffic)
- Sticky mobile bottom bar: **Call Now** + **Get Quote**
- Smooth scroll animations &amp; premium hover effects
- SEO title + meta description, Open Graph tags
- Web3Forms-connected quote form with validation &amp; inline success message
- Meta Pixel base code + Lead/Contact events
