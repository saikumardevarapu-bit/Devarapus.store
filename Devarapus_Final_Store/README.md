# Devarapus — Final Store Package

## What is included
- Responsive storefront
- Home & Kitchen + Electronics
- Search, category filters and sorting
- Product cards and starter catalogue
- Cart with quantity controls
- Checkout form
- COD / UPI selection
- Order confirmation and order number
- Demo admin panel
- Browser-local demo mode
- Supabase-ready database schema/config
- Netlify-ready hosting file

## Test the site
Open `index.html` in Chrome.

Demo admin:
- Click **Admin**
- Email/password prompt is simplified for demo mode.
- Demo password: `admin123`

## Important for real online orders
A static website cannot securely store shared customer orders by itself. This package therefore includes a Supabase-ready backend setup.

1. Create a free Supabase project.
2. Run `supabase.sql` in SQL Editor.
3. Put your project URL and anon key in `config.js`.
4. Deploy this folder to Netlify, Cloudflare Pages or Vercel.

Do NOT put a Supabase service_role key in `config.js`.

## Domain
After hosting, connect a domain such as:
- devarapus.in
- devarapus.com

The domain is optional; the hosting can be free.

## Payments
The current checkout records COD or UPI as the selected method. A real payment gateway (Razorpay/Cashfree/etc.) should be connected before accepting online payments. Gateway fees apply per transaction.
