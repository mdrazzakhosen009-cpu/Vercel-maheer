# MAHEER STORE Premium v12 — Vercel

This build keeps the MAHEER STORE Premium v12 website, Admin Panel, Turso database, Gemini AI order assistant, customer chats, reviews, products, agents, settings, payment settings and all existing UI/features unchanged.

## Vercel
Build is configured through `vercel.json` and `api/index.js`.

No Render configuration is required.

## Environment Variables
Add these in Vercel Project Settings → Environment Variables:

- TURSO_DATABASE_URL
- TURSO_AUTH_TOKEN
- GEMINI_API_KEY
- GEMINI_MODEL=gemini-3.1-flash-lite
- ADMIN_PASSWORD

`TURSO_AUTH_TOKEN` must have write permission.

## Domain
After deployment, add `maheerstore.com` and `www.maheerstore.com` under Vercel Domains, then configure the DNS records Vercel provides at the domain registrar.
