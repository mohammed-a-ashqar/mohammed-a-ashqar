## Hi, I'm Mohammed Alashqar 👋

Backend engineer from Gaza, Palestine. For 4+ years I've been building APIs and business systems with **PHP / Laravel** and **Node.js**: ticketing platforms, e-commerce, payment integrations and multi-tenant admin systems.

I care about code that the next developer can read: thin controllers, explicit domain rules, tests that describe behaviour, and CI that keeps it all honest.

### Tech

<p>
  <img src="https://skillicons.dev/icons?i=php,laravel,nodejs,ts,mysql,postgres,redis,docker,githubactions,tailwind,react&perline=11" alt="PHP, Laravel, Node.js, TypeScript, MySQL, PostgreSQL, Redis, Docker, GitHub Actions, Tailwind, React" />
</p>

**Backend:** PHP 8, Laravel (11/12), Node.js, REST APIs, Sanctum / Passport / JWT, queues & events<br>
**Data:** MySQL, PostgreSQL, Redis<br>
**Frontend (when needed):** Blade, Livewire, Filament, Alpine.js, Tailwind, React + Inertia<br>
**Tooling:** Git, GitHub Actions, PHPUnit / Pest, Pint, PHPStan, Docker, Postman / OpenAPI

### How I build

- **Thin controllers.** Requests are validated in FormRequests, turned into DTOs and handled by single-purpose Actions or Services.
- **Domain rules live in one place.** I use enums as state machines, value objects for money, and strategies for things that vary (pricing, payment providers).
- **Tests describe the behaviour**, and CI runs them with a style check and static analysis on every push.
- **Integrations fail safely.** That means signature-verified webhooks, idempotency keys, timeouts and retries.

### Featured work

| Project | What it shows |
|---|---|
| [**laravel-lazarus**](https://github.com/mohammed-a-ashqar/laravel-lazarus) | Self-healing Laravel package: a production exception becomes a failing reproduction test, a minimal patch, a green full suite and a draft pull request, never an auto-merge. `lazarus:scan` turns errors already in your logs into incidents, and free notifications arrive by email, Telegram, Slack or Discord. Secrets are redacted and edits run in a sandboxed git worktree. Works with Anthropic, OpenAI-compatible APIs or local Ollama. 136 tests on SQLite, MySQL, MariaDB and PostgreSQL, PHPStan at max level. |
| [**Sawt · صوت**](https://github.com/sawtgaza-star/sawt-backend) | Backend for a Gaza media platform for content creators, courses and storytelling (Laravel 11, Filament 3). It has a versioned REST API (`/api/v1`), a bilingual RTL admin dashboard with roles and permissions, and Instagram Graph API reels with concurrent per-reel insights and caching. It also has PayPal one-off payments, subscriptions and donations with verified webhooks, a multi-step "support Sawt" wizard, JWT auth and queued email notifications. |
| [**helpdesk-api**](https://github.com/mohammed-a-ashqar/helpdesk-api) | Node.js / TypeScript service-desk API (Fastify, Drizzle ORM, PostgreSQL) with a ticket lifecycle state machine, SLA tracking that pauses while waiting on the customer, least-loaded auto-assignment, RBAC, JWT + Argon2id and OpenAPI docs. 157 tests on in-process Postgres (PGlite), CI. |
| [**invoice-system**](https://github.com/mohammed-a-ashqar/invoice-system) | Laravel 12 + Livewire invoicing & receivables app: invoices with line items, partial payments, credit notes with restocking, derived statuses, PDF documents, reports and role-based access. 88 tests, CI. |
| [**laravel-payment-gateways**](https://github.com/mohammed-a-ashqar/laravel-payment-gateways) | Laravel package that puts Stripe, PayPal and WaafiPay (East-African mobile money) behind one API. It has a Money value object, idempotent requests, signature-verified webhooks turned into Laravel events, and `Payments::fake()` for tests. 212 tests, PHPStan at max level, CI on PHP 8.2–8.4 × Laravel 11/12. |
| [**portfolio-cms**](https://github.com/mohammed-a-ashqar/portfolio-cms) | Laravel 12 bilingual (EN/AR, RTL) CMS. Actions, DTOs, repositories behind interfaces, strategy pattern for pricing and video providers, an enum-driven state machine, 62 tests, CI. |

### 🔒 Private projects (client & company work)

Most of my production work belongs to employers and clients, so the repositories are private. Here is what I built and my role in each:

| Project | Domain | Stack | My role & highlights |
|---|---|---|---|
| **Danab** | Fault-reporting & ticketing for an electricity provider | Laravel 12, React + Inertia, TypeScript, REST API, GitHub Actions | Co-developed the backend: ticket assignment, field-staff workflows, mobile APIs, Excel import/export, API docs |
| **HomeKey** | Real-estate marketplace (web + mobile app) | Laravel 11, Passport, REST API, Telescope | Built the backend: property approval flow, agent subscriptions, mobile APIs, **WaafiPay** mobile-money payments |
| **Wefrh Assistant** | Companion API platform for a marketplace app | Laravel 11, Filament, Passport, versioned REST API | Co-developed: cached repository layer, API gateway, auditing, SMS integration, Postman docs |
| **Hilal · Karoto · Tullana** | Multi-vendor e-commerce (web + mobile) | Laravel, REST API | Extended the platforms with custom APIs, coupon and banner systems and client-specific features |
| **Fajr Relief** | Donation & fundraising | Laravel 10, Sanctum API | Integrated a third-party donation / payment API through a dedicated service layer |
| **MDM** | Invoicing system & company websites | Laravel, Livewire, Filament | Built the invoicing system (invoices, credit notes, payment tracking) and the Filament-based company CMS |

<sub>Code is private under client agreements; happy to walk through the architecture in an interview.</sub>

### Languages

Arabic (native) · English (C1) · Turkish (B1)

📫 mohammedname2002@gmail.com · [LinkedIn](https://www.linkedin.com/in/mohammed-a-ashqar)
