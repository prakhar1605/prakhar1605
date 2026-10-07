## Prakhar Pandey

**AI Product Engineer · TypeScript · Open Source · Agent Systems**

I build AI products from user problems through implementation, launch, and iteration. My work spans open-source agent tooling at Rowboat Labs, independently built products like CareerLift and Drona AI, and browser-agent research at the University of Washington.

30+ merged PRs at Rowboat Labs (YC S24). Solo-built CareerLift with 25,000+ organic users. Sole author of a paper accepted at a NeurIPS 2026 workshop.

B.S. (Honors) in Data Science & AI, IIT Guwahati · Expected August 2027.

[LinkedIn](https://www.linkedin.com/in/prakhar-pandey-56267a2a2/) · [Portfolio](https://prakhar-pandey-github-io.vercel.app/) · [LeetCode](https://leetcode.com/u/prakhar3104/) · [Email](mailto:prakhar9999pandey@gmail.com)

---

### Currently

**Research Intern — RAIVN Lab, University of Washington**  
*Remote · July 2026–Present*

Building multi-agent browser systems using vision-language models, Playwright, and Python. Implemented parallel execution with isolated browser contexts, best-of-N rollouts, and manager–worker task decomposition, reaching a 2.71× speedup on measured live runs.

Built model adapters and traced a grounding failure to a coordinate-normalization bug, improving a six-target check from 0/6 to 6/6 successful clicks.

### Previously

**Agentic AI Engineer Intern — Rowboat Labs (YC S24)**  
*San Francisco, Remote · May–August 2026*

Contributed 30+ merged PRs to a TypeScript/Electron open-source AI coworker platform, with both cofounders reviewing.

- Implemented Skills support so agents can load packaged instructions and tools on demand.
- Shipped ChatGPT OAuth 2.0 + PKCE, enabling users to connect an existing Codex subscription instead of managing separate API keys.
- Helped turn a community request for ChatGPT/Codex integration into a shipped product capability.

**Product Engineer Intern — ThinkSpace AI, Founding Team**  
*Singapore, Remote · December 2025–March 2026*

Built an Electron research assistant spanning PDF/DOCX, Google Drive, and live web search, with sentence-window retrieval and page-anchored citations. Evaluated with a legal QA team against a roughly 100-question gold standard.

**AI Engineer Intern — Compeers AI**  
*United States, Remote · September–December 2025*

Shipped two market-research tools for a B2B intelligence platform: an SEC EDGAR and Google Trends SWOT pipeline, and a Reddit audience profiler.

---

### Products & Open Source

**[CareerLift](https://carrerlift.in) — AI Career Platform**  
*25,000+ organic users · 100+ paid users within 15 days of premium launch*

Designed, built, and operate the product independently. Resume parsing, embeddings, vector search, and AI fit assessment help users find relevant jobs and research opportunities, with skill-gap analysis.

Automated a pipeline refreshing 3,500+ openings every 12–24 hours and sending personalized alerts.

*Next.js · TypeScript · Supabase · Vector Search · LLM APIs*

**[Drona AI](https://dronaai.in) — AI Mock-Interview Platform**  
*1,000+ organic users*

Built an adaptive interview product that generates role-specific questions from uploaded PDFs and adjusts difficulty based on performance. Re-architected from Streamlit to serverless Next.js, replacing a roughly 500 MB ChromaDB service with lightweight client-side scoring.

*Next.js · TypeScript · OpenRouter · Redis*

**[OpenCollab MCP](https://github.com/prakhar1605/Opencollab-mcp) — Open-Source Contribution Tools**

An MCP server that helps contributors find skill-matched issues, assess repository health, and plan contributions.

*Python · MCP · GitHub API · MIT License*

---

### Research

**[Navigating Epistemic Parity in LLM Agents](https://doi.org/10.5281/zenodo.21533560)**  
**Accepted at the NeurIPS 2026 workshop “Who Verifies the Agents?”**  
*Sole author · Workshop scheduled for December 2026 · Zenodo preprint available*

Built a 52-scenario benchmark studying how agents respond when injected memory conflicts with procedural skill instructions.

Across 1,383 deterministically graded runs, the tested models showed no consistent default precedence between the two sources. In 98.8% of tool-call runs, there was no accompanying explanation.

The work examines a practical reliability question: when an agent receives conflicting guidance, what does it actually do, and how can we verify that behaviour?

[Paper](https://doi.org/10.5281/zenodo.21533560) · [Code & Data](https://github.com/prakhar1605/epistemic-parity-bench)

---

### Stack

**Product engineering:** TypeScript, JavaScript, Python, SQL, React, Next.js, Electron, Node.js, FastAPI.

**Agents & AI:** Tool calling, MCP, multi-agent orchestration, RAG, LLM evaluation, vision-language agents, LangGraph, LangChain.

**Data & infrastructure:** PostgreSQL, Supabase, Redis, Docker, Vercel, GitHub Actions, Playwright.

**ML & post-training:** PyTorch, Hugging Face, TRL, LoRA, SFT, GRPO.

1,000+ LeetCode problems solved.

---

Open to AI product engineering opportunities, especially developer tools, agent infrastructure, and applications with real users.

[Get in touch](mailto:prakhar9999pandey@gmail.com)
