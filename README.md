# Fiomis — Choose Better

> **Thanks for visiting!** Fiomis is a commercial project, so its source code lives in a private repository.
> If you're reviewing my application and would like to see the code, I'm happy to share it.
>
> **[Request access to the source →](mailto:thisismd.riyash@gmail.com?subject=Fiomis%20source%20code%20access%20request&body=Hi%20Muhammed%2C%0A%0AI%27d%20like%20to%20review%20the%20Fiomis%20source%20code.%20My%20GitHub%20username%20is%3A%20)**
> — or message me on [LinkedIn](https://www.linkedin.com/in/muhammedriyash). Send your GitHub username and I'll add you as a read-only collaborator.

---

## What it is

Fiomis is a headless clothing store for the Indian market (hoodies, oversized tees, maxis), built as a TypeScript monorepo:
an Astro storefront on a Medusa v2 commerce back end with a custom admin. I design, build and maintain it on my own.

| | |
|---|---|
| **Storefront** | Astro (SSR/SSG with islands), React, Nano Stores, GSAP, Lenis, Babylon.js |
| **Back end and admin** | Medusa v2, Node.js 20, TypeScript, PostgreSQL 16, Redis 7 |
| **Payments and services** | Razorpay (server-side webhook completion), Resend email, Sentry, Cloudflare R2 |
| **Shared code** | `@fiomis/shared`: one order-status model and money types used by both apps |
| **Quality** | GitHub Actions CI, Playwright browser checks across five viewports, 40+ test files |
| **Infra** | Docker Compose for local Postgres and Redis |

## Highlights

- **Checkout and payments** — Razorpay orders are completed by a server-side webhook, never trusted from the browser.
- **Inventory** — an append-only stock ledger that records every change with its reason.
- **India-first tax** — GST-aware pricing and invoicing, with packing slips and an orders CSV export for accounting.
- **Admin security** — OTP sign-in, two-factor authentication and role-based access to admin screens.
- **Storefront experience** — a scroll-driven 3D brand story, a shared motion system, responsive image pipeline and SEO structured data.
- **Accessibility** — focus trapping in overlays, a skip link and 44 px touch targets across mobile layouts.

## Status

In active development since June 2026 (140+ commits). Not yet launched.

---
In active development since June 2026 (139 commits on the main branch). Not yet launched.
**Muhammed Riyash J** · Senior Full-Stack Developer · Bengaluru, India
[Portfolio](https://md-riyash-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/muhammedriyash) · [GitHub](https://github.com/MuhammedRiyash)
