# Michael Kariuki

Full-stack TypeScript developer building web products with React, Node and Cloudflare Workers.

I own features end to end: data model, API, UI, deploy. Most of my recent work is production software running on Cloudflare's edge - D1 databases, R2 storage, cron jobs and payment callbacks - with the same tests and migration discipline I would use on a team.

## Experience

**Full-Stack Engineer - OpenSlot** · Nairobi · Feb 2024 - Sep 2026

Salon and spa operations platform - scheduling, point of sale, Stripe payments, messaging and a consumer marketplace - live at [openslot.io](https://openslot.io/) with an Android app on [Google Play](https://play.google.com/store/apps/details?id=com.openslot.businessapp) and docs at [support.openslot.io](https://support.openslot.io/).

- Owned the real-time messaging layer: WebSocket Durable Objects with Momento pub/sub, a unified inbox shared by staff and clients, attachments served from R2.
- Wrote and maintained the customer documentation site at [support.openslot.io](https://support.openslot.io/) - product guides, walkthroughs and screenshots for every module.
- Introduced Playwright end-to-end testing for the partner dashboard and kept it green through redesigns: 122 specs and 586 tests across 23 feature areas.
- Contributed to a Hono and TypeScript API on Cloudflare Workers: 58 domain modules, 1,222 routes over Postgres with schema-per-tenant row-level security and 146 migrations.
- Contributed to Stripe Connect onboarding, Terminal tap-to-pay, webhook reconciliation, refunds, disputes and payout eligibility.
- Contributed to omnichannel notifications: Twilio SMS and virtual numbers, WhatsApp channels, queued transactional email.
- Authored the team's AI context-engineering standard: repo-wide guides and agent instructions adopted across the services.

## Selected work

- **[FixTrack](https://fixtrack.waigurumichael252.workers.dev)** - repair-shop operations for Kenyan SMEs: quotations, customer approval links, balance-guarded payments, M-Pesa STK Push with callback reconciliation, unmatched-payment review, email/SMS/WhatsApp quote notifications, invitations and email verification. React + Vite frontend, Hono Worker API, D1, R2, 15 Miniflare regression tests.
- **[Pulse](https://pulse.waigurumichael252.workers.dev)** - uptime and latency status page. Five-minute cron sweeps with per-monitor status and body assertions, 24h/7d/90d uptime windows, p95 latency, 90-day heatmap, SVG badges and an incident timeline. One Worker, one D1 database, no third-party monitoring.
- **[Chess Puzzles](https://chess-puzzles.waigurumichael252.workers.dev)** - offline-first chess tactics trainer with adaptive Elo and a 2,000-puzzle catalogue. Expo / React Native / TypeScript, 180 passing tests.
- **[Portfolio](https://michaelkariuki.waigurumichael252.workers.dev)** - zero-dependency kinetic-typography site in hand-written HTML, CSS and JavaScript.

## Stack

TypeScript - React - React Native / Expo - Next.js - Node - Hono - Express - SQL - Postgres - Cloudflare Workers - D1 - R2 - Queues - Durable Objects - Stripe - Cognito - Twilio - Momento - Vitest - Playwright

## Currently

- Shipping small, production-shaped products on Cloudflare to keep the stack current.
- Looking for full-stack or product engineering roles, Nairobi or remote.

## Contact

- Portfolio: https://michaelkariuki.waigurumichael252.workers.dev
- LinkedIn: https://www.linkedin.com/in/michael-kariuki-dev/
- Email: waigurumichael252@gmail.com
