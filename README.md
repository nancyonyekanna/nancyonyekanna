# Nancy Onyekanna

### Senior Full Stack Software Engineer — Laravel · Fintech · Real-time systems

📍 Agbor, Delta State, Nigeria · Open to remote · Founder & Lead Engineer @ **Naxfront Ltd**

Full stack engineer with **6+ years** building and operating production web systems,
specialising in **PHP/Laravel backends and financial-transaction infrastructure** —
escrow, payments, wallets, and the settlement logic that has to be correct when money
moves. I **own systems rather than tickets**: I make the architecture calls, tune
what's slow, harden what handles money, and document it so a team can build on it.
Comfortable across backend, frontend, and infrastructure, with a bias toward
correctness in domains where money and user trust are at stake.

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazonwebservices&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)

---

### 🔭 Featured projects

Engineering showcases — architecture, methodology, and selected code. Proprietary
logic (settlement/fee formulas, trading signals, tuned parameters) is intentionally
withheld; all credentials are stripped.

**[game-staking-platform](https://github.com/nancyonyekanna/game-staking-platform)** · `Laravel` · `MySQL` · `Redis` · `Pusher`
Competitive-gaming marketplace on Laravel: multi-currency **wallets & ledger**, P2P
**escrow** with disputes, a **matchmaking** queue, and **auto-generated
single-elimination tournaments** — settled idempotently across **7+ payment gateways**
with KYC/2FA and real-time updates.

**[algo-trading-infrastructure](https://github.com/nancyonyekanna/algo-trading-infrastructure)** · `Python` · `asyncio` · `C#`
Automated multi-broker futures trading platform. An async engine routes signals to
**four brokers** (NinjaTrader, MT5/FTMO, Interactive Brokers, Tradovate) over a ZeroMQ
transport across two networked nodes, behind a 12-check risk manager and a prop-firm
consistency governor — with a FastAPI operations dashboard and a restart-safe reconciler.

**[market-structure-research](https://github.com/nancyonyekanna/market-structure-research)** · `Python` · `pandas` · `FastAPI`
Systematic-trading research toolkit: instrument-parallel backtesting, **walk-forward
(in-sample/out-of-sample) validation**, a locked-case regression harness, and a
**causal, no-look-ahead simulator** — plus a zero-build web chart viewer.

> My primary production system — **Naxcrow** ([naxcrow.com](https://naxcrow.com)), an
> escrow & payments platform with an audit-grade transaction ledger, KYC, and
> Paystack/Flutterwave integrations — is private, but I'm happy to walk through the
> architecture on request.

---

### ⚙️ How I work

- **Correctness first** in money-moving code — strict consistency across every
  transaction, idempotent payments (no double settlements), and audit-grade logging
  that makes reconciliation and disputes traceable end to end.
- **Design for failure** — webhook idempotency and recovery paths for failed/partial/
  duplicated transactions, restart reconciliation, and kill-switches.
- **Make it fast, ship it predictably** — query tuning, indexing, and Redis caching;
  heavy work moved off the request cycle into queued jobs; Dockerised CI/CD.

---

### 🛠️ Tech

| | |
|---|---|
| **Backend** | Laravel · PHP · REST API design · auth & RBAC · queues & background jobs · WebSockets · webhooks |
| **Databases** | MySQL · schema design & normalisation · query optimisation · indexing · Redis |
| **Frontend** | JavaScript (ES6+) · Blade · responsive UI · dashboards & data-view interfaces |
| **DevOps & Cloud** | Docker · Git/GitHub · CI/CD · AWS · VPS & Nginx · cPanel |
| **Payments & Identity** | Paystack · Flutterwave · KYC / identity-verification APIs |
| **Testing & Quality** | PHPUnit / Pest · code review · structured logging · production debugging |
| **Also** | Python (systematic-trading & data tooling) · system architecture · performance tuning · technical documentation |

---

### 💼 Experience

**Founder & Lead Full Stack Engineer — Naxfront Ltd** · 2024–present
Own the full technical architecture of the company's fintech products: a secure
**escrow & transaction engine** (deposits, withdrawals, holds, releases with strict
consistency), **audit-grade financial logging**, **Paystack/Flutterwave** integrations
with idempotency and recovery paths, **KYC** and multi-layer validation, Dockerised
CI/CD, and VPS/Nginx operations.

**Full Stack Software Engineer — Independent / Contract** · 2018–present
Delivered production apps across fintech, online gaming, and business operations —
REST API design, relational data modelling, auth/RBAC, and production incident
resolution (race conditions in transaction handling, performance bottlenecks),
through build, deployment, and ongoing support.

---

### 🎓 Education & Certifications

- **B.Sc. Nursing Science** — Ambrose Alli University (2016–2021). Self-taught
  engineer; shipping production web systems since 2018 and full-time in software since.
- **Google Data Analytics** — Professional Certificate (2026)

---

### 📫 Reach me

- ✉️ nancyonyekanna2@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/nancy-onyekanna-44555b178)
- 🌐 [naxfront.com](https://naxfront.com)

<sub>Correctness, clean architecture, and systems that hold up when money and user trust are at stake.</sub>