# Bizgrowth Labs Website

Official website for **Bizgrowth Labs** — a personal branding, content marketing, and social media management agency based in Hyderabad, Telangana, India.

## Structure
- `index.html`: Self-contained, production-ready 5-page application (`Home`, `Our Services`, `Founder`, `Blogs`, `About Us`) with all assets embedded and responsive Tailwind CSS styling.

## Configuration
Open `index.html` and locate `BIZGROWTH_CONFIG` in the `<script>` section to update:
- `whatsappNumber`
- `businessEmail`
- `phoneNumber`
- `instagramUrl`
- `calendarBookingUrl`

Search `<head>` for `G-XXXXXXXXXX` and `google-site-verification` to enable Google Analytics (GA4) and Google Search Console.

## Deployment
Push this folder to a Git repository and deploy directly as a static site on **GitHub Pages**, **Vercel**, **Netlify**, or **Cloudflare Pages** (no build step required).
