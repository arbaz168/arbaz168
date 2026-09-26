# Arbaz Khan

**Senior Full Stack Engineer · .NET, React, AWS · Payments and real-time systems**

I design, build and run production SaaS end to end: APIs, frontends, cloud infrastructure, payments and the on-call work that keeps them healthy. 6+ years shipping ASP.NET Core and React to real users, most recently as the sole engineer behind [Sponsa](https://sponsa.app).

---

## Sponsa · creator monetization platform

Live in production with 2,000+ registered users. I own the whole stack: architecture, backend, frontend, infrastructure, releases and incident response.

**Engineering highlights**

- **Multi-provider payments:** PayPal, Ryft and Stripe Connect behind one payment flow, with multi-currency support and cached FX rates.
- **Reliable webhooks:** an idempotent store-and-retry inbox with dead-lettering, so duplicate deliveries and provider outages are handled safely.
- **Reconciliation:** background jobs that check payment state against providers and log exactly what they changed and why.
- **Real-time overlays:** WebSocket updates that drive live stream alerts and goal progress in OBS.
- **Integrations:** OAuth with YouTube, Twitch and Twitter, with token refresh and failure handling.
- **Media pipeline:** S3 and CloudFront delivery with a Lambda that resizes images on upload.
- **Observability:** structured logging with Serilog and Seq, alerting on payment failures, Sentry on the frontend.
- **Keeping it current:** upgraded to .NET 10 and EF Core 10, React 19, Vite 8 and Tailwind 4.
- **Delivery:** separate staging and production environments, GitHub Actions CI/CD for the frontend, xUnit test suite on critical payment and auth logic.

---

## LiveHire · managed talent hiring platform

[livehire.gentechs.io](https://livehire.gentechs.io) · Lead Full Stack Engineer · .NET 10, Next.js, React, SQL Server, SignalR

Companies hire pre-vetted developers and run the whole engagement in one place: chat and calls, time tracking, milestones and billing. I took over an existing codebase and rebuilt it across two APIs and two frontends.

**Engineering highlights**

- **Security pass on inherited code:** closed authorization gaps in real-time chat, moved auth to JWTs in HttpOnly cookies, upgraded legacy password hashes at sign-in without forcing resets, and took signing keys out of source.
- **Billing redesign:** replaced taking the full engagement value at hire with an escrow model. Funds are reserved at hire and settled per billing period against approved time, with every movement in a transaction ledger.
- **Production schema under EF Core migrations:** baselined a live SQL Server database that had only ad hoc scripts, added the 63 indexes it was missing, and shipped idempotent rollout scripts.
- **Real-time workspace:** SignalR chat with presence, typing, edits and search, video calls, and pushed notifications in place of polling.

---

## Open source

- **[aspnetcore-webhook-inbox](https://github.com/arbaz168/aspnetcore-webhook-inbox):** production-style payment webhook handling in ASP.NET Core 10. Signed delivery, database-level deduplication, leased workers that scale out safely, retries with backoff and dead-lettering. 31 tests, CI on GitHub Actions.

---

## Stack

| Area | Tools |
|---|---|
| Backend | C#, ASP.NET Core (.NET 10), Entity Framework Core, SQL Server, PostgreSQL, REST, WebSockets |
| Frontend | React, Next.js, TypeScript, JavaScript, Tailwind CSS, React Query |
| Cloud and DevOps | AWS (EC2, S3, CloudFront, Lambda), Azure, Docker, Kubernetes, IIS, GitHub Actions, Azure DevOps |
| Payments | PayPal, Stripe Connect, Ryft |
| Quality | xUnit, Vitest, Serilog, Seq, Sentry |

---

## Experience

| Role | Company | Period |
|---|---|---|
| Lead Full Stack Engineer | Sponsa | Nov 2023 to present |
| Lead Full Stack Engineer | LiveHire | Aug 2025 to present |
| Lead Full Stack Engineer | CoinBitSolutions | Jan 2020 to present |

**Other projects**

- **New Horizon Medical Solutions:** US healthcare portal for patient management, clinic registration and benefits verification.
- **KryptoBox:** cryptocurrency exchange platform.

---

## Contact

[LinkedIn](https://linkedin.com/in/arbazzkkhan) · [Email](mailto:arbaz.bajay@gmail.com) · [sponsa.app](https://sponsa.app)

Open to senior remote roles and relocation.
