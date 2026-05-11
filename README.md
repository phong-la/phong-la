---

<h1 align="center">Hi 👋, I build AI infrastructure that ships</h1>
<p align="center">
  <em>CEO @ Genation — AI policy enforcement that blocks violations before they hit your LLM bill</em>
</p>
<p align="center">
  <a href="https://platform.genation.ai"><img src="https://img.shields.io/badge/Genation-live-blue" alt="Genation"></a>
  <a href="https://www.linkedin.com/in/phongla-work"><img src="https://img.shields.io/badge/LinkedIn-connect-blue?logo=linkedin" alt="LinkedIn"></a>
  <a href="https://blog.phongla.dev"><img src="https://img.shields.io/badge/Blog-read-orange" alt="Blog"></a>
</p>

---

### What I'm Building
**Genation** — an AI gateway that enforces custom content policies at the prompt level. Instead of sending every user request to an expensive LLM guard and *then* to a frontier model, Genation runs a custom cross-encoder NLI model on CPU in <strong><10ms</strong> to catch policy violations early. Multi-layer cascade: mini model → flag → LLM guard → safe/block → LLM.
- **7 modules, 11K+ LoC** — API key management, billing, usage tracking, policy engine, model routing, completions proxy, security guard
- **Custom cross-encoder** — 3-class NLI (entail/neutral/contradict), per-clause decomposition, ONNX + INT8 for CPU deployment
- **Stack**: Deno, TypeScript, Hono, PostgreSQL, Drizzle ORM, Valkey/Redis, BullMQ, PyTorch, ONNX, Docker, Kubernetes
---
### Before Genation
| Venture | What | Traction |
|---|---|---|
| **HippoPenny LLC** (US) | AI-powered mobile game studio | Wacky Warper (and more): 200K+ downloads |
| **Laristo LTD** (UK) | Social platform for perfume enthusiasts | perfumerates.com — 92K perfume dataset, 40K daily organic visits (US-heavy), 1.2M monthly requests |
| **E-commerce** | Facebook-based online business | 300K-member community |

Each one shipped, got real users, generated revenue, and taught me something about building products people actually use.

---

### Competitive Programming
<p>
  <img src="https://img.shields.io/badge/ICPC-National%20Silver-blue" alt="ICPC Silver">
  <img src="https://img.shields.io/badge/Provincial%20Champion-2×%20Gold-gold" alt="Provincial Champion">
  <img src="https://img.shields.io/badge/Olympic%2030%2F4-2×%20Gold-gold" alt="Olympic 30/4">
  <img src="https://img.shields.io/badge/National%20Youth%20Informatics-2nd%20Prize-silver" alt="Youth Informatics">
</p>
Represented Vietnam in algorithmic competitions across high school and university. ICPC Vietnam National Silver (top ~30 teams out of 300+). Consistent podium finisher at national and regional levels over multiple years.

---

### Research
- **IEEE NICS 2020** — First author: *"Vehicle Counting: Survey and Experiments"* — peer-reviewed, published on IEEE Xplore
- **Cross-encoder BYOP** — 4.8K-sample Vietnamese NLI dataset for AI policy enforcement, custom training pipeline, arXiv preprint (in progress)

---

### Writing
I write about building AI infrastructure in production, ONNX deployment, content safety, and solo-founder engineering on my [blog](https://blog.phongla.dev) and [LinkedIn](https://linkedin.com/in/phongla-work).
Recent topics:
- Cross-encoder vs LLM for content policy enforcement
- Running transformer models on CPU at <10ms with ONNX
- Architecture decisions from building an AI gateway
- From 200K game downloads to AI security

---

### Technical Range

Languages:    TypeScript, Python, SQL

Backend:      Deno, Hono, Drizzle ORM, PostgreSQL, PgBouncer

Cache/Queue:  Valkey (Redis), BullMQ, atomic Lua scripts

ML/AI:        PyTorch, ONNX, HuggingFace, cross-encoder NLI, fp16 training

Infra:        Docker, Kubernetes, CloudFlare, SSE streaming proxy

Auth:         HMAC key auth, JWT/JWKS, API key management

---

### Let's Work Together
I help AI startups and enterprises optimize their inference pipelines, deploy models to production, and build content safety systems that actually ship.
**Currently open to**: fractional CTO, B2B consulting, and interesting AI infrastructure projects.
Reach out on [LinkedIn](https://linkedin.com/in/phongla-work) or [email](mailto:phongla.work@gmail.com).

---

<p align="center">
  <em>"I'm not just talking. I have production code, real users, and revenue."</em>
</p>
---
