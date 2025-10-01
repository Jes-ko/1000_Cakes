# 1000 Cakes — Website

A simple bakery website for browsing cakes, placing orders (COD for MVP), and contacting the cake designer.

## Tech
- React + Next.js
- MongoDB (Atlas free tier or local Community)
- Deployed on Cloudflare Pages (free)

## Local development
1. Install dependencies: `npm install`
2. Start dev server: `npm run dev` (opens http://localhost:3000/)
3. Build & run production locally (optional):
   - `npm run build`
   - `npm start`

## Environment variables
Create a `.env.local` file (not committed) and add what you need, e.g.:

MONGODB_URI=your_connection_string
NEXT_PUBLIC_SITE_NAME=1000 Cakes

## Deploy (Cloudflare Pages)
1. In Cloudflare → Workers & Pages → **Pages** → **Create a project** → **Connect to Git** (select this repo).
2. Choose the **Next.js** preset and deploy. Every push to `main` will auto-deploy.

---

**License:** Personal/educational use. Update before going live commercially.