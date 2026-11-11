# Champions Cricket Academy Website

Single-page React website (React 18 + htm + Tailwind via CDN) with an admin login at `/#admin`.

## Files
- `index.html` – the full website
- `supabase/schema.sql` – tables and security rules (run once in Supabase SQL Editor)
- `netlify.toml` – Netlify settings

## Setup
1. Supabase Dashboard > SQL Editor: run `supabase/schema.sql`.
2. Supabase Dashboard > Authentication > Users: create the admin user (email + password).
3. Deploy: push this repo to GitHub and connect it to Netlify, or drag the folder into Netlify Deploy.

## Edit content
Open `index.html` and change:
- `WA` (WhatsApp number), `NAME` (academy name)
- `IMG` (image URLs for hero, programs, coaches, gallery)
- the data lists near the top (`progs`, `coaches`, `sched`, `fees`, `faqs`, etc.)
- `SB` and `KEY` (Supabase URL and publishable key)

Replace the sample coach names, achievements, reviews, fees and contact details with the academy's real information before going live.
