# Champions Cricket Academy Website

Single-page React website (React 18 + htm + Tailwind via CDN) with a Supabase-backed admin panel at `/#admin`.

## Files
- `index.html` - website and admin panel
- `supabase/schema.sql` - tables and security rules (run once in Supabase SQL Editor)
- `netlify.toml` - Netlify settings

## Setup
1. Supabase > SQL Editor: run `supabase/schema.sql`.
2. Supabase > Authentication > Users: create the admin user (email + password).
3. Deploy: push to GitHub and connect to Netlify, or drag the folder into Netlify Deploy.

## Admin panel (/#admin)
- Dashboard: live counts and recent enquiries
- Enquiries and Messages: everything submitted from the website
- Students: add and delete
- Gallery: add image URLs, they appear on the website gallery
- Programs: hide or show programs on the website

## Edit content
In `index.html` change `WA`, `NAME`, `IMG`, the data lists near the top, and `SB` / `KEY` (Supabase URL and publishable key).
