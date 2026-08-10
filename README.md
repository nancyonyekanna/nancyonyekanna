# Hi, I'm Nancy 👋

### Software engineer — systematic-trading infrastructure & production fintech platforms

I build the demanding parts of financial software: **real-time, multi-broker trade
execution**, **no-look-ahead backtesting**, and **full-stack platforms that move real
money** — wallets, escrow, and payments. I care about correctness under load, clean
architecture, and systems that stay honest and survive production.

---

### 🔭 Featured work

**[algo-trading-infrastructure](https://github.com/nancydev244-netizen/algo-trading-infrastructure)** · `Python` · `C#`
Automated multi-broker futures trading platform. An async engine routes signals to
**four brokers** (NinjaTrader, MT5/FTMO, Interactive Brokers, Tradovate) over a
ZeroMQ transport spanning two networked nodes, behind a 12-check risk manager and a
prop-firm consistency governor — with a FastAPI operations dashboard and a
restart-safe state reconciler.

**[market-structure-research](https://github.com/nancydev244-netizen/market-structure-research)** · `Python` · `FastAPI`
Systematic-trading research toolkit. Instrument-parallel backtesting with
walk-forward (in-sample/out-of-sample) validation, a locked-case regression harness,
and a **causal, no-look-ahead simulator** — proven byte-identical to the live engine
— plus a zero-build web chart viewer for auditing every read bar-by-bar.

**[game-staking-platform](https://github.com/nancydev244-netizen/game-staking-platform)** · `Laravel` · `PHP`
Competitive-gaming marketplace on Laravel — multi-currency **wallets & ledger**, P2P
**escrow** with disputes, a **matchmaking** queue, and **auto-generated
single-elimination tournaments**, settled idempotently across **7+ payment gateways**
with KYC/2FA and real-time updates over Pusher.

> These repositories are curated portfolio showcases. Proprietary logic — trading
> signals, tuned parameters, and settlement/fee formulas — is intentionally excluded;
> the code shown is illustrative, and all credentials are withheld.

---

### ⚙️ How I work

- **Correctness first.** For backtesting I built a simulator where look-ahead is
  *impossible by construction* — a single clock hands strategies only past data —
  and gated it with a golden-master oracle and differential-equivalence tests.
- **Design for failure.** Gap-detection and back-fill on the data feed, restart
  reconciliation, idempotent money movement (no double payouts), kill-switches, and
  encrypted credentials at rest.
- **Clean boundaries.** Pluggable broker bridges behind one interface; a strategy
  layer that never knows which broker executes it; services that own each money-moving
  domain.
- **Measure honestly.** Walk-forward validation, robustness test suites, and results
  I can defend — no curve-fit numbers.

---

### 🛠️ Tech

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![asyncio](https://img.shields.io/badge/asyncio-3776AB?logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?logo=pandas&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white)
![ZeroMQ](https://img.shields.io/badge/ZeroMQ-DF0000?logo=zeromq&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

**Domains:** real-time systems · algorithmic trading · backtesting & simulation ·
payments & wallets · risk management · API & broker integrations

---

### 📫 Reach me

- ✉️ **support@naxfront.com** · **nancydev244@gmail.com**

<sub>Correctness, clean architecture, systems that hold up under real load.</sub>
