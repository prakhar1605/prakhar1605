# Hi, I'm Prakhar 👋

I build AI products end-to-end — agentic systems, RAG pipelines, and the full stack around them. Final-year **B.S. (Honors) in Data Science & AI at IIT Guwahati** ('27), currently doing multi-agent systems research at **RAIVN Lab, University of Washington**.

<a href="https://www.linkedin.com/in/prakhar-pandey-56267a2a2/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
<a href="https://prakhar-pandey-github-io.vercel.app"><img src="https://img.shields.io/badge/Portfolio-000?style=flat&logo=vercel&logoColor=white"/></a>
<a href="mailto:prakhar9999pandey@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white"/></a>
<a href="https://doi.org/10.5281/zenodo.21533560"><img src="https://img.shields.io/badge/Preprint-Zenodo-1682D4?style=flat&logo=zenodo&logoColor=white"/></a>

---

### Currently

**Research Intern · RAIVN Lab, University of Washington** *(Remote)* · Jul 2026 → present

Multi-agent web-browsing harness: up to 4 vision-language agents drive isolated Playwright browsers in parallel through a screenshot→action loop, with best-of-N selection over a pluggable judge (43 tests). Built a swappable policy layer with MolmoWeb-4B and Qwen-VL adapters — a 6-target grounding gate took the live Qwen3.5-27B adapter from 0/6 to 6/6 clicks by catching a coordinate-units bug before it could read as model error.

`Vision-Language Models` `Multi-Agent` `Playwright` `LLM Evals`

---

### Past

**Agentic AI Intern · Rowboat Labs (YC S24)** *(San Francisco — remote)* · May – Aug 2026

Shipped **Skills** into an open-source AI coworker platform (**15k+ ⭐**): agents load packaged instruction sets and tools on demand, so new capabilities ship as installable packages instead of core-code changes. Also shipped ChatGPT OAuth (OAuth 2.0 + PKCE) so users can run agents on an existing Codex subscription instead of separate API keys. 30+ PRs merged into a TypeScript-first production codebase, both co-founders reviewing.

`TypeScript` `Agent Orchestration` `MCP` `OAuth`

**Founding Engineer Intern · ThinkSpace AI** *(Singapore — remote)* · Dec 2025 – Mar 2026

Multi-document research assistant as an Electron desktop app: sentence-window RAG with citations anchored to exact page coordinates across 3 knowledge channels — PDF/DOCX, Google Drive, live web. Validated by a legal-advocate QA team against a ~100-question gold standard scoring factual and citation accuracy.

`LangChain` `RAG` `FastAPI` `Electron`

**AI Engineer Intern · Compeers AI** *(US — remote)* · Sep – Dec 2025

Two market-research tools for a B2B intelligence platform: a 4-module pipeline (Google Custom Search → PDF/CSV parsing → SEC EDGAR 10-K retrieval → Google Trends → SWOT comparison), and a Reddit audience profiler (PRAW, Laplace-smoothed uniqueness score, VADER) — 150 posts → 132 authors → 109 subreddits in a sample run.

`Python` `NLP` `Data Pipelines`

---

### Things I've shipped

**🎯 [CareerLift](https://carrerlift.in) — agentic AI career platform**
**5,000+ organic users.** LLM agents parse your resume, semantically match it against live job listings and 1,500+ IIT professor research roles, and return ranked roles with skill-gap analysis. The jobs pipeline refreshes 3,500+ Indian and international openings every 12–24 hours and pushes personalized email alerts — no manual curation, zero paid spend.

**🧠 [Drona AI](https://dronaai.in) — autonomous interview agent**
**1,000+ organic users, 500+ in the first two weeks.** Generates role-specific questions from an uploaded PDF, tunes difficulty from a rolling performance window, and streams a personalized feedback report. Re-architected from Streamlit to serverless Next.js on Vercel — replaced a ~500 MB ChromaDB + sentence-transformers stack with lightweight client-side scoring, same weak-area personalization at zero infra cost.

**🔌 [OpenCollab MCP](https://github.com/prakhar1605/Opencollab-mcp) — MCP server**
Open-source GitHub contribution matchmaker: skill-matched "good first issues", repo health scoring, PR plan generation. Zero-infra deploy via STDIO transport — installable through `uvx` in Claude Desktop and Cursor. MIT licensed.

---

### Research

**[Navigating Epistemic Parity in LLM Agents](https://doi.org/10.5281/zenodo.21533560)** — memory vs. skill conflict benchmark
Sole author · Zenodo preprint, Jul 2026 · [code](https://github.com/prakhar1605/epistemic-parity-bench)

A 52-scenario benchmark and eval harness measuring how agents resolve contradictions between injected memory and `SKILL.md` files. 1,383 deterministically-graded runs (3 models × 3 context orders) showed **no default precedence** between the two sources, and **silent resolution in 98.8%** of tool-call runs — agents pick a side and never say so.

---

### Stack I actually reach for

**AI / LLMs** — Python · LangGraph · LangChain · MCP · RAG · FAISS/ChromaDB · PyTorch · HuggingFace · Vision-Language Models · LLM Evals
**Backend** — FastAPI · Node.js · TypeScript · PostgreSQL · Supabase · Redis · MongoDB · Docker
**Frontend** — React · Next.js · Tailwind · Vercel
**DSA** — LeetCode 1710 (top 16.6%) · 1000+ problems

---

### How I think about building

Demos are easy. Products people come back to are hard. I optimise for the second one — shipped over polished, end-to-end over one nice slice, real users over screenshots.

If you're a founder or team building with LLMs and want a hand, my inbox is open.

<sub>Open to AI engineering opportunities. Remote preferred, but flexible.</sub>
