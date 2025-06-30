
<p align="center">
  <img src="https://silver-comparable-dolphin-329.mypinata.cloud/ipfs/bafybeie5azvjqqgct3m6gauekudqe2at2ptx74qjdpaadilveko5qihgnu" alt="Copil — DeFi’s Copilot" width="640">
</p>

<h2 align="center"><i>DeFi’s Copil'ot</i></h2>

Copil is an **AI‑powered DeFi automation platform** that lets you design, test, and run cross‑chain strategies trades, swaps, portfolio balances, and on‑chain alerts from a single FastAPI backend.

### Why Copil?

* **Autonomous Workflows** — Trigger‑action pipelines executed by Celery workers on a PostgreSQL/Redis backbone.
* **Cross‑Chain Reach** — Execute token swaps and liquidity strategies across major EVM networks via OneBalance SDK.
* **Secure Web3 Auth** — Wallet‑first sign‑in with Privy + JWT, encrypted key storage, and granular role policies.
* **AI at the Core** — Natural‑language agents (OpenAI, Anthropic, Amazon Bedrock) plan and optimise every DeFi task.
* **Modular & Extensible** — FastAPI + Pydantic v2 generate OpenAPI docs automatically.
* **Observability by Default** — Health endpoints, metrics, and Sentry error tracking keep production calm.

### Quick Start

```bash
git clone https://github.com/copilfi/copil.git
cd copil
make dev       # spins up API, workers & hot‑reload
```

#### Tech Stack at a Glance

| Layer           | Tech                                |
| --------------- | ----------------------------------- |
| API & Core      | FastAPI · Pydantic v2 · Uvicorn     |
| Data            | PostgreSQL · SQLAlchemy · Alembic   |
| Messaging       | Redis · Celery                      |
| Blockchain      | Web3.py · OneBalance SDK            |
| AI              | OpenAI · Anthropic · Amazon Bedrock |
| Auth & Security | Privy · Python‑JOSE · bcrypt        |
| Monitoring      | Sentry · Prometheus‑style metrics   |

