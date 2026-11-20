<h1 align="center">Hi, I'm Raj Chhapariya</h1>
<h3 align="center">AI / Data Engineer building reliable data and LLM systems</h3>

<p align="center">
  I design and evaluate evidence-grounded RAG pipelines, in-process analytical engines with DuckDB, and robust data platforms — backed by production full-stack engineering to take systems to real users.
</p>

<p align="center">
  <a href="https://rajchhapariya.space"><img src="https://img.shields.io/badge/Portfolio-rajchhapariya.space-1F3864?style=flat-square" alt="Portfolio" /></a>
  <a href="https://www.atsroast.com"><img src="https://img.shields.io/badge/Product-Resume%20Roaster-1F3864?style=flat-square" alt="Resume Roaster" /></a>
  <a href="mailto:rajchhapariya8@gmail.com"><img src="https://img.shields.io/badge/Email-rajchhapariya8%40gmail.com-1F3864?style=flat-square" alt="Email" /></a>
  <a href="https://www.linkedin.com/in/rajchhapariya/"><img src="https://img.shields.io/badge/LinkedIn-Raj%20Chhapariya-1F3864?style=flat-square" alt="LinkedIn" /></a>
  <a href="https://x.com/raj_chhapariya"><img src="https://img.shields.io/badge/@raj__chhapariya-1F3864?style=flat-square&logo=x&logoColor=white" alt="X" /></a>
</p>

---

### What I'm Building

**[Resume Roaster](https://www.atsroast.com)** — Founder & Developer *(2026 – Present)*  
AI-powered ATS resume optimizer and career studio built with Next.js, TypeScript, Supabase, the OpenAI API and Razorpay. Includes a free ATS-style resume scanner (layout and section heuristics with guidance on common ATS pitfalls), a bullet rewriter, a cover letter generator, an AI mock-interview simulator, and PDF/DOCX export. Live with a free tier and one-time paid plans.

---

### Featured Projects & Systems

| Project | Description | Primary Stack |
|---|---|---|
| **[Truly](https://trulyapp.online)** | Small-group social platform built around structured 60-minute video circles. Overbooking is blocked by an atomic conditional UPDATE (`booked_count < capacity`) inside a transaction, side effects go through a transactional outbox with a cron drain, IDs are UUIDv7. Tested with Vitest and Playwright E2E. Live at [trulyapp.online](https://trulyapp.online). | Next.js 15 · React 19 · TypeScript · Neon PostgreSQL · Drizzle ORM · Vitest · Playwright |
| **[Agentic RAG Knowledge Assistant](https://github.com/Rajchhapariya/Agentic-RAG-Knowledge-Assistant)** | Autonomous RAG system with query decomposition, hybrid lexical/vector search (BM25 + NumPy RRF $k=60$), atomic claim evidence auditing, and 90 automated test functions; refused 4/4 adversarial unanswerable questions (0 hallucinations) where naive hybrid RAG answered all 4. | Python · OpenAI API · Rank-BM25 · Pydantic · Streamlit |
| **[Turbine AvgEGT Regression](https://github.com/Rajchhapariya/AvgEGT_Prediction_Project)** | Industrial turbine engine Exhaust Gas Temperature (AvgEGT) regression for predictive maintenance ($R^2 = 0.9136$, RMSE = 10.83°C) with strict data leakage elimination. | Python · XGBoost · Scikit-learn · Pandas · Telemetry Analytics |
| **[Customer Churn & Retention Modeling](https://github.com/Rajchhapariya/Customer-Churn-Prediction)** | End-to-end subscriber churn risk modeling on 7,043 customer accounts using SMOTE and Random Forest (ROC-AUC: 0.823) with standalone CLI inference. | Python · Scikit-learn · Imbalanced-Learn · Random Forest · Seaborn |
| **[AI Data Analyst Agent](https://github.com/Rajchhapariya/AI-Data-Analyst-Agent)** | Autonomous tabular analytics agent with in-process DuckDB columnar OLAP, regex-based read-only SQL guard (35 blocked keywords), and numerical faithfulness verification. | Python · DuckDB · Plotly · Streamlit · Pandas |
| **[EdgeFed-Bench](https://github.com/Rajchhapariya/edgefed-bench)** | Benchmark testing whether INT8 quantization of client updates weakens Byzantine-robust aggregation (Multi-Krum, coordinate median, trimmed mean) under sign-flip, Gaussian, ALIE and IPM attacks. INT8 cuts uplink 75%; at 20% sign-flip Multi-Krum holds 85.03% (INT8) vs 85.01% (Float32) over 10 seeds with Holm-corrected paired tests. Client shards stored as Parquet, read via DuckDB. | Python · PyTorch · DuckDB · PyArrow · NumPy |
| **[taxi-stream-bench](https://github.com/Rajchhapariya/taxi-stream-bench)** | Streaming sink benchmark on NYC Yellow Taxi data: at-least-once vs offset-keyed effectively-once delivery into a Parquet lake, hard-killed 10 times per run on a live 6-partition Redpanda cluster. Effectively-once wrote 0 duplicate rows; at-least-once averaged 666.7 duplicates per run (3 seeds, 10 SIGKILLs per run). Parquet compaction (806 files to 1) made queries 9.3x faster. | Python · Redpanda (Kafka API) · DuckDB · Parquet · Docker |
| **[tf-misconfig-scanner](https://github.com/Rajchhapariya/tf-misconfig-scanner)** | Static Terraform scanner for 12 AWS misconfiguration rules using `python-hcl2` AST parsing and variable resolution; emits UNKNOWN instead of guessing on dynamic expressions. Head-to-head vs Checkov 3.4.0: on 33 independent TerraGoat items, F1 1.000 vs 0.800 (recall 100% vs 66.7%); across all 106 scored items, including 73 author-written fixtures, F1 1.000 vs 0.878. Small sample; TerraGoat is from Checkov's vendor. | Python · python-hcl2 · Terraform · AWS · pytest |
| **[JanDarshan](https://github.com/Rajchhapariya/JanDarshan)** | Independent political and legislative information platform covering Indian MPs and ministers, with data sync and cleaning scripts, an India state map, and Hindi/English i18n. Live at [jan-darshan.vercel.app](https://jan-darshan.vercel.app). | Next.js · TypeScript · MongoDB · Mongoose · react-simple-maps · d3-geo |
| **[VyaparStack](https://vyaparstack-nine.vercel.app)** | GST invoicing app for Indian freelancers: Section 31 invoices with automatic CGST/SGST/IGST split, UPI QR codes, and PDF generation. | Next.js · TypeScript · Drizzle ORM · Neon PostgreSQL · pdf-lib |
| **[MandateStack](https://subs-sync.vercel.app)** | Recurring-billing platform for Indian businesses: Razorpay subscription mandates over UPI AutoPay, webhook handling, cron payment reminders, and WhatsApp notifications via Twilio. | Next.js · TypeScript · Supabase · Razorpay · Twilio · pdf-lib |
| **[Aarohana Trails](https://aarohanatrails.com)** | Freelance build for a trekking company: departure booking with an atomic conditional seat increment, a TipTap-based admin CMS, trek itineraries with Leaflet maps, and Sentry monitoring. | Next.js 16 · TypeScript · PostgreSQL · Prisma ORM · Tailwind CSS |
| **Namma Metro Guide** | Android transit navigation guide for Bengaluru Namma Metro with route planning, fare estimation, and interchange mapping. | Kotlin · Jetpack Compose · Room · Maps Compose · Firebase |

---

### Background & Operating Principles

- **Deterministic Guardrails First**: I prioritize architectural guardrails (read-only SQL keyword filtering, Pydantic validation, and post-generation evidence checks) over unconstrained LLM output.
- **Measured, Not Assumed**: My AI and data projects ship with automated tests and reported metrics, compared against a baseline where one exists.
- **Real-World Business Grounding**: Before going full-time on software, I ran my own restaurant in Varanasi (2025). I build with real business constraints and costs in mind.

---

### Technical Skills

- **Languages:** Python · TypeScript · SQL
- **Data & ML:** Pandas · NumPy · scikit-learn · XGBoost · PyTorch · DuckDB
- **LLM Systems:** OpenAI API · RAG (BM25 + dense retrieval) · Pydantic
- **Web & Databases:** Next.js · React · PostgreSQL (Neon, Supabase) · MongoDB · Drizzle · Prisma
- **Testing & Infra:** pytest · Vitest · Playwright · Docker · Kafka API (Redpanda) · Git

---

### Connect with Me

- **Portfolio & Case Studies:** [rajchhapariya.space](https://rajchhapariya.space)
- **LinkedIn:** [linkedin.com/in/rajchhapariya](https://www.linkedin.com/in/rajchhapariya/)
- **X:** [x.com/raj_chhapariya](https://x.com/raj_chhapariya)
- **GitHub:** [github.com/Rajchhapariya](https://github.com/Rajchhapariya)
- **Email:** [rajchhapariya8@gmail.com](mailto:rajchhapariya8@gmail.com)
