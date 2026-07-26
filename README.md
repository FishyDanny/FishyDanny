# Danny Li

**Agentic engineer in Sydney.** I build LLM agent systems, and the full-stack products they run inside.

UNSW — Actuarial Studies + Computer Science. Currently shipping a rostering SaaS for Australian small
businesses, and open to agentic / AI engineering and full-stack roles.

📍 Sydney, Australia · 💼 [LinkedIn](https://linkedin.com/in/dannyxyli) · ✉️ dannyliworking@gmail.com

---

## What I'm building

**Minishift** — _private, commercial_ · Workforce management for Australian small businesses. The
interesting part is the scheduler: a Google OR-Tools CP-SAT service that treats AU labour rules as
hard constraints, so it will refuse to emit a roster that breaches the 12-hour daily cap, the 152-hour
monthly cap, or the 10-hour rest gap between consecutive-day shifts. Most SMB roster tools either
don't encode labour law at all or are priced for enterprise procurement.

React + Express + Postgres + Redis, with the solver as a separate Python/FastAPI microservice. Shift
trading marketplace, multi-tenancy, RBAC, Stripe subscriptions.

**Campsite Studios** — _private, commercial_ · Autonomous AI agents that run business operations from
Discord — voice command in, executed work and a report out. Subscription product on an agent
orchestration layer.

**[Recipe Browser](https://recipe-browser-lime.vercel.app)** — _live demo_ · Social recipe platform.
Pass a recipe by QR code, rescale quantities to any serving size, cook it hands-free with a
wake-locked step view. Next.js App Router, Prisma, Better Auth, Stripe, Playwright.

## Public code

| Project                                                                                      | What it is                                                                                                                                                                                                                                                                                     |
| -------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[Road Safety Risk Prediction](https://github.com/FishyDanny/Road-Safety-Risk-Prediction)** | Deep learning on 36 years of Australian crash data — Random Forest baseline vs. feedforward and residual networks, Bayesian hyperparameter tuning. Served behind a validated FastAPI endpoint with SHAP attribution, because a risk score you can't explain can't be justified to a regulator. |
| **[P2P DB Vault](https://github.com/FishyDanny/simple_file_sharing_server)**                 | Peer-to-peer file sharing — an `asyncio` Python server with optional TLS and a React/Electron desktop client, rewritten from a threaded implementation to compare the two concurrency models.                                                                                                  |

> Most of my commit history sits in private product repositories, so the graph is greener than this
> list is long. Happy to walk through any of the private work in detail.

## What I work with

**Languages** TypeScript · Python · SQL
**Web** Next.js (App Router) · React · Tailwind · Prisma · PostgreSQL
**AI/Agents** LLM agent orchestration · tool-use pipelines · MCP servers · prompt and eval workflows
**ML/Optimisation** TensorFlow/Keras · scikit-learn · SHAP · OR-Tools CP-SAT · pandas
**Testing** Playwright · Jest · pytest
**Ops** Docker · GitHub Actions · Vercel · Redis · Sentry · Stripe

## How I work

I lean hard on agentic tooling — most of what I ship is built with agents in the loop, with the
scaffolding (plans, standards, review gates) checked into the repo alongside the code. I care about
the boring parts that make that safe: typed boundaries, tests that actually run in CI, and secrets
that never reach a commit.

---

_Open to graduate and junior roles in agentic/AI engineering and full-stack product work — Sydney or remote._
