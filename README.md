# Hi, I'm Minwoo Park 👋

AI Engineer building agentic, multi-agent tooling and the data systems underneath it. MISM (Business Intelligence & Data Analytics, AI Management concentration) at Carnegie Mellon University, Aug 2026 to Dec 2027.

Most recently the sole engineer on a production AI expense platform at Accuver America (Python, Flask, SQLite, Docker): receipt OCR, statement matching, 729 merged PRs, a 5,100+ test suite behind CI gates, and a Gemini-to-Claude fallback chain benchmarked against a 90-receipt golden set.

  
## What I Work With

- **LLM / AI:** RAG, prompt caching, structured output, multi-agent orchestration, LLM evaluation and golden-set benchmarking, LangChain, Anthropic / OpenAI / Gemini APIs, MCP, ChromaDB, OCR extraction, Text-to-SQL
- **Data & Engineering:** Python (Flask, pytest, pandas, scikit-learn), SQL (SQLite, MySQL, DuckDB, PostgreSQL / Supabase), R (caret, glmnet), Java, Docker, GitHub Actions, Playwright, Streamlit, React, Power BI (DAX), process mining (ProDiscovery)
- **Certifications:** AWS Certified AI Practitioner, AWS Certified Cloud Practitioner, Lean Six Sigma Yellow Belt

  
## Recent Work

- **AI Expense Platform** (Accuver America, 2026): receipt OCR, statement parsing, receipt-to-statement matching and exception flagging that cut reconciliation time 90%+; benchmarked 7 LLMs, cut LLM cost ~90% with prompt caching, shipped nine schema migrations on the live database with rehearsed drills
- **Weekly finance tooling** (Accuver America): rolling sales forecast automation (about 6 hours of weekly manual work to a one-minute run), a DuckDB + Streamlit revenue-forecast comparison tool with a guarded Text-to-SQL assistant, and a Salesforce pipeline change tracker
- **5G-domain RAG prototype** (Accuver America): LangChain + ChromaDB + Claude over 7 standards whitepapers (~700 chunks) with a Streamlit UI
- **Sustainability data audit** (Andersen Corporation, 2025): Python + Power BI data-integrity audit across 50+ sites and 20+ vendors that surfaced $20K+ in duplicate billing and weighing errors
- **Process mining** (PuzzleData, 2024): 3M+ funnel log rows on a life-insurance engagement whose recommendations lifted final-stage conversion 5%; led a procurement proof of concept (1,200+ events, ~80-85% conformance)

  
## Featured Projects

- **[Sharday](https://oursharday.com)**: collaborative 2-4 person travel planner (React 19, Supabase with RLS, Edge Functions, realtime sync, Cloudflare Pages); 251 commits, 19 migrations, used by 5 people
- **[Walmart Purchase Prediction](https://github.com/minwoo-data/walmart-sales-forecasting)**: regression model comparison in R (linear, ridge, lasso, RF, GBM) on 550K+ transactions; log-linear best at R² 0.74
- **[Process Mining Portfolio](https://github.com/minwoo-data/process-mining-portfolio)**: procure-to-pay event log from three systems, discovery and conformance checking (~80-85%)
- **[보다 (boda)](https://github.com/minwoo-data/boda)**: vision OCR (Gemini to Claude) that turns receipt images into structured expense data and Excel

  
## Claude Code Tooling

Seven open-source plugins for [Claude Code](https://claude.com/claude-code), used throughout the 729-PR Accuver codebase and adopted by the successor engineer:

**Parallel workflow**
- **[ddaro](https://github.com/minwoo-data/ddaro)**: worktree-based parallel workflow with deletion-aware staging, crash-recoverable context, and CI-orchestrated merges

**Multi-model review**
- **[prism](https://github.com/minwoo-data/prism)**: multi-angle code review, 5 parallel agents plus a singleton verifier pass
- **[triad](https://github.com/minwoo-data/triad)**: 3-perspective deliberation (clarity, longevity, comprehension) until consensus
- **[mangchi](https://github.com/minwoo-data/mangchi)**: cross-model code hardening, Claude writes while Codex CLI critiques one axis at a time
- **[prism-devil](https://github.com/minwoo-data/prism-devil)**: single-agent attacker-mindset review with auto-loaded checklists

**Deep research as verified RAG**
- **[batchim (받침)](https://github.com/minwoo-data/batchim)**: verification-gated research with an isolated verifier, 3-panel entailment checks, code-enforced span/number anchors, and a sha256-signed run ledger

**Receipts**
- **[boda (보다)](https://github.com/minwoo-data/boda)**: the vision OCR pipeline above, packaged as a plugin

**Technique cards (not counted above)**
- **[galmuri (갈무리)](https://github.com/minwoo-data/galmuri)** distills reusable techniques from a project into cards; **[knowledge](https://github.com/minwoo-data/knowledge)** is the library it writes to

  
## How I Work

I treat AI coding as an engineering system, not a single chat:

- **Parallel, isolated branches**: worktrees keep concurrent work from colliding ([ddaro](https://github.com/minwoo-data/ddaro))
- **Cross-model review gates**: Claude and Codex critique each other before anything merges ([prism](https://github.com/minwoo-data/prism), [triad](https://github.com/minwoo-data/triad), [mangchi](https://github.com/minwoo-data/mangchi))
- **Verification before trust**: research and retrieval must cite, anchor, and pass entailment checks, not just sound right ([batchim](https://github.com/minwoo-data/batchim))
- **Distill what works**: recurring solutions become reusable technique cards ([galmuri](https://github.com/minwoo-data/galmuri) to [knowledge](https://github.com/minwoo-data/knowledge))

  
## Contact

- Email: minwoo.park219@gmail.com
- LinkedIn: [linkedin.com/in/mp74484](https://www.linkedin.com/in/mp74484/)
- Portfolio: [minwoopark.dev](https://minwoopark.dev/)
