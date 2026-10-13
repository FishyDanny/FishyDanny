```console
danny@sydney ~ % whoami
danny li · software engineer · sydney, australia
unsw — computer science + actuarial studies, class of 2025

danny@sydney ~ % cat about.txt
I build full-stack products and the LLM agent systems
that run inside them. Most recently a software engineer
at Duo Tax (Jun–Aug 2026), moving the company off bought
SaaS onto systems I built and maintained.
Constraint solvers, typed boundaries, and tests that
actually run in CI.

danny@sydney ~ % ls -l ~/shipping
drwx------  minishift/       rostering SaaS; CP-SAT scheduler refuses illegal shifts
drwx------  tallyproof/      bank-statement PDFs to CSV, checked against the balance
drwxr-xr-x  yapfeed/         short public-domain audio on Cloudflare Pages + D1
drwxr-xr-x  road-safety/     crash-type models behind a FastAPI + SHAP endpoint
drwxr-xr-x  p2p-db-vault/    asyncio file sharing with TLS and an Electron client
drwx------  recipe-browser/  recipes that survive being shared

danny@sydney ~ % cat stack.toml
languages = ["typescript", "python", "sql"]
web       = ["react", "next.js", "express", "prisma", "postgres", "redis"]
cloud     = ["aws", "cloudflare", "vercel", "docker"]
ml        = ["tensorflow", "scikit-learn", "shap"]
solvers   = ["or-tools cp-sat"]
agents    = ["claude code", "opencode", "ollama"]
testing   = ["playwright", "vitest", "jest", "pytest"]

danny@sydney ~ % ./hire-me --status
open to software engineering roles · full-stack, backend, AI
sydney or remote
mail  dannyliworking@gmail.com
in    linkedin.com/in/dannyxyli

danny@sydney ~ % ▊
```

### Selected work

| Project | What it is | Links |
|---|---|---|
| **Minishift** | Rostering for Australian shift crews. Began as my UNSW COMP3900 capstone with a team of five, where I built the OR-Tools CP-SAT autoscheduler. Solo since January 2026: self-hosted Postgres, Redis and JWT auth, Stripe billing, security hardening. | [Live](https://minishift-zeta.vercel.app) · code private |
| **Tallyproof** | Converts PDF bank statements to CSV, Xero, QuickBooks, OFX or QIF in the browser. Nothing is uploaded, and every row is checked against the running balance. | [Live](https://tallyproof.pages.dev) · code private |
| **Yapfeed** | A no-account feed of short, credited public-domain audio. Cloudflare Pages Functions and D1, offline prefetch, and podcast RSS import behind a human review queue. | [Live](https://s72-yapfeed.pages.dev) · [Code](https://github.com/FishyDanny/yapfeed) |
| **Road Safety Risk Prediction** | UNSW ACTL3143 project classifying 57,430 Australian road-fatality records as single- or multi-vehicle crashes. The Random Forest reached 0.806 AUC-ROC; served through FastAPI with SHAP explanations. | [Code](https://github.com/FishyDanny/Road-Safety-Risk-Prediction) |
| **P2P DB Vault** | A UNSW networking assignment rewritten as an asyncio peer-to-peer file sharing server, with optional TLS and a React/Electron client. | [Code](https://github.com/FishyDanny/simple_file_sharing_server) |
