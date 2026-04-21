### Hi, I'm Tyler 👋

I'm a **Data Engineer at Entrata** based in Lehi, UT. I build pipelines, BI tooling, and AI-assisted developer tools — usually somewhere in the seam between **data infrastructure, LLMs, and quantitative analysis**.

- 🛠️  **Stack:** Python · SQL · Postgres · Redshift · Snowflake · Domo · FastAPI · React · Docker
- 🤖  **Currently exploring:** LLM-powered semantic layers, agentic BI workflows, and quant trading on prediction markets
- 📫  **Reach me:** [LinkedIn](https://www.linkedin.com/in/shepherd-tyler/)

---

### 🚀 Featured Projects

#### [`quant-kbtc`](https://github.com/TylerShep/quant-kbtc) — Kalshi BTC Trading Bot
Automated 15-minute prediction-market bot combining **Order Book Imbalance (OBI)** and **Rate of Change (ROC)** signals with **ATR volatility-regime filtering**, fixed-fractional position sizing, circuit-breaker risk controls, and a real-time React/TradingView dashboard. Includes a backtesting engine, walk-forward optimizer, and signal-decay monitoring (IC, Sharpe drift).
> `Python` · `FastAPI` · `WebSockets` · `React` · `TypeScript` · `Docker`

#### [`domo-semantic-layer-beast`](https://github.com/TylerShep/domo-semantic-layer-beast) — AI-Powered BI Documentation
Reads Beast Modes, card metadata, and Redshift connector SQL from any Domo instance and turns them into business-friendly markdown via any OpenAI-compatible LLM gateway (OpenAI, LiteLLM, OpenRouter, Azure). Read-only by design, with a Playwright auth fallback and Cursor IDE rules/skills for agentic analysis workflows.
> `Python` · `LLMs` · `Playwright` · `Domo API` · `Redshift`

#### [`domo-scheduled-ext-reporting`](https://github.com/TylerShep/domo-scheduled-ext-reporting) — Scheduled BI Delivery
YAML-driven, vendor-neutral tool that ships Domo cards, datasets, and rich messages to **Slack, Microsoft Teams, and email** on a cron schedule. Native REST engine with a JAR fallback, sandboxed `asteval` alert expressions, Jinja-templated copy, run history, Prometheus metrics, and an opt-in FastAPI web UI. **432 tests at 85.6% coverage.**
> `Python` · `FastAPI` · `APScheduler` · `htmx` · `SQLite/Postgres`

#### [`viz-wiz`](https://github.com/TylerShep/viz-wiz) — Conversational Data Exploration
Natural-language to SQL to chart, in one chat interface. Connects to **17+ data sources** (Postgres, Snowflake, BigQuery, Databricks, Redshift, Salesforce, NetSuite, Domo, and more), renders **22 chart types** with Recharts, and supports proactive clarification, zero-row recovery, and multi-model fallback (Claude, GPT-4o, Gemini). Includes dashboards, reports (doc + slide modes), and scheduled Slack delivery.
> `TypeScript` · `React` · `Python` · `FastAPI` · `Anthropic / OpenAI / Google AI`

#### [`cfb-data`](https://github.com/TylerShep/cfb-data) — College Football ETL Pipeline
Modular, extensible, tested ETL pipeline for the CollegeFootballData.com REST API into PostgreSQL. Built as a reference architecture for clean Python ETL patterns.
> `Python` · `PostgreSQL` · `REST APIs`
