CIS graduate from Cal State San Marcos, currently working as a web developer. I build things at the intersection of data engineering, full-stack development, and AI-powered tooling.
Show Image

Featured Projects

Data Process Analytics with AI for FastAIJobs
An end-to-end data platform built for FastAIJobs that detects newly funded startups from the news, scrapes their job boards, and surfaces opportunities on a single searchable site, so job seekers find roles at companies actively growing before anyone else does.
The platform is composed of two connected systems: a Funding Signals Pipeline that ingests RSS feeds (TechCrunch, GlobeNewswire), runs articles through a multi-stage ETL (prefilter → extract → classify → dedupe → score) using pure regex classification and a 7-rule weighted scoring model, then outputs structured leads with confidence ratings and a Job Aggregation Engine that concurrently scrapes 9 ATS platforms (Greenhouse, Lever, Ashby, etc.) via async Python, processes and deduplicates listings, and serves them through a static JSON-backed Next.js frontend deployed on Vercel.

My contributions:
Designed and audited the core job schema across pipeline phases
Built deduplication logic and indexed the dedup queue
Developed the analytics dashboard with tab navigation and Phase 7 visualizations (charts A–E)
Implemented a prefilter layer to reduce noise before enrichment
Fixed export report rendering and Unicode encoding issues
Python asyncio pandas Next.js TypeScript ETL RSS Regex Vercel JSON/JSONL

SOS — Support of Sale (Restaurant POS)
Full-stack restaurant point-of-sale system with real-time order management and role-based access control (BOH / FOH / Manager).

My contributions:
Scaffolded the Spring Boot backend and model classes
Fixed BOH and FOH dashboard views
React Spring Boot Node.js PostgreSQL Socket.io JWT Tailwind CSS

🛠️ Skills
Languages: Python, JavaScript, Java, SQL
Frontend: React, Vite, Tailwind CSS, HTML/CSS
Backend: Node.js, Express, Spring Boot
Data/DB: PostgreSQL, Prisma ORM, ETL pipelines
Tools: Git, Claude Code, WordPress, WP Engine

📫 Let's connect
LinkedIn → https://www.linkedin.com/in/jose-ortega-86b1153b8/
