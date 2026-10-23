## Hi, I'm Mohammad Sayyedi 👋

**Founder & Software Engineer** — I design, build and ship products end to end: architecture, backend, frontend, AI pipelines, DevOps and cloud.

- 🚀 Building AI-powered products for real users, from idea to production
- 🤖 Focus: LLM pipelines with grounding & human-in-the-loop review, data ingestion, automation
- ☁️ Shipping on Kubernetes, Docker, ArvanCloud, Firebase and Cloudflare with self-hosted CI/CD
- 🌍 Open to remote roles and relocation (Canada)

---

### 🛠️ Tech Stack

**Languages:** TypeScript · JavaScript · C# · SQL  
**Frontend:** React 19 · Vite · Next.js · Tailwind CSS  
**Backend:** Node.js · Express · REST APIs · background workers  
**Data:** PostgreSQL · Firebase Firestore  
**AI:** OpenAI API · Claude API · prompt engineering · RAG-style grounding  
**DevOps & Cloud:** Docker · Kubernetes · GitHub Actions (self-hosted runners) · ArvanCloud · Cloudflare Workers · Firebase  
**SEO / GEO:** structured data (JSON-LD) · sitemaps & news sitemaps · IndexNow · Google Indexing API · llms.txt

---

### 📂 Featured Projects

> Source code for these projects is private. Live demos and code walkthroughs are available on request.

#### 🌐 [MohajerX](https://mohajerx.com) — AI immigration news platform
Automated immigration intelligence for the 30 most popular destination countries, monitoring 150+ official government sources.
- Ingestion pipeline (RSS/Atom, HTML extraction, headless browser) with content-hash diffing so the LLM runs only when a source actually changes
- Anti-hallucination design: extraction-only prompts grounded in fetched source text, with every article reviewed by an editor before publishing
- Instant indexing (IndexNow + Google Indexing API), news sitemaps, FAQ schema and `llms.txt` for AI search engines
- Sequential article IDs via atomic Firestore transactions
- **Stack:** React 19, Vite, Express, Firebase, OpenAI, Docker, Cloudflare, GitHub Actions

#### 📊 Tarazoo (ترازو) — financial intelligence platform
Turns company disclosures from Codal (Iran's stock-market disclosure system) into clear, readable analysis: quarter-over-quarter and year-over-year comparisons and industry benchmarks.
- Web app + background worker + PostgreSQL, containerized on ArvanCloud
- Paid subscriptions with online payments; Telegram & Bale bots for news delivery
- **Stack:** TypeScript, Node.js, PostgreSQL, Docker, ArvanCloud

#### 💳 Dinarak (دینارک)
TypeScript product deployed on a Kubernetes cluster.

#### 🍽️ food1 · 🃏 Taash
TypeScript web apps, containerized and deployed on ArvanCloud with automated CI/CD.

#### 🎮 GameNet PC
C# desktop application for gaming-café PC management.

#### 🏢 Internal AI assistant
Company-wide internal AI chat portal for employees, built on ArvanCloud AI-as-a-Service.

---

### 📫 Get in touch
- 🌐 [mohajerx.com](https://mohajerx.com)
- 💼 Open to opportunities — feel free to reach out
